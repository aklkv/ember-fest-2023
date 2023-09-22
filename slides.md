---
theme: academic
title: Road to Embroider
class: text-left
highlighter: shiki
lineNumbers: false
info: |
  ## Road to Embroider
  Moving mountains and getting everyone onboard.
drawings:
  persist: false
transition: fade-out
mdc: true
layout: intro
---

<style>
  h1, h2, h3 {
    background-color: #2B90B6;
    background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }
</style>

# Road to Embroider

Moving mountains and getting everyone onboard.

<br/>
<br/>

## Alexey Kulakov

Software Engineer at HashiCorp

<v-clicks>

a.k.a.

- Why my CI broken
- 🤖 dependoAlexey

</v-clicks>

<uim-github /> aklkv <uim-twitter /> akulakov

---
layout: image-right
image: ./assets/Screenshot 2023-09-21 at 10.08.59 PM.png
---

### HashiCorp Cloud Platform

<br>

<v-clicks>

- `yarn` + `workspaces`
- <img src="assets/Screenshot 2023-09-22 at 1.41.57 AM.png">
- ***9*** local addons
- ***13*** in-repo engines
- ***8*** teams
- ***126*** ICs
- ***50*** PR/day
- ***22*** API services
- ***no ember-data***

</v-clicks>

<!--
  - Most addons use TS
-->

---
layout: image-right
image: ./assets/Screenshot 2023-09-21 at 10.08.59 PM.png
---

## Where we were a year ago

<br>

<v-clicks>

- `yarn` + `workspaces`
- ember 3.28
- no embroider
- slow builds/rebuilds ~2min/~1.5min

</v-clicks>

<!--
  - full app
  - individual engines (much faster but has it's own issues)
-->

---
layout: default
---

## How do we move forward?

<v-clicks>

- Big lift to move to ember 4.8
- move to GHA
- Helios
- Embroider
- `pnpm` + `turborepo`
- glint + template imports

</v-clicks>

<!--
  - reduce build times
  - improve DX
-->

---
layout: image-right
image: ./assets/Screenshot 2023-09-22 at 12.11.23 AM.png
---

## Helios

<br>

<v-clicks>

- provides primitive building blocks
- multi product
- accessability focused

</v-clicks>
  
---
layout: default
---

## Think big, start small

<br>

<v-clicks>

- start with RFC (Hermes)
- get buy-in from stakeholders
- be vocal
- be inclusive
- be patient
- be ready to compromise
- be ready to fail
- stay optimistic

</v-clicks>

---
layout: default
---

## You are ready to start

<br>

<v-clicks>

- is there blueprint or a codemod (make one)
- solve it for yourself first, then for others
- make smaller changes
- make it easy to adopt
- use atomic commits (Conventional Commits)
- notify stakeholders

</v-clicks>

---
layout: default
---

## Continues Process

<br>

<v-clicks>

- keep improving
- read ember RFCs
- watch main repos on github

</v-clicks>

---
layout: default
---

## Embroider

<br>

<v-clicks>

- run experimental branch with embroider (naive)
- convert local addons to v2
- identify issues
- fix
- repeat

</v-clicks>

---
layout: default
---

## Are we there yet?

<br>

<v-clicks>

No

but we are getting there

</v-clicks>

<br>

<v-clicks>

- initial build: 2.5min -> 1.5min
- rebuild: 1.5min -> ~5s

</v-clicks>

---
layout: default
---

## What's next?

<br>

<v-clicks>

- `pnpm` + `turborepo` 🤔 ?
- glint + template imports

</v-clicks>

---
layout: center
transition: slide-up
level: 2
class: text-center
---

## Thank you!

👋
