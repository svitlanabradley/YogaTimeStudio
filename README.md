
# 🧘‍♀️ Yoga Time Studio

**Yoga Time Studio** is a fully responsive, accessible website for a yoga studio. It was developed to demonstrate strong design principles and front-end development best practices. The site includes dynamic content loading, form interaction, and smooth, user-friendly navigation—built with clean, well-structured HTML, CSS, and JavaScript using ES modules.

---

## 📄 Pages

- **Home**: A landing page with intro content and scroll navigation to the booking form.
- **Classes**: Dynamically generated list of yoga classes using JSON.
- **Contact**: Contact info and details about the studio.
- **Thank You Page**: Confirmation after form submission.

---

## 🎯 Features & Requirements Covered

### ✅ **Design Principles**
- Proximity, alignment, repetition, contrast, and white space are applied throughout.
- Consistent color palette and typography enhance readability.
- Responsive layout with no horizontal scrolling at any size (min. 320px).
- Navigation menu uses responsive behavior and supports wayfinding.

### 📱 **Responsiveness**
- Fully responsive design for mobile, tablet, and desktop.
- Responsive hamburger menu for small screens.

### 🧭 **Wayfinding**
- Clear site navigation across all pages.
- Active link highlighting and accessible page titles/meta descriptions.

### 🌍 **Accessibility & Usability**
- All interactive elements are keyboard and screen-reader friendly.
- Color contrast meets WCAG standards.
- Semantic HTML structure used throughout.

### 🖼️ **Optimized Images**
- Web-optimized images with intrinsic aspect ratios.
- `loading="lazy"` used to progressively load media.

---

## 📋 HTML Form

- Integrated HTML5 booking form with name, email, class selection, and message fields.
- Form data is displayed on a confirmation page.
- Mobile-friendly and accessible input controls.

---

## 🧠 JavaScript Functionality

### ✅ **JavaScript Concepts Applied**
- **ES Modules** for clean, organized code.
- **DOM interaction** to modify page elements and handle events.
- **Array methods** to loop and generate content dynamically.
- **Template literals** used for building HTML strings.
- **localStorage** stores user form inputs for better UX.
- **Fetch API** used to retrieve class data from a local JSON file.
- **Async/await + try/catch** for error-handled data fetching.
- **Modal dialog** structure for enhanced interactivity.
- **15+ items** dynamically rendered with at least 4 pieces of data each.

---

## 📦 Performance

- Each page is optimized to stay under 500kB total data transfer from an empty cache.
- Lightweight CSS and JavaScript are bundled efficiently.
- Lazy loading boosts performance on slower networks.

---

## 🔧 Technologies Used

- **HTML5**, **CSS3**, **JavaScript (ES6+)**
- **Modular JavaScript** structure
- Responsive design via media queries and `aspect-ratio`
- JSON for dynamic content

---

## 🔗 Meta & SEO

- Unique meta titles and descriptions for each page.
- Favicon and social sharing meta tags included for better visibility.

---

## 📁 Project Structure

\`\`\`bash
📁 yoga-studio/
├── index.html           # Landing page
├── classes.html         # Yoga class schedule
├── contacts.html        # Contact & form page
├── thanks.html          # Confirmation page after form submission
├── siteplan.html        # Project planning and documentation
├── js/
│   └── main.js          # ES module JavaScript logic
├── css/
│   └── styles.css       # Custom responsive styles
├── data/
│   └── classes.json     # JSON data source for yoga classes
├── assets/
│   └── images/          # Optimized images with lazy loading
└── README.md

\`\`\`

---

## 🧪 Future Improvements

- Backend integration for real booking submissions.
- Testimonials or blog feature.
- Accessibility audit and performance testing via Lighthouse.

---

## 📜 License

This project is for educational and portfolio purposes.
