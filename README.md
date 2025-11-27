Here is a **fully rewritten, polished, well-structured Markdown README** including **your additional prompt about the English ⇆ Mandarin toggle button**.

I kept everything professional, organized, and suitable for GitHub.

---

# 🍽️ Taste of Malaysia — Web Builder Project

_A Web Builder Warm-up Task using PaddleOCR-VL & ERNIE AI_

## 📋 Project Overview

This project was developed as part of the **ERNIE Hackathon Warm-up Task: Web Builder Challenge**. The main objectives were:

- Extract text, layout, and images from a PDF using **PaddleOCR-VL**
- Convert extracted content into **Markdown**
- Transform the Markdown into a **fully responsive website** using **ERNIE AI**
- Deploy the final page using **GitHub Pages**

---

# 🍜 About the Website

**Taste of Malaysia** is a vibrant, single-page restaurant website showcasing the diverse flavors of Malaysian cuisine. The webpage presents an organized, visually rich menu with smooth navigation and modern UI features.

---

# 🎨 Design Features

### 🎨 Color Theme

| Purpose        | Color     | Description                                                |
| -------------- | --------- | ---------------------------------------------------------- |
| **Primary**    | `#0F6B4F` | Deep emerald green inspired by Malaysian tropical heritage |
| **Secondary**  | `#F4A340` | Warm golden yellow representing turmeric and spices        |
| **Accent**     | `#C41E3A` | Rich crimson red reminiscent of sambal                     |
| **Background** | `#FFF8F0` | Cream white with subtle texture                            |
| **Text**       | `#2C2C2C` | Dark charcoal for readability                              |

### ✨ Key UI/UX Features

- Fully responsive (mobile → desktop)
- Sticky navigation bar
- Smooth scrolling between sections
- Card-based menu layout with hover interactions
- Batik-pattern decorative accents
- High-quality food images
- Floating “Back to Top” button
- Scroll-fade animation for sections
- **NEW: Language Toggle (English ⇆ Mandarin Simplified)**

---

# 📂 Project Workflow

## **Step 1 — Content Creation**

Menu content was designed in **Canva** and categorized into:

- Appetizers
- Noodles
- Rice Dishes
- Malaysian Classics
- Chinese-Malaysian Dishes
- Indian-Malaysian Dishes
- East Malaysian Dishes
- Desserts
- Drinks

## **Step 2 — OCR Processing**

Using **PaddleOCR-VL**, we extracted:

- Text
- Layout information
- Images

The output was compiled into:
`Taste of Malaysia (ERNIE HACK).pdf_by_PaddleOCR-VL.md`

## **Step 3 — AI-Generated Web Development**

The Markdown and detailed prompt (see below) were fed into **ERNIE AI** to generate a polished, production-ready HTML website.

---

# 🧠 ERNIE AI Prompt (Base Prompt)

Below is the **original full prompt** used to generate the website:

```md
Create a modern, responsive single-page restaurant website for "Taste of Malaysia" with the following specifications:

Color Theme:

- Primary: #0F6B4F
- Secondary: #F4A340
- Accent: #C41E3A
- Background: #FFF8F0
- Text: #2C2C2C
- Navigation bar: Semi-transparent dark overlay with white text

Website Structure:

1. Hero Section:

   - Full-width banner
   - Heading: “TASTE OF MALAYSIA”
   - Subheading: “Authentic Malaysian Cuisine”
   - Social handles: @cwhui1001 @Aiyern30
   - CTA: “View Menu”

2. Sticky Navigation Bar with links:
   Home | Appetizers | Noodles | Rice Dishes | Classics | Chinese-Malaysian | Indian-Malaysian | East Malaysian | Desserts | Drinks

3. Menu Sections (with images):

   - Appetizers: Roti Canai, Satay, Cucur Udang
   - Noodles: Char Kuey Teow, Mee Goreng Mamak, Asam Laksa
   - Rice Dishes: Nasi Lemak Ayam, Hainanese Chicken Rice, Nasi Kukus
   - Malaysian Classics: Rendang, Asam Pedas, Ikan Bakar
   - Chinese-Malaysian: Sweet & Sour Chicken, Claypot Rice, Steamed Fish
   - Indian-Malaysian: Tandoori Set, Mutton Varuval, Chapati
   - East Malaysian: Hinava, Umai, Linopot
   - Desserts: Cendol, Pisang Goreng Cheese, Onde-Onde
   - Drinks: Teh Tarik, Sirap Bandung, Kopi O

4. Footer:
   - Contact placeholder
   - Social icons
   - Copyright notice

Design Requirements:

- Card layout with hover lift
- Image-first designed dish cards
- Batik pattern accents
- Fade-in animation on scroll
- Smooth scroll behavior
- Back-to-top floating button
- Single HTML file with CSS + JS embedded
- Use provided image URLs
- SEO meta tags
```

---

# ➕ Additional Prompt Added (New Feature)

During development, we discovered the need for an extra enhancement, so we added this additional prompt:

```md
Add a toggle button at the top right corner to switch the site’s text
between English and Mandarin Chinese (Simplified).

Requirements:

- Default language: English
- Use a simple JavaScript dictionary/object for translation
- All headings, navigation labels, food names, descriptions, and UI text must switch accordingly
- The toggle button should visually show EN | 中文
```

---

# 🍽️ Menu Summary

| Category           | Items |
| ------------------ | ----- |
| Appetizers         | 3     |
| Noodles            | 3     |
| Rice Dishes        | 3     |
| Malaysian Classics | 3     |
| Chinese-Malaysian  | 3     |
| Indian-Malaysian   | 3     |
| East Malaysian     | 3     |
| Desserts           | 3     |
| Drinks             | 3     |

Total dishes: **27**

---

# 🛠️ Technologies Used

- **PaddleOCR-VL** — OCR extraction
- **ERNIE AI** — Web code generation
- **HTML5/CSS3/JavaScript** — Frontend
- **GitHub Pages** — Deployment
- **Canva** — Menu design

---

# 👥 Contributors

- **@cwhui1001**
- **@Aiyern30**

---

# 🌐 Live Demo

👉 [_(GitHub Pages URL)_](https://aiyern30.github.io/ernie-warm-up/)

---

# 📁 Project Files

```
├── taste-of-malaysia.html                               # Main website
├── Taste of Malaysia (ERNIE HACK).pdf       # Original Canva design
├── Taste of Malaysia (ERNIE HACK).md        # OCR-extracted markdown
└── README.md                                 # This file
```

---

# 🚀 How to Run Locally

```bash
git clone https://github.com/yourusername/taste-of-malaysia.git
cd taste-of-malaysia
```

Open `taste-of-malaysia.html` in any browser.

---

# 📝 Lessons Learned

- PaddleOCR-VL works well for extracting structured text + images from PDFs
- ERNIE AI can generate surprisingly high-quality production web code
- Progressive refinement via prompt updates greatly improves results
- SPAs (Single Page Applications) are effective for restaurant menus
- Multi-language support can be added efficiently with JS dictionaries

---

# 📄 License

This project was developed for educational use as part of the ERNIE Hackathon Warm-up Task.

Made with ❤️ and 🌶️ celebrating Malaysian cuisine.

---
