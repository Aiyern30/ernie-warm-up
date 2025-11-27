
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

Primary: Deep emerald green (#0F6B4F) - representing Malaysian tropical heritage
Secondary: Warm golden yellow (#F4A340) - inspired by turmeric and traditional spices
Accent: Rich crimson red (#C41E3A) - reminiscent of sambal and chili
Background: Cream white (#FFF8F0) with subtle texture
Text: Dark charcoal (#2C2C2C) for readability
Navigation bar: Semi-transparent dark overlay with white text

Website Structure:

Hero Section

Full-width banner with "TASTE OF MALAYSIA" as main heading
Subheading: "Authentic Malaysian Cuisine"
Social media handles: @cwhui1001 @Aiyern30
Call-to-action button: "View Menu"


Navigation Bar (Sticky on scroll)

Logo: "Taste of Malaysia"
Menu links: Home | Appetizers | Noodles | Rice Dishes | Classics | Chinese-Malaysian | Indian-Malaysian | East Malaysian | Desserts | Drinks
Each link should smoothly scroll to the corresponding section


Menu Sections (in order):
Appetizers Section:

Roti Canai (RM4.50) - with first image
Chicken Satay (RM12.00 / 6 pcs) - with second image
Cucur Udang (RM8.00) - with third image

Noodles Section:

Char Kuey Teow (RM12.50) - with first noodles image
Mee Goreng Mamak (RM10.00) - with second noodles image
Asam Laksa (RM11.00) - with third noodles image

Rice Dishes Section:

Nasi Lemak Ayam Goreng (RM14.00) - with first rice image
Hainanese Chicken Rice (RM11.50) - with second rice image
Nasi Kukus (RM12.50) - with third rice image

Malaysian Classics Section:

Beef Rendang (RM16.50) - with first classics image
Asam Pedas Fish (RM18.00) - with second classics image
Ikan Bakar (RM18.50) - with third classics image

Chinese-Malaysian Dishes Section:

Sweet & Sour Chicken (RM12.50) - with first Chinese-Malaysian image
Claypot Chicken Rice (RM13.00) - with second Chinese-Malaysian image
Hainanese Steamed Fish (RM17.00) - with third Chinese-Malaysian image

Indian-Malaysian Dishes Section:

Tandoori Chicken Set (RM14.00) - with first Indian-Malaysian image
Mutton Varuval (RM18.50) - with second Indian-Malaysian image
Chapati with Chicken Curry (RM8.00) - with third Indian-Malaysian image

East Malaysian Dishes Section:

Hinava from Sabah (RM12.00) - with first East Malaysian image
Umai from Sarawak (RM12.00) - with second East Malaysian image
Linopot from Sabah (RM11.00) - with third East Malaysian image

Desserts Section:

Cendol (RM6.00) - with first dessert image
Pisang Goreng Cheese (RM7.00) - with second dessert image
Onde-Onde (RM5.00 / 8 pcs) - with third dessert image

Drinks Section:

Teh Tarik (RM4.50) - with first drink image
Sirap Bandung (RM3.50) - with second drink image
Kopi O (RM3.50) - with third drink image


Footer Section:

Contact information placeholder
Social media icons: @cwhui1001 @Aiyern30
Copyright notice



Design Requirements:

Use a card-based layout for menu items with hover effects (slight lift and shadow)
Each menu item card should display: image on top, dish name, price, and description
Add subtle fade-in animations as users scroll to each section
Include decorative Malaysian batik patterns as background accents
Make the website fully responsive (mobile, tablet, desktop)
Use elegant typography: heading font should be bold and modern, body text should be clean and readable
Add a "Back to Top" floating button
Include smooth scroll behavior for all navigation links

Technical Specifications:

Single HTML file with embedded CSS and JavaScript
Use the exact image URLs provided in the markdown
Ensure all images are properly sized and optimized for web viewing
Add loading states for images
Include meta tags for SEO and social media sharing

Please generate a complete, production-ready HTML file with all styling and functionality included.
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

👉 [_GitHub Pages URL_](https://aiyern30.github.io/ernie-warm-up/)

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

Open `index.html` in any browser.

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
