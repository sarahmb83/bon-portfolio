# Sarah Bonville Portfolio — Project Brief

## Goal
Build a clean, static portfolio site in plain HTML/CSS. No frameworks, no build tools
beyond a local dev server. Deploy via Netlify (connected to GitHub). I'm replacing
my existing Webflow site.

## Stack
- Plain HTML + CSS (no frameworks, no Astro, no React)
- Google Fonts: Montserrat + Open Sans
- Simple local dev server via Node (e.g. `npx serve` or live-server)
- GitHub for version control
- Netlify for hosting (auto-deploys on push to main)

## File structure
/
├── index.html
├── work/
│ └── accessibility-khan-academy.html
├── images/
│ (all assets already in this folder)
├── css/
│ └── styles.css
└── CLAUDE.md

## Design
- Fonts: Montserrat (headings) + Open Sans (body) via Google Fonts
- Keep the same general visual style as the existing site — clean, minimal,
  professional
- Mobile responsive
- No contact form anywhere — replaced with a footer byline (see below)

## Pages

### 1. Home (index.html)

**Nav**
- Logo: images/portfolio-logo@2x.png — links to /
- Nav link: Home

**Hero section**
- Large text: "Sarah Bonville"
- H1: "Hey there, I'm a product designer / accessibility designer / design-thinker!"
- Subtext: "Please pardon my appearance while I continue to work on my portfolio
  site. If you're looking for specific samples of work that you don't find here,
  feel free to reach out on LinkedIn."

**Experience section**
- H2: "My experience"
- Intro: "My goal is to utilize the full product design life cycle to create a
  thoughtful, empathetic user experience, for all."
- Grid of 6 roles:

  1. Magic School | images/ms-logo.jpg
     Senior Product Designer
     July 2022 — Nov 2024

  2. Khan Academy | images/KAlogo.png
     Senior Product Designer, Platform Accessibility
     July 2022 — Nov 2024

  3. Sun Life | images/SLlogo.png
     Senior User Experience Designer
     Jun 2021 — Jul 2022

  4. Travelers Insurance Company | images/TRlogo.png
     User Experience Lead
     Mar 2020 — Jun 2021

  5. SwingU | images/SUlogo.png
     Senior User Interface Designer
     Nov 2018 — Mar 2020

  6. Finalsite | images/FSlogo.png
     Product Designer
     Dec 2013 — Nov 2018

**Work section**
- H2: "My work"

  Magic School (h3: "Magic School — coming soon!")
  - Quizzes — coming soon (placeholder, no link)
  - Student Room Revamp — coming soon (placeholder, no link)

  Khan Academy (h3: "Khan Academy")
  - Accessibility Design → /work/accessibility-khan-academy.html
  - Assessments → https://www.figma.com/deck/cHHaiDOw9lu7zLMWvVid6f/SB-•-KA-•-AX--Short-
    (opens in new tab)
  - Interactive Graph — coming soon (placeholder)
  - Course and Unit Revamp — coming soon (placeholder)

  - H3: "A11y @ Travelers — coming soon!"
  - H3: "Sun Life — coming soon!"

**Footer**
- NO contact form
- Simple professional byline with:
  - © Sarah Bonville
  - LinkedIn link (PLACEHOLDER — ask me for URL before publishing)
  - "WIP ♡" note

---

### 2. Khan Academy Case Study (work/accessibility-khan-academy.html)

**Nav** (same as home)

**Hero**
- H1: "Accessibility"
- Subhead: "at Khan Academy"

**Project overview grid**
- Label: "Project Overview"
- Text: "As a Senior Product Designer with a focus on Accessibility, I lead a11y
  at the design team level to increase working knowledge and practice for a11y,
  and coordinate cross-functionally to drive strategic a11y efforts across the
  platform."

- Label: "My Contributions"
- Intro: "There are multiple bodies of a11y work that span the design team level
  and the platform level. Some larger efforts include:"
- Bullet list:
  - A11y design reviews, with a11y annotations, A11y Guild reviews and design
    knowledge sharing and up-skilling.
  - Co-lead A11y Guild at Khan Academy.
  - Create a11y resources from the ground up that set ways of working for a11y
    across agile teams, like checklists and product development process.
  - Including a11y in my own product design projects at KA.
  - Work cross-functionally with an a11y pod to deliver strategic objectives for
    the org, including a path to VPAT and a11y vendor collaboration.

**Full-width image**
- images/a11y KA.png

**A11y annotations section**
- H2: "A11y design annotations"
- Feature project label: "Course and unit revamp"
- Description: "This project was to revamp our course and unit pages at Khan
  Academy. Part of design review and deliverables to our cross-functional team
  includes design review for a11y, documentation via comments or Figma a11y
  annotations, and collaboration with PMs and Engineers to align on a11y needs
  ahead of time. Here's a few examples:"

- H3: "A11y annotations for skip link, landmarks and headings"
- Image: "images/a11y annotations skip link, landmarks, headings.png"
  Alt: "A user interface showing accessibility annotations for skip link,
  landmarks and headings"

- H3: "A11y annotations for links, buttons, images, tooltips"
- Image: "images/a11y annotations - links, buttons, images, tooltips.png"
  Alt: "A user interface showing accessibility annotations for links, buttons,
  images and tooltips"

- H3: "A11y annotations for focus order (or TAB stops)"
- Image: "images/a11y annotations - focus order.png"
  Alt: "A user interface showing accessibility annotations for focus order or
  tab stops"

**Footer** (same as home)

---

## Key decisions
- No contact form anywhere — spam issue. Footer has LinkedIn link instead.
- Mostly static — no CMS, no JS frameworks needed
- Placeholder SVGs exist for "coming soon" work items (images/placeholder 1.svg etc)
- More case study pages will be added later — build the structure to support that
- Keep image filenames as-is from the /images folder

## When I say "ask me"
- LinkedIn URL: ASK ME before adding any social links
- Any other social/professional links: ASK ME
- Headshot or personal photo: TBD