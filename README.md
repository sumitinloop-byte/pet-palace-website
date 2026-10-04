# Pet Palace — Mobile-First Business Website

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Website-059669?style=for-the-badge&logo=googlechrome&logoColor=white)](https://pet-palace-bhubaneswar.netlify.app)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-17201c?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sumitinloop-byte/pet-palace-website)
[![Google Rating](https://img.shields.io/badge/Google%20Rating-3.9%20%E2%98%85%20(988%20Reviews)-ffc83d?style=for-the-badge&logo=google&logoColor=0f3d2e)](https://maps.google.com/?q=Pet+Palace+Sailashree+Vihar+Bhubaneswar)

> A modern, mobile-first business website built for **Pet Palace**, a neighborhood pet shop in Sailashree Vihar, Bhubaneswar, Odisha. Designed to convert local pet owners and directory searchers into direct phone calls and WhatsApp leads with zero friction.

---

## 🔗 Live Deployment & Repository

- **🌐 Live Production Website:** [https://pet-palace-bhubaneswar.netlify.app](https://pet-palace-bhubaneswar.netlify.app)
- **💻 GitHub Source Repository:** [https://github.com/sumitinloop-byte/pet-palace-website](https://github.com/sumitinloop-byte/pet-palace-website)

---

## 📌 Project Overview & Client Context

Pet Palace is an established local pet store in Bhubaneswar catering to owners of **dogs, cats, birds, rabbits, and fish/aquatics**. While having a strong local reputation (**3.9★ Google Rating with 988 verified reviews**), the business previously lacked an official website or streamlined digital customer contact point.

This project delivers a **production-ready, mobile-first web solution** specifically structured to meet the assignment brief:
- **Mobile-first architecture**: Optimized touch targets, zero layout breakage on small screens, and a persistent native-app-style sticky contact bar.
- **Conversion focus**: Pre-filled WhatsApp routing and one-tap calling rather than generic disconnected contact forms.
- **Strict factual integrity**: Built strictly from verified business lead data without inventing claims, doctor certifications, fake reviews, or unavailable services.

---

## 📱 Key Features & Standout UX Enhancements

### 1. Persistent Mobile Quick-Action Dock (`.mbar`)
- Fixed bottom dock featuring **Call (+91 93376 27738)**, **WhatsApp Enquiry**, and **Google Maps Directions**.
- Responsive behavior: Spans mobile viewports with native app ergonomics and seamlessly docks into a floating pill on tablet/desktop displays.

### 2. Interactive Product & Supply Category Filtering *(Standout Feature)*
- **Interactive filter pills** (`All Supplies`, `Pet Nutrition`, `Accessories & Toys`, `Cages & Habitats`, `Care & Grooming`) provide instant visual filtering with smooth transitions.
- Tapping any pet category card above (*Dogs, Cats, Birds, Rabbits, Fish*) automatically selects the corresponding supply category and smoothly scrolls to it.

### 3. Smart WhatsApp Enquiry Form with One-Tap Query Chips
- Includes quick-query preset chips (`🐶 Dog Food`, `🐱 Cat Litter`, `🦜 Bird Cages`, `🐠 Aquatics`) that auto-fill the query box with one tap.
- Client-side validation: Prevents empty submissions and encodes messages directly into WhatsApp Web / App URLs (`https://wa.me/919337627738?text=...`) without requiring an unconfigured backend.

### 4. Accessible High-Resolution Gallery Carousel
- Tap-to-expand lightbox with **Next / Previous navigation**, active image counter (`Photo X of 4`), and keyboard accessibility (`Escape` to close, `←` / `→` arrow keys to navigate).
- Click-outside detection to dismiss smoothly.

### 5. Verified Social Proof & Google Maps Embed
- Prominently showcases real Google Business proof (**3.9★ / 988 verified reviews**) without fabricated user quotes.
- Live interactive Google Map embed with an overlay badge for one-click directions.

### 6. ScrollSpy Navigation & Progress Bar
- Real-time reading progress bar at the top of the viewport.
- Header navigation links automatically update with active state indicator as the user scrolls through sections.

---

## 🛠️ Tech Stack & Technical Architecture

- **Markup:** Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<address>`, `<footer>`) with SEO meta tags, OpenGraph tags, and full ARIA accessibility attributes.
- **Styling:** Custom Modern CSS3 with CSS Custom Properties (`:root`), fluid typography and spacing via `clamp()`, Flexbox, and CSS Grid.  
  *(Pure native CSS — zero bulky framework overhead, achieving sub-second first contentful paint).*
- **Scripting:** Modular Vanilla JavaScript (ES6+) for drawer toggles, FAQ accordions, filter state management, modal carousel, and WhatsApp URL builders.
- **Icons & Fonts:** FontAwesome 6 (free CDN), Google Fonts (*Fraunces* for editorial brand titles + *Plus Jakarta Sans* for clean UI readability).
- **Deployment:** Netlify continuous deployment with automatic cache invalidation and HTTPS.

---

## 📊 Verified Client Data vs. Project Assumptions

As required by Section 5 of the assignment brief, confirmed business facts are strictly separated from prototype assumptions:

| Field | Verification Status | Source / Value | Note / Handling in Project |
| :--- | :---: | :--- | :--- |
| **Business Name** | ✅ Verified | `Pet Palace` | Displayed prominently across branding, header, and footer. |
| **Category** | ✅ Verified | `Pet Shop` | Tagline and meta descriptions reflect local pet store identity. |
| **Phone / WhatsApp** | ✅ Verified | `+91 93376 27738` | Wired to `tel:` and direct WhatsApp API across all CTAs. |
| **Physical Address** | ✅ Verified | `LC 116/9, Manas Rd, Phase II, Sailashree Vihar, Chandrasekharpur, Bhubaneswar, Odisha 751021` | Rendered with semantic `<address>` and linked to Google Maps. |
| **Google Rating & Reviews** | ✅ Verified | `3.9 ★` (988 verified reviews) | Displayed accurately as business data; no individual quotes were fabricated. |
| **Email Address** | 🚫 Omitted | *Not provided* | **Strictly excluded** from the UI as per assignment guidelines. |
| **Existing Website / Socials** | 🚫 None Found | *None found* | No dead social media links added; focus kept on direct WhatsApp & Call. |
| **Product Inventory** | ⚠️ Assumption | Generic supplies (*Nutrition, Accessories, Habitats, Grooming*) | Labeled as inventory categories with clear WhatsApp stock inquiry disclaimer. |
| **Imagery** | ⚠️ Prototype Mock | High-quality Unsplash pet photography | Used for representation only; disclaimer added in gallery subtext. |

---

## 🖼️ Image Sources & Attribution

All images utilized in this prototype are royalty-free assets from **Unsplash** under the Unsplash License (free for commercial and personal use without copyright infringement):
- **Hero Showcase Dog:** Unsplash photo `1583511655857-d19b40a7a54e`
- **Pet Food (Nutrition):** Unsplash photo `1568640347023-a616a30bc3bd`
- **Pet Accessories:** Unsplash photo `1535294435445-d7249524ef2e`
- **Cages & Aquariums:** Unsplash photo `1516734212186-a967f81ad0d7`
- **Care & Grooming:** Unsplash photo `1583337130417-3346a1be7dee`
- **Gallery Showcase Shots:** Unsplash photos `1548767797-d8c844163c4c`, `1522276498395-f4f68f7f8454`, `1452570053594-1b985d6ea890`, `1585110396000-c9ffd4e4b308`

*(Note: In accordance with project instructions, these stock images are presented purely for prototype catalog visualization and are not claimed to be photos of the physical shop).*

---

## 💻 Local Setup & Run Instructions

No complex build tools, package managers, or `node_modules` are required. The project runs directly in any modern browser:

### Option 1: Quick Local Preview
1. **Clone the repository:**
   ```bash
   git clone https://github.com/sumitinloop-byte/pet-palace-website.git
   cd pet-palace-website
   ```
2. **Open directly in your browser:**
   - On Windows: Double-click `index.html` or run:
     ```powershell
     start index.html
     ```
   - On macOS:
     ```bash
     open index.html
     ```
   - On Linux:
     ```bash
     xdg-open index.html
     ```

### Option 2: Run with a Local Development Server (Recommended for testing)
If you use VS Code or Python:
- **VS Code:** Right-click `index.html` and select **"Open with Live Server"**.
- **Python 3:**
  ```bash
  python -m http.server 3000
  ```
  Then open `http://localhost:3000` in your browser.

---

## 📱 Responsive Testing & Breakpoints

The layout has been tested and verified across major device viewports:
- **Mobile Phones (320px – 480px):** Single-column stacked layout, collapsible drawer menu, horizontal-snap card sliders, and bottom sticky quick-action dock.
- **Tablets (640px – 1023px):** 2 and 3-column responsive grid adjustments, enhanced touch padding.
- **Laptops & Desktops (1024px – 1440px+):** Full desktop navigation with ScrollSpy, multi-column grid displays, interactive hover effects, and centered action pill.

---

## 🤖 AI-Assisted Workflow Disclosure

In accordance with Section 9 of the project evaluation criteria:
- Generative AI was leveraged as an agentic pair-programmer for rapid prototyping, CSS variable structuring, and accessibility auditing.
- All code, business logic, responsive breakpoints, and client facts were manually audited, verified, and refined to ensure full compliance with the client brief and strict performance standards.

---

## 👨‍💻 Developer & Submission Info

- **Project:** Pet Palace Client Website Assignment
- **Target Location:** Sailashree Vihar, Chandrasekharpur, Bhubaneswar, Odisha
- **License:** MIT License