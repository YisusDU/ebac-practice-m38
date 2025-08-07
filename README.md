# Academia Editorial de Amazon - Marketing Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)

## Preview
<img src="https://github.com/YisusDU/ebac-practice-m38/blob/main/assets/img/preview-AMZ.webp" alt="general preview">

---

## 📂 Relevant Source Files

- `assets/img/preview-AMZ.webp`
- `index.html`

---

## 🎯 Purpose and Scope

This repository contains the complete implementation of a marketing landing page for **"Academia editorial de Amazon"** (Amazon Editorial Academy), a course that teaches users how to write and sell ebooks using **Amazon KDP (Kindle Direct Publishing)** and AI tools.  

The system is designed as a **static promotional website** that guides potential customers through a structured marketing funnel with the goal of **course enrollment**.

The repository implements a **single-page application** focused entirely on **conversion optimization**, featuring multiple content sections, multimedia assets, and call-to-action elements.

For detailed information about:

- Landing page content structure and user journey, see **Landing Page Architecture**.  
- Styling system details, see **Styling System**.  
- Asset management strategies, see **Visual Asset Management**.

---

## 🏗️ System Architecture Overview

The repository follows a traditional **static website architecture** with a clear separation between:

- Content structure  
- Visual presentation  
- Asset management

The system centers around a **single HTML file** that orchestrates the loading of compiled stylesheets and various marketing assets.

The SCSS system provides a modular approach to styling with clear separation between variables, mixins, layout rules, and component definitions.

> **Sources:**  
> `index.html` (lines 1–272)

---

## 🧩 Core Technical Components

### Entry Point and Content Structure

- The primary application entry point is `index.html`, which implements a comprehensive marketing landing page with **semantic HTML5** structure.
- Includes extensive **SEO metadata**, **Open Graph** tags for social media sharing, and **accessibility** considerations.
- Uses **BEM-style CSS classes** for maintainable styling.
- Focus on keywords related to Amazon KDP and ebooks.

> **Sources:**  
> `index.html` (lines 1–42, 89–100, 245–256)

---

### Asset Integration and Loading Strategy

| Asset Category  | File Examples                      | Purpose                  | Loading Strategy          |
|-----------------|----------------------------------|--------------------------|---------------------------|
| Hero Graphics   | `amz-poster-img.png`              | Primary visual appeal    | Direct HTML embedding     |
| Video Content   | `amz-edit-garanty.mp4`, `amz-poster-animated.mp4` | Trust signals, engagement | Autoplay, loop, muted     |
| Social Proof    | `amz-users-aprove.png`, `amz-collab.png` | Credibility building     | Lazy loading compatible   |
| Process Visuals | `amz-working.png`, `amz-interview.webp` | Feature explanation      | Standard loading          |

- Prioritizes critical marketing assets via direct HTML integration.
- Uses semantic alt text for accessibility.
- Video elements utilize HTML5 autoplay for engagement without user interaction.

> **Sources:**  
> `index.html` (lines 46–50, 105–113, 189–192, 207–210)

---

## 📊 Technical Standards and SEO Implementation

| Implementation Area | Technical Details                        | File Reference  |
|---------------------|----------------------------------------|-----------------|
| Meta Description    | Amazon KDP course description for search results | `index.html` (8–11)   |
| Keywords            | Targeted terms: Curso, venta, ebooks, amazon, kindle, KDP | `index.html` (16–17)  |
| Open Graph          | Title, description, and image for social sharing | `index.html` (19–28)  |
| Robots Directive    | Index, follow for search engine crawling | `index.html` (13–14)  |

---

## 🌐 External Dependencies and Performance

- Typography loaded from **Google Fonts** with **preconnect optimization** for:
  - Poppins  
  - Open Sans  
  - Rubik  
  - Spicy Rice  
- DNS prefetching used for fonts.googleapis.com and fonts.gstatic.com  
- Single compiled stylesheet loaded with source maps for development  

> **Sources:**  
> `index.html` (7–37, 30–36)

---

## 📌 Summary

This repository represents a focused implementation of a **marketing landing page** with:

- Clear technical architecture  
- Comprehensive asset management  
- Optimization for SEO and user conversion  

The modular approach to styling and content organization enables maintainable development while
supporting the primary business objective of **course enrollment conversion**.

>[!Note]
>You can check the full documentation <a href="https://deepwiki.com/YisusDU/ebac-practice-m38">-here-</a>
