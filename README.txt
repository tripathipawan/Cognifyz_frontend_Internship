# 🏢 Cognifyz Technologies — Frontend Development Internship

A structured repository of all **6 frontend development tasks** completed during a one-month remote internship at **Cognifyz Technologies** — progressing from fundamental HTML/CSS structure through intermediate layout techniques to advanced JavaScript DOM manipulation, public API integration, and interactive form handling.

---

## 📌 Internship Details

| Field | Details |
|---|---|
| **Intern Name** | Pawan Tripathi |
| **Organization** | Cognifyz Technologies |
| **Internship Title** | Frontend Development Internship |
| **Duration** | 22nd October 2025 – 22nd November 2025 |
| **Mode** | Remote |
| **Contact** | tripathipawan8705@gmail.com |

---

## 📌 Overview

This repository documents the complete progression of frontend development skills developed during the internship. Tasks are organized into three difficulty levels — **Basic**, **Intermediate**, and **Advanced** — each building on the foundation established in the previous level.

The internship covered core web fundamentals (HTML5, CSS3, JavaScript ES6+), responsive layout design, DOM manipulation, asynchronous API consumption with `fetch()`, and user-facing form validation with JavaScript event handling.

---

## 📁 Repository Structure

```
Cognifyz_frontend_Internship/
├── Level_1/                         # Basic HTML & CSS — Tasks 1 and 2
│   ├── Task_1_Introduction_Page/    # Introductory webpage with HTML structure
│   │   ├── index.html               # Page with name, motivational quote, and image
│   │   └── style.css                # Base styles for the introduction page
│   └── Task_2_Inline_Styling/       # Inline CSS styling and layout design
│       ├── index.html               # Quote of the Day section with image and caption
│       └── style.css                # Color, spacing, and font styling
│
├── Level_2/                         # Intermediate Projects — Tasks 3 and 4
│   ├── Task_3_External_CSS_Layout/  # External CSS file with structured layout
│   │   ├── index.html               # Multi-section page using class/ID-based selectors
│   │   └── style.css                # Padding, margin, hover effects, color scheme
│   └── Task_4_BG_Color_Changer/     # Interactive background color changer
│       ├── index.html               # Button-driven color change UI
│       ├── style.css                # Button and page layout styles
│       └── script.js                # DOM event listeners and CSS property updates via JS
│
├── Level_3/                         # Advanced Projects — Tasks 5 and 6
│   ├── Task_5_API_Integration/      # Public API data fetch and dynamic card rendering
│   │   ├── index.html               # Card container layout for user data display
│   │   ├── style.css                # Card component styles and responsive grid
│   │   └── script.js                # fetch() call, JSON parsing, dynamic DOM card creation
│   └── Task_6_Form_Submission/      # Interactive form with validation and submission feedback
│       ├── index.html               # Feedback form — name, email, message fields
│       ├── style.css                # Form layout, input styles, popup animation
│       └── script.js                # Form validation, submission handler, popup animation
│
└── README.txt                       # Original internship summary and task description
```

---

## 📋 Tasks Breakdown

### 🟢 Level 1 — Basic HTML & CSS

**Task 1: Introduction Web Page**

Built a structured introductory webpage from scratch using semantic HTML5. The page includes a personal introduction, a motivational quote, and a programming-related image. The primary focus was understanding HTML document structure, heading hierarchy, paragraph elements, and image embedding with proper `alt` attributes.

**Task 2: Inline Styling and Layout**

Applied inline CSS styling to explore how style attributes directly affect element appearance. Designed a "Quote of the Day" section with a styled image and descriptive caption. Practiced controlling color, font size, spacing, and text alignment directly within HTML tags before moving to external stylesheets.

---

### 🟡 Level 2 — Intermediate Projects

**Task 3: External CSS and Structured Layout**

Rebuilt the layout from Task 2 using a fully separate external CSS file — establishing the content/design separation principle. The page uses multiple sections with class and ID-based selectors, applies padding and margin for spatial layout, and implements hover state styling. The primary learning objective was understanding CSS specificity, the cascade, and clean selector organization.

**Task 4: Background Color Changer**

Built an interactive browser page where clicking buttons dynamically changes the page's background color using JavaScript. Each button targets a different color and updates `document.body.style.backgroundColor` on click. This task introduced JavaScript DOM manipulation, `addEventListener()`, event object handling, and modifying CSS properties programmatically.

---

### 🔴 Level 3 — Advanced Projects

**Task 5: Public API Integration**

Integrated a public REST API using JavaScript's native `fetch()` function to retrieve user data in JSON format. The data — including each user's name, phone number, gender, and country — is parsed from the API response and dynamically rendered as styled cards in the DOM. This task introduced asynchronous JavaScript concepts (`async/await`, Promises), JSON parsing, and the pattern of separating data fetching from DOM rendering.

**Task 6: Interactive Form with Validation and Submission Feedback**

Built a complete feedback form (name, email, message fields) with client-side validation and a post-submission confirmation experience. JavaScript validates that all fields are filled and the email follows a valid format before allowing submission. On successful submission, a popup message ("Form submitted successfully") appears with a CSS animation. This task covered `preventDefault()`, real-time input validation, conditional rendering via DOM manipulation, and CSS keyframe animation triggered by JavaScript.

---

## 🧠 Key Concepts Covered

| Concept | Applied In |
|---|---|
| HTML5 semantic structure | Tasks 1, 2, 3 |
| Inline vs. external CSS | Tasks 2, 3 |
| CSS selectors, specificity, cascade | Task 3 |
| CSS hover states and transitions | Task 3 |
| JavaScript DOM manipulation | Task 4, 5, 6 |
| `addEventListener()` and event handling | Tasks 4, 6 |
| `fetch()` and async/await | Task 5 |
| JSON parsing and dynamic rendering | Task 5 |
| Form validation and `preventDefault()` | Task 6 |
| CSS keyframe animations via JavaScript | Task 6 |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup across all tasks |
| CSS3 | Styling, layout, hover effects, keyframe animations |
| JavaScript (ES6+) | DOM manipulation, event handling, API fetching, form validation |

> All tasks are built with zero dependencies — no npm, no frameworks, no build tools. Each task folder opens directly in any browser.

---

## 🚀 Getting Started

No installation required. Each task is a standalone set of static files.

**1. Clone the repository**
```bash
git clone https://github.com/tripathipawan/Cognifyz_frontend_Internship.git
cd Cognifyz_frontend_Internship
```

**2. Open any task**

Navigate into any task folder and open its `index.html` file directly in a browser:

```bash
# Example — open Task 4
cd Level_2/Task_4_BG_Color_Changer
open index.html
```

Or use the VS Code **Live Server** extension for a better development experience:
```
Right-click on index.html → Open with Live Server
```

> **Note for Task 5:** An active internet connection is required for the API fetch call to retrieve user data.

---

## 🌱 What I Learned

This internship provided structured hands-on exposure to the full foundation of frontend development:

- Deep practical understanding of HTML5 document structure and semantic elements
- Writing clean, organized CSS with proper separation of concerns using external stylesheets
- DOM manipulation fundamentals — selecting elements, modifying content, and responding to events
- Asynchronous JavaScript patterns with `fetch()`, `async/await`, and JSON data handling
- Building a complete form validation flow from input checking through to submission feedback
- Triggering and controlling CSS animations programmatically from JavaScript

---

## 👨‍💻 Author

**Pawan Tripathi**
- GitHub: [@tripathipawan](https://github.com/tripathipawan)
- LinkedIn: [Pawan Tripathi](https://www.linkedin.com/in/pawan-tripathi-9a8158367)
- Email: tripathipawan8705@gmail.com

---

> *Thank you to Cognifyz Technologies for providing this structured learning opportunity and the task framework that guided this progression through core frontend fundamentals.*

---

## 📄 License

This repository is open source and available under the [MIT License](LICENSE).
