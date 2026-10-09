# 🔴 REDLINE Fitness

### TRAIN IN A DIFFERENT LIGHT.

A premium, fully responsive fitness studio website built with **HTML5, CSS3, and JavaScript**.

REDLINE Fitness is a fictional boutique fitness studio concept based in Prague, Czech Republic. The project combines bold typography, cinematic imagery, immersive interactions, and a distinctive dark visual identity to deliver a modern fitness experience.

**[🌐 Live Demo](https://glovatskiy.github.io/redline-fitness/)** | **[💻 GitHub Repository](https://github.com/glovatskiy/redline-fitness)**

---

## 📸 Project Preview

<table>
  <tr>
    <th width="50%">DEFAULT MODE</th>
    <th width="50%">RED ROOM MODE</th>
  </tr>
  <tr>
    <td align="center" valign="top">
      <img
        src="./assets/images/redline-fitness.png"
        alt="REDLINE Fitness website — Default Mode"
        width="100%"
      />
    </td>
    <td align="center" valign="top">
      <img
        src="./assets/images/redline-fitness-redroom-mode.png"
        alt="REDLINE Fitness website — RED ROOM Mode"
        width="100%"
      />
    </td>
  </tr>
</table>

<p align="center">
  <em>Two distinct visual experiences. One REDLINE identity.</em>
</p>

---

## ✨ Features

### 🔴 RED ROOM — Signature Theme Switcher

One of REDLINE Fitness's signature features is **RED ROOM**, an immersive alternative visual mode that transforms the website's atmosphere.

- Switch between the default dark theme and RED ROOM.
- Dynamic background, surface, and accent color changes.
- Red glow effects and atmospheric styling.
- Smooth visual transitions.
- Theme management using CSS custom properties.
- CSS-driven state management with the `:has()` selector.
- No JavaScript required for theme switching.

### 📸 FIND YOUR RED — Signature Photo Experience

An interactive section inviting visitors to experience the REDLINE aesthetic.

- Custom-designed photo upload interface.
- Red-light-inspired visual identity.
- Support for selecting images from the user's device.
- Dedicated layout combining cinematic imagery and interactive UI.
- Designed for future personalized photo transformations.

> **Note:** The current implementation includes the photo-upload interface. Image processing and downloadable results are planned enhancements.

### 📱 Fully Responsive Design

The website is designed to provide a consistent experience across desktop, tablet, and mobile devices.

- Desktop, tablet, and mobile layouts.
- Responsive typography and spacing.
- CSS Grid and Flexbox layouts.
- Interactive hamburger navigation on mobile.
- Responsive training cards and membership pricing.
- Optimized layouts for different viewport sizes.

### 🏋️ Trainer Showcase

A dedicated section introducing the REDLINE coaching team.

- Three trainer profiles.
- Professional photography.
- Training specializations.
- Individual biographies.
- Responsive trainer cards.

### 📅 Training Schedule

A structured class schedule designed to make training information easy to explore.

- Training sessions displayed as individual cards.
- Class names, times, and difficulty levels.
- TODAY and TOMORROW controls.
- Available spots and fully booked indicators.
- Booking and waitlist entry points.
- Clear visual distinction between class availability states.

### 💳 Membership Plans

Three membership options designed for different training needs.

| Membership | Description |
|------------|-------------|
| **DROP IN** | Single-class access without commitment |
| **REDLINE 8** | Eight classes per month with additional benefits |
| **UNLIMITED** | Unlimited training access with premium benefits |

Additional features:

- Highlighted most popular membership.
- Transparent pricing and benefits.
- Clear calls to action.
- Responsive pricing cards.

### 🎨 Cinematic Visual Design

REDLINE Fitness uses a high-impact visual language inspired by premium boutique fitness studios.

- Full-width cinematic hero background.
- Oversized editorial typography.
- Bebas Neue and Inter font pairing.
- Black, charcoal, ivory, and red color palette.
- Animated training-discipline ticker.
- High-contrast buttons and interactive elements.
- Hover effects and transitions.
- Consistent design tokens and spacing.

### 🌐 Additional Features

- Semantic HTML5 structure.
- Descriptive image alternative text.
- Accessibility attributes for interactive elements.
- Custom SVG favicon.
- SEO metadata.
- Open Graph metadata for social sharing.
- Footer navigation and social media links.
- Deployment using GitHub Pages.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic website structure |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript** | Interactive navigation and UI behavior |
| **CSS Grid** | Responsive layouts |
| **Flexbox** | Flexible interface components |
| **CSS Custom Properties** | Design tokens and theme management |
| **CSS `:has()`** | CSS-driven RED ROOM theme switching |
| **Google Fonts** | Bebas Neue and Inter |
| **Font Awesome** | Interface and social media icons |
| **Git** | Version control |
| **GitHub** | Repository hosting |
| **GitHub Pages** | Website deployment |

---

## 🎨 Design System

The REDLINE visual identity emphasizes **intensity, confidence, and minimalism**.

### Typography

**Bebas Neue**
- Main headings
- Branding
- Editorial statements
- Prominent UI elements

**Inter**
- Body text
- Descriptions
- Supporting content
- Interface labels

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| REDLINE Red | `#C40000` | Primary brand accent |
| Black | `#000000` | Main dark backgrounds |
| Charcoal | Dark gray tones | Cards and secondary surfaces |
| Ivory | Off-white tones | Text and contrast |

### Design Principles

- Strong visual hierarchy.
- Oversized editorial typography.
- Minimal distractions.
- High-contrast interactions.
- Consistent spacing and alignment.
- Reusable design patterns.
- Responsive layouts.
- Cohesive visual identity.

---

## 📂 Project Structure

```text
redline-fitness/
├── index.html
├── style.css
├── assets/
│   └── images/
│       ├── hero-img.webp
│       ├── marcus-thorne-trainer.webp
│       ├── elena-rossi-trainer.webp
│       ├── david-chen-trainer.webp
│       ├── find-your-red.webp
│       ├── favicon.svg
│       ├── redline-fitness.png
│       └── redline-fitness-redroom-mode.png
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/glovatskiy/redline-fitness.git
```

### 2. Navigate to the project

```bash
cd redline-fitness
```

### 3. Run locally

Open `index.html` directly in your browser.

Alternatively, use the **Live Server** extension in Visual Studio Code.

No dependencies, package installation, or build process are required.

---

## 💡 Development Process

This project was developed as part of an **AI-Assisted Frontend Development Practicum**.

The development process followed a structured workflow combining UI/UX design, frontend implementation, testing, and AI-assisted development.

### 1. Planning

- Defined the REDLINE Fitness concept.
- Established the website's structure and content.
- Identified the main sections and user interactions.
- Planned the signature RED ROOM experience.

### 2. UI/UX Design

- Explored visual concepts using UX Pilot.
- Developed desktop, tablet, and mobile layouts.
- Established typography, colors, and spacing.
- Designed the website's visual hierarchy.

### 3. Frontend Implementation

- Built the website using HTML, CSS, and JavaScript.
- Implemented responsive layouts using Grid and Flexbox.
- Created the RED ROOM theme using CSS custom properties.
- Developed mobile navigation and interactive UI elements.

### 4. Testing and Refinement

- Tested responsive layouts across different screen sizes.
- Checked navigation and interactive elements.
- Refined typography, spacing, and visual consistency.
- Reviewed the website's appearance in different theme modes.

### 5. Deployment

- Managed source code using Git and GitHub.
- Deployed the website through GitHub Pages.
- Added SEO and Open Graph metadata.
- Configured a custom SVG favicon.

### AI-Assisted Development

AI tools supported the development workflow through:

- Design exploration and UI/UX planning.
- Implementation guidance.
- Responsive layout refinement.
- Debugging and troubleshooting.
- Code review and improvement suggestions.

The project demonstrates a practical workflow combining frontend development fundamentals with AI-assisted tools.

---

## 🔮 Future Improvements

- [ ] Implement personalized red-light photo transformations.
- [ ] Add downloadable photo results.
- [ ] Connect class bookings to a backend.
- [ ] Implement membership checkout.
- [ ] Add automated frontend tests.
- [ ] Expand accessibility testing.
- [ ] Improve performance and image loading.

---

## 📌 Project Status

**Deployed — Frontend Portfolio Project**

REDLINE Fitness is a fictional fitness studio created for educational and portfolio purposes.

Booking and membership features are demonstrations rather than live commercial services.

---

## 👨‍💻 Author

**Vladislav Glovatskiy**

Frontend Developer | React & JavaScript

[GitHub](https://github.com/glovatskiy)

---

<p align="center">
  <strong>🔴 TRAIN IN A DIFFERENT LIGHT.</strong>
</p>