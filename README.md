# Accessible Form UI

This project is based on the [Accessible Form UI](https://roadmap.sh/projects/accessible-form-ui) challenge from roadmap.sh.

## 📌 Project Overview
The goal of this project is to create an accessible **form UI** using only **HTML and CSS**.  
The form includes:
- Full name, email, password, and confirm password fields.
- Password visibility toggle buttons (eye icon).
- A **profile completeness circular progress bar**.
- A **checklist of requirements** that must be met for the form to reach 100% completeness.

This version is a **static UI component** (non-functional). It can later be enhanced with **JavaScript** for interactivity.

🔗 **Live Demo**: [Accessible Form UI on GitHub Pages](https://yanamak89.github.io/Accessible_Form_UI/)

## 🎯 Learning Goals
- Practice **semantic HTML** structure.
- Apply **CSS layouts** (Grid, Flexbox).
- Build **accessible forms** with ARIA attributes.
- Improve skills in **styling focus states, error states, and interactive elements**.

## ✅ Accessibility Guidelines Applied
- **Labels**: Each form field is linked to a `<label>` with `for` and `id`.
- **Focus states**: Clear focus outlines for keyboard navigation.
- **Error messaging**: Space reserved for inline error messages.
- **ARIA attributes**: `aria-required`, `aria-invalid`, and `aria-describedby` used where relevant.
- **Color contrast**: Meets WCAG contrast standards.
- **Interactive elements**: Password toggle button works with screen readers and keyboards.

## 🛠️ Tech Stack
- **HTML5**
- **CSS3** (Layouts, Positioning, Accessibility, Grid, Flexbox, Variables) 

No JavaScript is used in this static implementation.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/accessible-form-ui.git
   cd accessible-form-ui
   ```
2. Open `index.html` in your browser.

## 🔮 Future Improvements
- Add **JavaScript validation** for real-time error messages.
- Animate the **profile completeness progress ring**.
- Store progress in **local storage**.

---
Made with ❤️ for practice and learning accessible web development.
