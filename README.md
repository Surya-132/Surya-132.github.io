# 🧾 Portfolio Website – Krishna Surya

https://surya-132.github.io/

This is a personal portfolio website created using **HTML** and **CSS**, designed to showcase my background, skills, and projects. Below is a breakdown of the structure of the website.

---

## Website Structure

### `<!DOCTYPE html>` + `<html>`
- The website begins with a standard HTML5 declaration.
- A custom background border is applied using `border-image` directly in the `<html>` tag.

---

### `<head>`
- Contains:
  - Page title
  - Google Fonts (`Tangerine`) for stylized headers
  - Link to external CSS file
  - Viewport settings for responsiveness

---

### `<body>`
Main content of the portfolio. Organized into several sections:

#### 1. **Profile Photo**
- An image floated to the right (`asset0.jpg`), styled with a black border.

#### 2. **Header + Navigation**
- Contains:
  - A heading (`My Portfolio`) with custom font
  - A simple nav bar with anchor links to:
    - GitHub
    - Projects
    - Contact section

#### 3. **About Me (`#about`)**
- Brief self-introduction
- Highlights your interests in **Web Dev**, **AI**, and **Competitive Programming**

#### 4. **Education (`#education`)**
- A table with three rows for:
  - School
  - Intermediate
  - Current college (Amrita)

#### 5. **Skills (`#skills`)**
- Unordered list of languages/tools you’re familiar with:
  - Dart
  - HTML/CSS
  - Python
  - Java

#### 6. **Projects (`#portfolio`)**
- Section includes:
  - Titles and descriptions of 4 projects
  - Corresponding screenshots (`asset1.png`, `asset2.png`, `asset3.png`)
  - GitHub repo links

#### 7. **Contact (`#contact`)**
- Phone number
- Email (clickable link)
- Social icons for:
  - Twitter
  - Facebook
  - LinkedIn  
  Each icon is inside a rounded black-bordered container.

---

## Styling
- Some inline styles are used (e.g., fonts, borders, layout)
- Most of the layout is controlled by external CSS (`CSS Portfolio - Final.css`)
- Uses serif Google font **Tangerine** for titles and emphasis

---

## Notes
- Designed with simplicity in mind – ideal for a beginner project
- Could be improved further using responsive design, semantic HTML tags, and separating styles from markup
