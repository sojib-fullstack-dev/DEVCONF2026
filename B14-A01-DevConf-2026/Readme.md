## 🌟 WELCOME TO ( সহজ সরল সিম্পল ) ASSIGNMENT-001 😎

---

📅 Deadline For 60 marks: **Jul 11 2026 (11:59 pm ⏱️)**

📅 Deadline For 50 marks: **Jul 12 2026 (11:59 pm ⏱️)**

📅 Deadline For 30 marks: **Any time after the 50 marks deadline**

---

## 📌 Assignment Requirements

### ✅ Main Requirements (50 Marks)

### 🔹 Navbar Section

- Logo aligned to the left ("DEVCONF 2026")
- Menu items centered (Speakers, Schedule, Tracks, Venue, Blog)
- A "Register Now" button aligned to the right

---

### 🔹 Banner (Hero) Section

- A full-width dark background image with overlay
- Centered bold multi-line heading ("Code. *Connect*. Create") — style one word (e.g. "Connect") in italics for emphasis
- Centered supporting paragraph text below the heading
- One "Register Now" button, centered, below the text

---

### 🔹 Meet the Speakers Section

- Centered section heading ("Meet the Speakers")
- A 2x2 grid of speaker cards (minimum 4 speakers)
- Each card must include:

  - A speaker photo
  - A small category/track label (e.g. AI/ML, Cloud & DevOps, Frontend, Security)
  - Speaker name
  - Speaker title/company

---

### 🔹 Secure Your Spot (Pricing) Section

- Centered section heading ("Secure Your Spot") with a subtitle
- Three pricing cards in a row (Standard, Pro, Team)
- The middle/featured plan (Pro) should be visually highlighted (different background color)
- Each card must include:

  - Plan name/label
  - Price
  - A bullet list of included features
  - A button at the bottom

---

### 🔹 Footer Section

- Logo on the left
- Social media links with icons on the right
- A horizontal divider
- Copyright message below the divider

---

## 🎨 PLACEHOLDER SECTION — AI CHALLENGE (10 Marks)

This is the **only** section where AI usage is expected and encouraged.

- Replace the "Something Missing? Generate a relevant section with AI" placeholder with a brand-new section of your own idea.

- The section **must stay relevant to the DevConf 2026 theme** (e.g. Sponsors,  Venue, FAQ, Newsletter Signup, Hackathon Details, Past Highlights, Job Board, etc.).
- Use AI (Claude, ChatGPT, or any tool) to help you **ideate, design, and/or code** this section.

- Marks will be given based on:

  - How **unique** and creative the section idea is
  - How well it **fits** visually and thematically with the rest of the page
  - How effectively you used AI (clarity and quality of your prompting)

- You must **submit the prompt(s)** you used to generate this section along with your submission (see Submission Format below).

---

## 🔸 Other Requirements (Must Follow)
- Minimum **5 GitHub commits**
- **No Lorem Ipsum** text anywhere on the website
- No duplicated/copy-pasted text across repeating sections (e.g. each speaker bio/description must be unique)

---

## 🎥 ADDITIONAL REQUIREMENT — Concept Explanation Video (Optional, 0 Marks)

> ⚠️ **This is fully optional and carries no marks in this assignment. However, it is highly recommended.** Starting from the next assignment, submitting a short explanation video like this will become **mandatory**, so use this one to get comfortable with the format early.

- Record a **max 5-minute video** explaining the following basic HTML & CSS questions in your own words:

  1. What is the difference between a `<div>` and a `<span>`? When would you use each?
  2. What is the CSS Box Model? Explain `content`, `padding`, `border`, and `margin`.
  3. What is the difference between a CSS `class` and an `id`? When should you use one over the other?
  4. What is Flexbox, and what's the difference between `justify-content` and `align-items`?
  5. What is the difference between `position: relative`, `absolute`, and `fixed` in CSS?

- Speak naturally, in your own words — no need to read from a script.
- Screen recording with your face on camera (or voice-over on slides/code) is fine, whichever you're comfortable with.
- Upload the video link (YouTube/Google Drive) along with your submission.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- No JavaScript
- No CSS frameworks or libraries

---

## 📂 Submission Format

- **GitHub Repository Link**
- **Live Website Link (GitHub Pages)**
- **AI Prompt(s)** used for the Placeholder Section (paste as text, or include in a `PROMPTS.md` file in your repo)
- **(Optional) Concept Explanation Video Link**

---

## ❓ Common Questions & Answers

**Can I use different images?**

- Yes, you may use any relevant images (speaker photos, hero background, etc.).

**Can I change the alignment and design freely?**

- No. You must follow the alignment and layout shown in the Figma design.

**Can I change colors?**

- Yes, as long as the colors are relevant and visually consistent with a tech-conference theme.

**Do I need to make the page pixel-perfect?**

- No. You can use your own margin and padding while following the overall structure from Figma.

**Can I use AI to build my sections?**

- Only for the **Placeholder Section** (see below). For every other section, you are expected to write the HTML & CSS yourself. Using AI to generate the Navbar, Banner, Speakers, Pricing, or Footer sections is **not recommended** and may cost marks during evaluation.

**Is the explanation video mandatory?**
- No, not for this assignment. It's optional and won't be graded, but it's a good habit to build early since it will be mandatory starting next assignment.

---
---

## ❓ Common Issues You May Face and Quick Solutions

**GitHub Pages showing 404 / site not loading?**
- Your main HTML file **must be named `index.html`** (lowercase). GitHub Pages looks for this file by default. Rename it if it's called anything else (e.g. `home.html`, `Index.html`).

**Images or CSS not loading on GitHub Pages?**
- Add `./` before your file paths: `./style.css`, `./images/photo.jpg` instead of `style.css` or `/images/photo.jpg`.
- File names are **case-sensitive** on GitHub Pages (Linux). `Photo.jpg` ≠ `photo.jpg` — make sure casing matches exactly.

**CSS background image not showing?**
- Paths in CSS `background-image: url(...)` are relative to the **CSS file location**, not the HTML file. Use `./images/bg.jpg` or `../images/bg.jpg` depending on your folder structure.

**Site not updating after pushing to GitHub?**
- Wait 1–2 minutes, then hard refresh: `Ctrl + Shift + R` (Windows) / `Cmd + Shift + R` (Mac) to bypass browser cache.

**CSS changes not reflecting locally?**
- Hard refresh: `Ctrl + Shift + R`. Your browser is likely showing a cached version.

**Commit count is less than 5?**
- Commit after completing each section (Navbar → Banner → Speakers → Pricing → Footer). Don't push everything in one final commit.

**Fonts or icons not loading?**
- If using Google Fonts or icon libraries via `<link>`, they require an internet connection. They will work fine on GitHub Pages.

**Page looks fine locally but broken on GitHub Pages?**
- Check all file/folder names for typos and casing mismatches. Windows ignores case, but GitHub Pages (Linux) does not.
