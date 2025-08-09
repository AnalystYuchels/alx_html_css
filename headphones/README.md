# Headphones Landing Page

A fully responsive landing page built using **HTML** and **CSS** (with minimal JavaScript for the hamburger menu). The project follows best practices for structuring HTML, styling with reusable CSS components, and ensuring cross-device responsiveness.

## 📌 Project Overview

This project is part of the **ALX Front-End Specialization**, focusing on building a modern, responsive landing page for a fictional headphone brand. It includes a hero section, services description, results display, contact form, and footer.

The page adapts seamlessly for **desktop**, **tablet**, and **mobile** views, with interactive elements like hover effects, animations, and a hamburger menu.


## 🎯 Learning Objectives

By completing this project, you will:

* Apply **responsive design principles** for different screen sizes.
* Use **CSS variables** for maintainable styling.
* Implement **flexbox** and **grid layouts**.
* Add **custom icons** using font files.
* Create **shapes with pure HTML & CSS** (pentagons for the results section).
* Add **animations and hover states** to interactive elements.
* Implement a **hamburger menu** using vanilla JavaScript.


## 📂 Project Structure

```
alx_html_css/
└── headphones/
    ├── images/                 # Image assets (logo, background images)
    ├── icons/                  # Custom font icons (holberton_school-icon)
    ├── 0-index.html             # Hero section only
    ├── 0-styles.css
    ├── 1-index.html             # + "What we do" section
    ├── 1-styles.css
    ├── 2-index.html             # + "Our results" section
    ├── 2-styles.css
    ├── 3-index.html             # + Contact form
    ├── 3-styles.css
    ├── 4-index.html             # + Footer
    ├── 4-styles.css
    ├── 6-index.html             # Pentagon shapes using CSS only
    ├── 6-styles.css
    ├── 7-index.html             # Added animations
    ├── 7-styles.css
    ├── 8-index.html             # Hamburger menu with JavaScript
    ├── 8-styles.css
    ├── script.js                # JavaScript for hamburger menu
    └── README.md                # Project documentation
```


## 🖥️ Features

* **Hero Section** with background image, headline, subheading, and CTA button.
* **What We Do** section with custom icons.
* **Our Results** section featuring CSS-drawn pentagons.
* **Contact Form** for user messages.
* **Footer** with logo and social media links.
* **Fully responsive** (desktop, tablet, and mobile views).
* **Animations** on hover for service icons and results shapes.
* **Hamburger Menu** for navigation on small screens.


## 🎨 Style & Interaction Details

* **Content max-width:** `1000px` (centered).
* **Link hover/active color:** `#FF6565`.
* **Button hover/active:** `opacity: 0.9`.
* **Fonts:** `Source Sans Pro` and `Spin Cycle OT`.
* **Responsive Breakpoint:** Mobile layout at `480px` and below.
* **Custom Shapes:** Pentagons made purely with HTML & CSS.


## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/alx_html_css.git
cd alx_html_css/headphones
```

### 2️⃣ Open in browser

Simply open any `index.html` file in your browser to view the page.


## 📱 Responsive Design

* **Desktop** – Full navigation menu visible.
* **Tablet** – Adjusted spacing and scaling of sections.
* **Mobile (≤ 480px)** – Hamburger menu replaces full navigation.


## ⚡ JavaScript Features (Task 8)

* **Hamburger Menu Toggle**
  When clicked, the hamburger icon shows or hides the navigation links with smooth animations.