# Luméa Beauty — Career Application Portal 🌸

> **“Create. Inspire. Belong.”**  
> Build the future of beauty with people who believe that creativity has no single definition.

A frontend web development project designed as a career portal for **Luméa Beauty**, a fictional modern beauty company and creative atelier founded in Bengaluru.

🌐 **Live Demo:** [https://lumea-beauty-alpha.vercel.app](https://lumea-beauty-alpha.vercel.app)  
📦 **Repository:** [https://github.com/prapdt-code/lumea-beauty](https://github.com/prapdt-code/lumea-beauty)

---

## 📸 Overview & Design Philosophy

Luméa Beauty's career website is built with a restrained, editorial aesthetic. It avoids generic SaaS gradients, heavy glassmorphism, or artificial corporate HR patterns, opting instead for:

- **Restrained Color Palette**: Warm ivory (`#FAF7F2`), cream (`#F3ECE2`), muted rose (`#C68B84`), soft brown (`#765B51`), and charcoal (`#252220`).
- **Editorial Typography**: Serif display headings (*Cormorant Garamond*) paired with clean, accessible sans-serif body copy (*Plus Jakarta Sans*).
- **Tactile UI Elements**: Handcrafted brand emblem centerpiece, subtle border lines, rounded cards, and gentle interactions.

---

## 🗂️ Project Structure & Pages

The application is structured as a dedicated multi-page website:

| Page | File | Description |
| :--- | :--- | :--- |
| **Home** | [`index.html`](index.html) | Brand introduction, hero tagline, interactive Luméa Atelier logo seal, and navigation teasers. |
| **About** | [`about.html`](about.html) | Heritage story, Bengaluru formulation origins, 4 core pillars (*Skin First*, *Radical Honesty*, *Tactile Craft*, *Every Hue*), and brand milestones. |
| **Open Roles** | [`roles.html`](roles.html) | 6 open job openings with interactive category filtering and detail modal views. |
| **Life at Luméa** | [`life.html`](life.html) | Culture guide highlighting our 3 values (*Creative Freedom*, *Rest & Restoration*, *Cohort Learning*) and studio perks. |
| **Apply** | [`apply.html`](apply.html) | Standalone 5-step application form with validation, progress tracking, and file uploads. |

---

## 💼 Open Roles Included

1. **Social Media & Content Intern** — Marketing · Bengaluru · Internship
2. **Makeup Artist** — Creative · Mumbai · Full-time
3. **Marketing Associate** — Marketing · Delhi · Full-time
4. **Graphic Designer** — Creative · Bengaluru · Full-time
5. **Product Development Intern** — Product / R&D · Hyderabad · Internship
6. **Customer Experience Associate** — Product / CX · Remote · Part-time

*Clicking "Apply" on any role automatically passes the role ID as a query parameter and selects it inside the application form.*

---

## ✨ Multi-Step Application Flow (`apply.html`)

The application process is divided into a structured 5-step journey:

1. **Step 01 — Personal Information**:
   - Full Name, Email, Phone, City, and Date of Birth with live field validation.
   - Profile Photo upload with real-time circular image preview.
   - Optional LinkedIn and Portfolio / Website links.

2. **Step 02 — Role & Preferences**:
   - Clickable interactive role cards (highlighted on selection).
   - Employment Type radio pills (*Internship*, *Full-time*, *Part-time*).
   - Preferred Location pills (*Bengaluru*, *Mumbai*, *Delhi*, *Hyderabad*, *Remote*, *Open to relocation*).

3. **Step 03 — Experience & Background**:
   - Experience tier selection and availability / notice period.
   - Dynamic work/project experience entries (*+ Add Another Experience* and *Remove*).
   - Personal statement / cover note.

4. **Step 04 — Portfolio & Documents**:
   - Drag-and-drop / click-to-upload Resume/CV area with file confirmation badge.
   - Online Portfolio / Figma / Behance / Drive URL.
   - Additional creative case-study notes.

5. **Step 05 — Review & Confirmation**:
   - Summary review card displaying candidate details, avatar preview, role preferences, and attached documents before final submission.
   - **Application Success Screen**: Displays a confirmation message personalized to the candidate's selected role along with a unique reference tracking ID (e.g. `#LUM-84920`).

---

## 🛠️ Built With

- **HTML5** — Semantic, accessible markup.
- **CSS3** — Custom properties (variables), responsive flexbox and CSS grid layouts.
- **JavaScript (ES6+)** — Client-side state management, query parameter routing, form validation, and file reading (FileReader API).
- **Google Fonts** — *Cormorant Garamond* & *Plus Jakarta Sans*.

---

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/prapdt-code/lumea-beauty.git
   cd lumea-beauty
   ```

2. Start a simple local server:
   ```bash
   # Using Python 3:
   python3 -m http.server 8080

   # Or using Node:
   npx serve .
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

---

## 📄 License & Credits

Designed and coded for **Luméa Beauty Studio**. Built for creative minds who believe that creativity has no single definition.
