## Inspiration

One in three teenage girls has felt unsafe walking home alone.
We've felt it too — that moment where your heart races, your 
palms sweat, and you wish someone just *knew* where you were.

We looked for solutions. Every app required a download. Every 
tool required WiFi. Every option required time — the one thing 
you don't have in an unsafe moment.

So we asked ourselves: **what if safety was just one tap away?**
No download. No login. No delay. Just one tap — and your circle 
protects you.

**We built SafeCircle because no girl should ever face that 
moment alone.**

---

## What it does

SafeCircle is a **free, browser-based personal safety web app** 
built specifically for teenage girls. It works on any phone 
browser — no installation, no account, no barriers.

In **one tap**, SafeCircle:

- 📍 Shares your **live location** with your trusted circle 
  of contacts
- 🔕 Sends a **silent SOS alert** via SMS — no one around 
  you knows you've asked for help
- 🤖 Activates an **AI safety advisor** powered by Claude API 
  for calm, real-time guidance
- 🔑 Delivers a **pre-set code word** to trusted contacts so 
  they know exactly what kind of help you need
- ⏱️ Fires in **under 2 seconds** — because every second counts

_No app download. No account needed. No WiFi required.
Works on any phone browser, anywhere in the world, for free._

---

## How we built it

We started with one rule: **if it takes more than one tap, 
it's too slow.**

Every design decision, every technical choice, every word on 
screen was made with that rule in mind.

```javascript
// One tap. One function. One second.
function activateSafeCircle() {
  getLocation();
  sendSilentSMS();
  activateAIAdvisor();
}
```

**Our tech stack:**

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Live Location | Browser Geolocation API |
| Silent SOS Alerts | Twilio SMS API |
| AI Safety Advisor | Claude API by Anthropic |
| UI/UX Design | Figma |
| Code & Collaboration | GitHub |

**Our process:**

1. **Research** — We interviewed teenage girls about their 
   safety experiences and what made them feel most vulnerable
2. **Design** — We wireframed every screen in **Figma**, 
   testing for panic-proof UX: large buttons, high contrast, 
   minimal text, one action per screen
3. **Build** — We built mobile-first in HTML, CSS, and 
   JavaScript so it works on any phone browser
4. **Integrate** — We connected Twilio for silent SMS alerts 
   and the Claude API for the AI safety advisor
5. **Test** — We tested with real teen girls under simulated 
   stress conditions and refined based on their feedback
6. **Deploy** — We hosted on GitHub Pages for free, 
   zero-barrier access

---

## Challenges we ran into

**⚡ Speed vs. silence**
Getting the alert to fire in under 2 seconds while staying 
completely silent was our hardest engineering challenge. Our 
solution: pre-load the geolocation request on page load, so 
there's **zero delay** the moment a girl taps the button.

**🎨 Panic-proof design**
We originally designed a 4-step flow. After testing with 
friends under stress, we realized 4 steps was 3 too many. 
We redesigned everything around a **single tap**. Every word 
on screen was rewritten for clarity under pressure — no 
jargon, no small text, no confusion.

**📵 No-install constraint**
Building real-time location sharing entirely inside a browser 
— without a native app, without push notifications — required 
creative use of the **Web Share API** and SMS fallbacks through 
Twilio to ensure alerts always reached trusted contacts.

**🤖 AI that stays calm**
Prompting the Claude AI advisor to give responses that are 
calm, clear, and actionable — not alarming — in high-stress 
situations required careful prompt engineering and extensive 
testing across different unsafe scenarios.

**🔒 Privacy by design**
We built SafeCircle so that location data is never stored on 
any server. It's sent directly to trusted contacts and 
immediately discarded — because a safety tool should never 
become a surveillance tool.

---

## Accomplishments that we're proud of

- ✅ A **fully working MVP** that loads on any phone browser 
  in under 3 seconds
- ✅ **Zero install barrier** — works on the oldest phones, 
  slowest connections, and most basic browsers
- ✅ An **AI safety advisor** that gives calm, context-aware, 
  real-time guidance during unsafe situations
- ✅ A **silent SOS system** that alerts trusted contacts 
  without anyone nearby knowing
- ✅ UI tested with **real teenage girls** and redesigned 
  based on their direct feedback
- ✅ **Privacy-first architecture** — no location data ever 
  stored on our servers
- ✅ Aligned with **5 UN Sustainable Development Goals**
- ✅ Built entirely by **girls in STEM**, for girls everywhere

---

## What we learned

> *"The best technology disappears."*

SafeCircle works best when a girl doesn't have to think about 
it — it just works, instantly, silently, and reliably.

**We learned that simplicity is the hardest thing to build.**
Cutting our flow from 4 taps to 1 took more work than building 
the original 4-tap version. Every removed step required more 
engineering, more testing, and more courage to delete something 
we'd worked hard on.

**We learned that building *for* your community means building 
*with* your community.** The girls we tested with didn't just 
give us feedback — they gave us perspective. They told us what 
fear actually feels like, and that changed everything about 
how we designed SafeCircle.

**We learned that the Claude API is incredibly powerful for 
social good.** Prompting an AI to be a calm, trustworthy 
safety companion — not just a chatbot — opened our eyes to 
what responsible AI can do for vulnerable communities.

**And most importantly — we learned that girls in STEM don't 
just study problems. We solve them.**

---

## What's next for SafeCircle — *One tap. Your circle protects you.*

SafeCircle started as a hackathon project.
It doesn't have to end there.

**Short term:**
- 🌐 **Multilingual support** — so every girl, in every 
  language, can access safety
- 📴 **Offline mode** — SOS alerts that work with zero 
  data connection via SMS-only fallback
- ♿ **Accessibility features** — voice activation and 
  screen reader support for girls with disabilities

**Medium term:**
- 🏫 **School partnerships** — integrating SafeCircle 
  into school safety programs and student ID systems
- 👨‍👩‍👧 **Guardian dashboard** — optional visibility 
  portal for parents of younger teens
- 📊 **Anonymous safety heatmaps** — community data to 
  identify unsafe areas and drive local policy change

**Long term:**
- 🌍 **NGO & UN partnerships** — scaling SafeCircle 
  through girls' safety organizations globally
- 🏛️ **Policy advocacy** — using SafeCircle data to 
  support legislation protecting girls in public spaces
- 💜 **SafeCircle Foundation** — making this permanently 
  free for every girl, everywhere, forever

---

## 🌱 UN Sustainable Development Goals

| Goal | How SafeCircle Addresses It |
|---|---|
| **SDG 3** — Good Health & Wellbeing | Protects girls' physical safety in real time |
| **SDG 5** — Gender Equality | Built by girls, for girls, closing the safety gap |
| **SDG 10** — Reduced Inequalities | Free and works on any device — no one left behind |
| **SDG 11** — Safe & Inclusive Communities | Strengthens community safety nets for girls |
| **SDG 16** — Peace, Justice & Strong Institutions | Empowers girls to seek help safely and discreetly |

---

*SafeCircle — One tap. Your circle protects you.*
