# Ismail Dwi - Minimalist Digital Portfolio

# Name       : Ismail Dwi Muh. Anugerah
# Student ID : 202410370110013
# Course     : Web Programming 5D Class of 2026

A clean, responsive, and minimalist digital portfolio built with a design language inspired by Notion's classic black-and-white environment. This portfolio is designed to showcase my journey and projects in **Python, Data Analysis, Data Visualisation**, and **Business Analytics**.

## 🚀 Features

- **Notion-Inspired Aesthetic:** Minimalist UI with a classic black-and-white theme, rounded corners, and a clean cover/profile layout.
- **Dark Mode Support:** Built-in theme toggle (Light/Dark) that automatically detects system preferences and saves user choices via `localStorage`.
- **Seamless Localization (i18n):** Instant translation toggle between Indonesian (IDN) and English (ENG) without reloading the page, with user preference persistence.
- **Infinite Scroll Galleries:** CSS-powered infinite marquee animations for both the "Certificates" and "Projects" sections, providing a dynamic way to showcase items.
- **Responsive Design:** Fully responsive layout that adapts gracefully from desktop to mobile screens, complete with a hamburger menu for mobile navigation.
- **Vanilla Tech Stack:** Built entirely without external heavy frameworks—just pure HTML, CSS, and JavaScript.

## 🛠️ Built With

- **HTML5:** Semantic structure.
- **CSS3:** Custom variables (CSS properties) for theme management, Flexbox for layout, and Keyframes for marquee animations.
- **JavaScript (Vanilla):** DOM manipulation for theme toggling, language switching, and mobile menu interaction.

## 📂 Project Structure

```text
📦 WebPorto
 ┣ 📂 assets
 ┃ ┣ 📜 cover.jpg             # Hero section cover background
 ┃ ┣ 📜 profile.jpg           # Profile picture
 ┃ ┗ 📜 (Project/Cert Images) # Various thumbnail assets
 ┣ 📜 index.html              # Main HTML structure and inline JS logic
 ┣ 📜 style.css               # Styling and theme variables
 ┗ 📜 README.md               # Project documentation
```

## ⚙️ Getting Started

To view or modify this project locally, no build tools or dependencies are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ismaildwi24/Portofolio-Web-Project.git
   ```
2. **Open the project:**
   Simply double-click on `index.html` to open it in your default web browser, or use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code for live reloading during development.

## 📝 Customization

- **Updating Content:** Open `index.html`. Project and certificate entries are hardcoded inside the `<article>` tags within the gallery sections.
- **Updating Translations:** Locate the `translations` object inside the `<script>` tag at the bottom of `index.html`. You can edit the string values for both the `id` and `en` keys to change the text across the site.
- **Changing Colors:** Open `style.css` and locate the `:root` and `[data-theme="dark"]` selectors at the top of the file. You can easily tweak the hex codes to change the color palette.

## 🧑‍💻 About the Author

**Ismail Dwi**
Data Enthusiast & Python Learner focusing on transforming raw data into meaningful business insights.

---
*Created with simplicity and clarity in mind.*
