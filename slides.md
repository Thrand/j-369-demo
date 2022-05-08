---
theme: seriph
# random image from a curated Unsplash collection by Anthony
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## 30/60/90
  Presentation to cover (how would i onboard myself?
  what key actions to engage the team + wider business
  What changes would you implement within the first 90 days

# persist drawings in exports and build
drawings:
  persist: true
download: true
layout: cover
---

# 30/60/90

Onboarding presentation and plan

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Next <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---

# Table of Contents

1. Introduction
2. Understanding so far
3. First 30 days
4. Middle 60 days
5. 90 Days & beyond
7. Q&A
---
layout: presenter
presenterImage: 'https://pbs.twimg.com/profile_images/1523099183556829185/nUzz-EW0_400x400.jpg'
---

# Jordan Shaw

- 💻 Technical Lead
- ✏ Passionate about Software, Security & Dev growth
- 🎨 Experienced in building awesome stuff

<div class="my-10 grid grid-cols-[80px,1fr]">
  <div><ri-github-line class="opacity-30"/><a href="https://github.com/thrand" target="_blank">thrand</a></div>
  <div><ri-twitter-line class="opacity-30"/><a href="https://twitter.com/shawthing17" target="_blank">shawthing17</a></div>
</div>

---
layout: two-cols
url: https://www.fruugo.co.uk
class: my-cool-content-on-the-right
---
# Current organisation

<div v-click="1"><li> ~25 engineers </li></div>
<div v-click="2"><li> 3 front end & designer </li> </div>
<div v-click="3"><li> 3 external teams </li></div>
<div v-click="4"><li> Agile </li></div>
<div v-click="5"><li> Product organisation ramped up </li></div>
<div v-click="6"><li> Mostly Mid-Snr developers </li> </div>

::right::

# Future plans 
<div v-click="7"><li> Grow team </li></div>
<div v-click="8"><li> Organisational changes</li></div>
<div v-click="9"><li> Increase job satisfaction  </li></div>
<div v-click="10"><li> Retention </li></div>

---
layout: image-right 
image: './images/first30.png'
---
# First 30 days 
Orientation starts here

Key outcomes

<div v-click="1"><li> Introductions to the team 🤝</li></div>
<div v-click="2"><li> Understand the products 🧠</li></div>
<div v-click="3"><li> Familiarise with Operations 💭</li></div>
<div v-click="4"><li> Read relevant materials 📰</li></div>
<div v-click="5"><li> Review Tech Strategy 💡</li></div>
<div v-click="6"><li> Understand what success looks like 🎉</li></div>
---
layout: image-left
image: ./images/middle60.png
---

# 60 Days
The Middle 8

Key outcomes

<div v-click="1"><li> Build relationships with team ❤ </li></div>
<div v-click="2"><li> Identify talent gaps 🔍</li></div>
<div v-click="3"><li> Consider alternatives 📈</li></div>
<div v-click="4"><li> Challenge Tech Strategy ❓</li></div>
<div v-click="5"><li> Review on-boarding experience 🤓</li></div>
---
layout: image-right
image: ./images/next90.png
---

# By Day 90
and looking forward

<div v-click="1"><li> Building future teams 🔨</li></div>
<div v-click="2"><li> Progression plan 📈</li></div>
<div v-click="3"><li> Demonstrate learnings 🧮</li></div>
<div v-click="4"><li> Gather Feedback 🗣️</li></div>
<div v-click="5"><li> Increased visibility 🏆</li></div>

---
layout: center
class: text-center
---

# Q & A

---
layout: center
class: text-center
---

# Thank you

<div class='mx-auto px-5 w-100 grid place-items-center grid-cols-2 gap-x-20'>
  <a href="https://forms.gle/7J5yTdoGWHvHyQAR6"><img src="/images/feedbackQR.png" /></a>
  <a href="https://sli.dev"><img src="https://sli.dev/logo-title.png" /></a>
</div>

