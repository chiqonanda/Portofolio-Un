# Portofolio-

# 🌌 Dark Portfolio Website

Website portfolio statis yang dibuat menggunakan **HTML5, CSS3, Bootstrap 5, dan Vue JS (CDN)**.  
Project ini dikembangkan sebagai tugas pembuatan website portfolio dengan tampilan modern dark theme.

---

## 👨‍💻 About the Project

This project is a personal portfolio website designed to showcase profile information, technical skills, professional experience, and certifications.

The website is fully responsive and structured using Bootstrap grid system.  
Vue JS is integrated via CDN to add simple interactivity such as dynamic data rendering and looping.

---

## 🚀 Features

- Responsive Navbar (Bootstrap 5)
- Full-screen Hero Section
- About Me Section
- Skills with dynamic Progress Bars
- Professional Experience Section
- Certificates Section with image cards
- Dark Modern UI Design
- Responsive Layout
- Smooth Scrolling

---

# 📌 Section Explanation

---

## 🏠 1. Home (Hero Section)

### Description
The hero section introduces the profile with:
- Profile image
- Name
- Short introduction
- Action buttons

### Implementation
- Bootstrap Grid (`container`, `row`, `col-md`)
- Vue interpolation `{{ name }}`
- Full-screen layout using `min-height: 100vh`

---

## 👤 2. About Me Section

### Description
Contains personal introduction and academic background as an Information Systems student at Universitas Mulawarman.

### Implementation
- Bootstrap grid layout
- Typography customization via CSS
- Vue dynamic content rendering

---

## 💻 3. Technical Skills

### Description
Displays skill levels using Bootstrap progress bars.

### Implementation
- Bootstrap `progress` component
- Vue `v-for` for looping skills
- Dynamic width binding using `:style="{ width: skill.level + '%' }"`

---

## 🏢 4. Professional Experience

### Description
Shows professional or academic experience in structured layout.

### Implementation
- Bootstrap spacing utilities
- Custom dark background styling

---

## 🏆 5. Certificates Section

### Description
Displays certifications in responsive card grid layout including uploaded certificate images.

### Implementation
- Bootstrap `card`
- Bootstrap grid (`row`, `col-md-4`)
- Responsive image handling
- Hover animation effects
- Optional Vue `v-for` for looping certificates

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Website structure |
| CSS3 | Styling and dark theme design |
| Bootstrap 5 | Layout system, navbar, grid, card, progress bar |
| Vue JS (CDN) | Data binding, interpolation, looping |
| Google Fonts | Typography enhancement |

---

# 📸 Website Preview

## Home Section
![Home Preview](assets/home.png)

## About Section
![About Preview](assets/about.png)

## Certificates Section
![Certificates Preview](assets/certificates.png)

---

# 📂 Project Structure



---

# 📱 Responsive Design

The website is fully responsive and adapts to:

- Desktop
- Tablet
- Mobile devices

Bootstrap breakpoints are used to maintain layout consistency across screen sizes.

---

# 🧠 Learning Outcome

Through this project, I learned:

- Building responsive layouts using Bootstrap Grid System
- Creating full-screen sections using CSS
- Applying modern dark UI color grading
- Implementing Vue JS (CDN) for dynamic rendering
- Structuring clean and maintainable front-end code

---

# 👤 Author

**Your Name**  
Information Systems Student  
Universitas Mulawarman  
Year: 2026

---

# 📌 Notes

- This project is built without using any ready-made templates.
- All layouts are structured manually using Bootstrap components.
- Vue is implemented via CDN without build tools or Vue CLI.
