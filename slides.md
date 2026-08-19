---
theme: default
background: "#0b1220"
title: E-Bike & E-Scooter Safety
info: |
  E-Bike & E-Scooter Safety Message for Secondary Students
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: fade
mdc: true
css: unocss
---

<style>
:root {
  --asphalt: #0b1220;
  --asphalt-2: #131c2e;
  --caution: #f5a623;
  --caution-2: #ffd166;
  --stop: #e63946;
  --go: #2ec4b6;
  --paper: #f4f1ea;
}
.slidev-layout {
  background: var(--asphalt);
  color: var(--paper);
}
.slidev-layout h1, .slidev-layout h2, .slidev-layout h3 {
  color: var(--paper);
}
.card {
  background: var(--asphalt-2);
  border: 1px solid rgba(245,166,35,0.25);
  border-radius: 16px;
  padding: 1.4rem 1.6rem;
}
.rule-card {
  background: var(--asphalt-2);
  border-left: 6px solid var(--caution);
  border-radius: 12px;
  padding: 1.5rem 1.8rem;
}
.stop-card {
  border-left-color: var(--stop) !important;
}
.go-card {
  border-left-color: var(--go) !important;
}
.icon-badge {
  width: 64px;
  height: 64px;
  border-radius: 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: rgba(245,166,35,0.12);
  color: var(--caution);
  font-size: 32px;
  flex-shrink: 0;
}
.icon-badge.stop { background: rgba(230,57,70,0.12); color: var(--stop); }
.icon-badge.go { background: rgba(46,196,182,0.12); color: var(--go); }
.checklist-item {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  font-size: 1.15rem;
  padding: 0.5rem 0;
}
</style>

<!-- SLIDE 1: TITLE -->

<div class="flex flex-col items-center justify-center h-full">
  <div class="icon-badge mb-6" style="width:96px;height:96px;font-size:52px;">
    <Icon name="bike" />
  </div>
  <h1 class="text-5xl font-bold mb-4" style="color: var(--caution-2)">
    E-Bike & E-Scooter Safety
  </h1>
  <p class="text-xl opacity-80">A message for secondary students</p>
</div>

<div class="abs-br m-6 text-sm opacity-50">
  Ride smart. Ride responsibly.
</div>

---
transition: fade
---

<!-- SLIDE 2: INTRO -->

# Fun, Fast, and Freeing

<div class="grid grid-cols-2 gap-8 mt-8 items-center">
<div>

<v-clicks>

- E-bikes and e-scooters are a popular way to get to school, visit friends, and get around town
- They're convenient and fun...
- ...but they can also be **dangerous** when operated irresponsibly

</v-clicks>

</div>
<div class="flex justify-center">
  <Icon name="zap" size="6rem" style="color: var(--caution)" />
</div>
</div>

---
layout: center
transition: fade
---

<!-- SLIDE 3: KEY MESSAGE -->

<div class="text-center">
  <Icon name="gauge" size="4rem" style="color: var(--stop);" class="mb-6 mx-auto" />
  <p class="text-2xl opacity-70 mb-2">The most important thing to remember:</p>
  <h1 class="text-4xl font-bold leading-tight" style="color: var(--caution-2)">
    Your e-bike or e-scooter<br/>can go faster than you think.
  </h1>
  <p class="mt-8 text-xl opacity-80 max-w-2xl mx-auto">
    At higher speeds, you have less time to react — and a crash can result in
    serious injuries. Even a small mistake can have big consequences.
  </p>
</div>

---
transition: slide-left
---

<!-- SLIDE 4: HELMET -->

<div class="flex items-start gap-6">
  <div class="icon-badge go"><Icon name="hard-hat" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Wear a Helmet</h1>
    <p class="text-lg opacity-60">Every ride. Every time.</p>
  </div>
</div>

<div class="rule-card go-card mt-8 text-xl">
  A helmet is one of the simplest things you can do to protect yourself from
  a serious head injury.
</div>

---
transition: slide-left
---

<!-- SLIDE 5: SLOW DOWN -->

<div class="flex items-start gap-6">
  <div class="icon-badge"><Icon name="turtle" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Slow Down</h1>
    <p class="text-lg opacity-60">Speed kills the margin for error</p>
  </div>
</div>

<div class="rule-card mt-8 text-xl">
  Don't race your friends, show off, or push your e-bike or e-scooter to its
  maximum speed. Slow down around intersections, driveways, pedestrians, and
  crowded areas.
</div>

---
transition: slide-left
---

<!-- SLIDE 6: PAY ATTENTION -->

<div class="flex items-start gap-6">
  <div class="icon-badge"><Icon name="eye" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Pay Attention</h1>
    <p class="text-lg opacity-60">Eyes up, phone away</p>
  </div>
</div>

<div class="rule-card mt-8 text-xl">
  Put your phone away. Don't text while riding. Keep your eyes and attention
  on the road and your surroundings — be ready for cars, pedestrians,
  potholes, doors opening, and other unexpected hazards.
</div>

---
transition: slide-left
---

<!-- SLIDE 7: RULES OF THE ROAD -->

<div class="flex items-start gap-6">
  <div class="icon-badge"><Icon name="traffic-cone" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Follow the Rules of the Road</h1>
    <p class="text-lg opacity-60">You're a vehicle — act like one</p>
  </div>
</div>

<div class="rule-card mt-8 text-xl">
  Stop at stop signs and red lights. Ride where you're supposed to ride.
  Follow traffic laws and pay attention to vehicles around you. Don't assume
  a driver sees you.
</div>

---
transition: slide-left
---

<!-- SLIDE 8: DON'T MODIFY -->

<div class="flex items-start gap-6">
  <div class="icon-badge stop"><Icon name="wrench" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Don't Modify Your Ride to Go Faster</h1>
    <p class="text-lg opacity-60">Built-in limits exist for a reason</p>
  </div>
</div>

<div class="rule-card stop-card mt-8 text-xl">
  Many e-bikes and e-scooters have built-in speed limits and safety features.
  Don't remove, bypass, or disable them. Making your ride faster can make it
  significantly more difficult to control and increases the risk of a serious
  crash.
</div>

---
transition: slide-left
---

<!-- SLIDE 9: DON'T RIDE DISTRACTED -->

<div class="flex items-start gap-6">
  <div class="icon-badge"><Icon name="headphones" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Don't Ride Distracted</h1>
    <p class="text-lg opacity-60">Your attention is your safety system</p>
  </div>
</div>

<div class="rule-card mt-8 text-xl">
  Music, phones, friends, and other distractions can take your attention
  away from what matters most — what is happening around you.
</div>

---
transition: slide-left
---

<!-- SLIDE 10: PEER PRESSURE -->

<div class="flex items-start gap-6">
  <div class="icon-badge stop"><Icon name="users" size="32px" /></div>
  <div>
    <h1 class="text-3xl font-bold">Don't Let Friends Talk You Into Risks</h1>
    <p class="text-lg opacity-60">Cool for seconds, costly for life</p>
  </div>
</div>

<div class="rule-card stop-card mt-8 text-xl">
  Racing, performing tricks, riding recklessly, carrying extra passengers, or
  riding at excessive speeds may look cool for a few seconds. A serious crash
  can change your life in an instant.
</div>

---
layout: center
transition: fade
---

<!-- SLIDE 11: THINK BEFORE YOU RIDE CHECKLIST -->

<h1 class="text-3xl font-bold text-center mb-8">Think Before You Ride</h1>

<div class="grid grid-cols-2 gap-x-10 gap-y-2 max-w-3xl mx-auto">
<v-clicks>

<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Is my helmet on?</div>
<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Are my brakes and tires working?</div>
<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Can I see and be seen?</div>
<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Am I riding at a safe speed?</div>
<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Am I following the rules?</div>
<div class="checklist-item"><Icon name="square-check" size="1.2rem" style="color: var(--go)" /> Am I paying attention?</div>

</v-clicks>
</div>

<div v-click class="text-center mt-10 text-xl" style="color: var(--caution-2)">
  If the answer to any of those questions is <b>no</b>, fix the problem before you ride.
</div>

---
layout: center
transition: fade
---

<!-- SLIDE 12: CLOSING -->

<div class="text-center">
  <Icon name="shield-alert" size="4rem" style="color: var(--stop);" class="mb-6 mx-auto" />
  <h1 class="text-3xl font-bold mb-4" style="color: var(--caution-2)">
    You don't get a reset button after a serious crash.
  </h1>
  <p class="text-2xl mt-8">
    Ride smart. Ride responsibly.<br/>
    And make sure you arrive safely.
  </p>
</div>

---
layout: full
---

<Youtube id="ZykdMe0aATM" width="100%" height="100%"/>

---
