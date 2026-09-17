# 🤝 Contributing to Live Digital Clock

First off, thank you for considering contributing to the **Live Digital Clock** project! It's contributions like yours that make the open-source community an amazing place to learn, inspire, and create.

Whether you are fixing a bug, improving the UI/UX, optimizing JavaScript logic, or adding new features, all forms of contribution are greatly appreciated.

---

## 📜 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Pull Requests](#pull-requests)
- [Project Structure](#-project-structure)
- [Development Guidelines](#-development-guidelines)
  - [HTML Guidelines](#html-guidelines)
  - [CSS Guidelines](#css-guidelines)
  - [JavaScript Guidelines](#javascript-guidelines)
- [Git Commit Guidelines](#-git-commit-guidelines)

---

## 📜 Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

---

## 🚀 How Can I Contribute?

### Reporting Bugs

Before creating a bug report, please check the [Issues tab](https://github.com/adarsh0707-kumar/Clock/issues) to see if the bug has already been reported.

When reporting a bug, please include:
* **A clear and descriptive title.**
* **Steps to reproduce the issue.**
* **Expected vs. actual behavior.**
* **Browser and device details** (e.g., Chrome v120 on Windows 11, Safari on iOS).
* **Screenshots or screen recordings** if applicable.

Please use our [Bug Report Template](.github/ISSUE_TEMPLATE) when opening a new issue.

### Suggesting Enhancements

If you have ideas to improve the design, accessibility, responsiveness, or features (e.g., dark mode toggle, alarm, stopwatch, 12/24 hour format toggle):

1. Check if the enhancement has already been proposed.
2. Open an issue using the [Feature Request Template](.github/ISSUE_TEMPLATE).
3. Clearly explain **what** the feature is and **why** it would be beneficial.

### Pull Requests

Follow these steps to submit your changes:

1. **Fork the Repository**: Click the "Fork" button at the top right of the repository page.
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Clock.git
   cd Clock
   ```
3. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   # OR for bug fixes
   git checkout -b fix/issue-description
   ```
4. **Make Your Changes**: Keep changes concise and focused on the intended issue/feature.
5. **Test Your Changes**: Open `index.html` in multiple browsers and test responsiveness across different screen widths.
6. **Commit Your Changes**: Follow clear commit message standards (see below).
7. **Push to GitHub**:
   ```bash
   git push origin feature/your-feature-name
   ```
8. **Submit a Pull Request**: Go to the original repository on GitHub and open a Pull Request targeting the `main` branch. Describe your changes and link any related issues.

---

## 📁 Project Structure

```text
Clock/
├── .github/
│   └── ISSUE_TEMPLATE/    # Issue templates for bugs and features
├── index.html             # Main HTML structure
├── style.css              # Styling, layouts, fonts, and responsive design
├── script.js              # Clock logic, timer functions, DOM manipulation
├── CODE_OF_CONDUCT.md     # Community guidelines
├── CONTRIBUTING.md        # Contribution guidelines (this file)
├── LICENSE                # MIT License
├── README.md              # Project overview and instructions
└── SECURITY.md            # Security policy and reporting procedure
```

---

## 🎨 Development Guidelines

### HTML Guidelines
- Use clean, semantic HTML5 elements (`<main>`, `<header>`, `<section>`, `<footer>`).
- Ensure all interactive elements have appropriate ARIA attributes and accessibility labels for screen readers.
- Keep the structure modular so script bindings stay clean.

### CSS Guidelines
- Maintain modern CSS practices using **Flexbox** or **CSS Grid** for layout alignment.
- Keep styling responsive across mobile, tablet, and desktop breakpoints.
- Use CSS custom properties (variables) for colors and fonts where possible to facilitate easy theme switching.

### JavaScript Guidelines
- Write modern, clean ES6+ JavaScript.
- Avoid global variable pollution by encapsulating logic appropriately.
- Handle DOM manipulation efficiently and avoid redundant queries inside timer loops (`setInterval` / `requestAnimationFrame`).
- Include helpful code comments for complex functions.

---

## 💬 Git Commit Guidelines

Write clear and descriptive commit messages using standard prefixes:

- `feat:` A new feature for the user or UI.
- `fix:` A bug fix.
- `docs:` Changes only to documentation (`README.md`, `CONTRIBUTING.md`, etc.).
- `style:` Formatting, indentation, CSS styling adjustments with no logical code changes.
- `refactor:` Code changes that neither fix a bug nor add a feature.
- `perf:` A code change that improves performance.

**Example:**
```bash
git commit -m "feat: add 12/24 hour time format toggle button"
```

---

Thank you for helping make **Live Digital Clock** better! ⏰✨