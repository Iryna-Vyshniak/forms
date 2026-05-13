# Universal Form System

A comprehensive, beautifully designed demonstration of HTML5 form capabilities focused on semantic structure, accessibility (A11y), and modern CSS architecture.

This project includes both a standard registration form and an advanced multi-section data entry interface, showcasing a wide variety of native HTML form elements without relying on JavaScript frameworks or external dependencies.

---

## ✨ Features

### ♿ Accessibility (A11y) First

Built with accessibility as a core principle using:

- Semantic HTML elements (`fieldset`, `legend`, `label`)
- Proper form labeling and associations
- `aria-*` attributes for assistive technologies
- Screen-reader-only utility classes (`sr-only`)
- Keyboard-friendly focus states with `:focus-visible`

---

### 🎨 Modern CSS Architecture

- Native CSS Custom Properties (Variables)
- CSS Grid & Flexbox layouts
- Responsive design patterns
- Smooth transitions and visual feedback
- Modern pseudo-classes:
  - `:valid`
  - `:invalid`
  - `:focus-visible`
  - `:placeholder-shown`

---

### 🌗 Automatic Dark / Light Mode

Supports automatic theme switching based on the user's system preferences using:

```css
@media (prefers-color-scheme: dark)
```

---

### 🧩 Rich HTML5 Input Support

Demonstrates proper usage of native HTML input types including:

- Text
- Email
- Password
- Search
- URL
- Telephone
- Number
- Range
- Date & Time
- Color Picker
- File Upload
- Radio Buttons
- Checkboxes
- Select & Multi-select
- Datalist Suggestions
- Textarea

---

### ✅ Native Validation Experience

Uses built-in browser validation combined with custom CSS states to provide immediate and accessible visual feedback.

---

### 📱 Fully Responsive

Optimized for:

- Mobile devices
- Tablets
- Laptops
- Large desktop screens

---

## 📂 Project Structure

```txt
.
├── index.html
├── extra-form.html
└── styles/
    └── index.css
```

### `index.html`

**Standard Registration Form (Ukrainian)**

A localized production-style registration form demonstrating:

- Text inputs
- Email fields
- Password inputs
- Radio buttons
- Checkboxes
- Native validation
- Accessible form structure

---

### `extra-form.html`

**Universal Entry Form (English)**

An advanced demonstration featuring:

- Complex input types
- Logical form sections
- Datalists
- Custom file upload styling
- Temporal settings
- Advanced controls
- Documentation fields

---

### `styles/index.css`

**Global Stylesheet**

Contains:

- Theme variables
- Global resets
- Layout utilities
- Form styling
- Responsive breakpoints
- Dark mode rules

---

## 🚀 Getting Started

This project uses only standard web technologies.

No build tools, package managers, or frameworks are required.

### 1. Clone or Download

```bash
git clone <repository-url>
```

Or download the ZIP archive directly from GitHub.

---

### 2. Open in Browser

Open either:

- `index.html`
- `extra-form.html`

in any modern web browser.

---

### 3. Test Responsiveness

Resize the browser window or use Developer Tools → Device Mode.

---

### 4. Test Dark Mode

Switch your operating system appearance between Light and Dark modes.

---

## 🛠️ Technologies Used

- HTML5
  - Semantic Structure
  - Native Forms
  - Browser Validation

- CSS3
  - Custom Properties
  - CSS Grid
  - Flexbox
  - Media Queries
  - Backdrop Filters

---

## 🎨 Design System

The project uses a scalable design system powered by CSS variables.

### Includes

- Fluid typography using `clamp()`
- Consistent spacing scale
- Adaptive color palette
- Accessible focus indicators
- Responsive layout tokens

### Example Variables

```css
:root {
  --spacing-sm: 0.5rem;
  --spacing-md: 1rem;
  --spacing-lg: 2rem;

  --radius-md: 1rem;

  --transition-fast: 150ms ease;
}
```

---

## ♿ Accessibility Highlights

- Proper heading hierarchy
- Semantic grouping with `fieldset`
- Keyboard navigation support
- Screen reader compatibility
- Visible focus states
- High contrast support
- Required field indicators

---

## 📄 License

This project is provided for educational and demonstration purposes.