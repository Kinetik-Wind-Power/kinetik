# Kinetik Wind Power — Website Plan

## 🏢 Company Summary

**Kinetik Wind Power** is a startup wind energy services company based in **Kavalkinaru, Tirunelveli District, Tamil Nadu, India**. Led by **K. Ramachandran** (Managing Director, 25+ years experience), the company provides end-to-end solutions for wind turbine installation, operation, and maintenance.

**Specialization:** Vestas RRB make turbines (225 kW, 500 kW, 600 kW)

---

## 🎯 Website Goals

1. Establish credibility as a professional wind energy services company
2. Showcase core services with real field images from the company's portfolio
3. Generate leads via a contact form
4. Modern, premium, mobile-responsive single-page landing website

---

## 🧭 Site Architecture (Single Page Landing)

The website will be a single `index.html` file with CSS and JS, using smooth scroll navigation between sections:

### Navigation Bar (Sticky)
- Logo (from PDF: `kinetik-pdf-page1-img2.jpeg`)
- Links: Home | About | Services | Gallery | Team | Contact
- Mobile hamburger menu

### Section 1: Hero
- Full-width hero with dramatic wind turbine background image
- Gradient overlay (dark blue/green tones matching the Kinetik brand)
- Heading: "Powering Tomorrow, Sustainably"
- Subtext: "End-to-end wind energy solutions — Installation, Operation & Maintenance"
- CTA Button: "Get in Touch" → scrolls to contact section
- Animated counter stats bar below hero:
  - "25+ Years Experience"
  - "Vestas RRB Specialists"
  - "End-to-End Solutions"
  - "Fastest Response Time"

### Section 2: About Us
- Split layout: text left, image right
- Company overview text from company profile
- Image: field work photo from PDF

### Section 3: Core Services
- Section heading with underline accent
- Grid of service cards (3 columns on desktop, 1 on mobile) with icons and real photos:

| Service | Image Source |
|---------|-------------|
| Electronics Module Service | PDF page 4 images |
| Panel Rewiring Work | PDF page 5 images |
| Cable Joint (up to 33kV) | PDF page 6 images |
| Spare Parts Supply | PDF page 9 images |
| Hydraulic & Yaw Unit Servicing | PDF page 10 images |
| Generator Services (Nacelle) | PDF page 11 images |
| Gearbox Service (Nacelle) | PDF page 12 images |
| Fire-Damaged Nacelle Refurbishment | PDF page 14 images |
| Installation & Commissioning | PDF page 16 images |

### Section 4: Why Choose Us
- Highlight cards with animated icons:
  - ✅ Expert Team with 25+ years
  - ⚡ Fastest fault response time in the industry
  - 📊 Transparent reporting system
  - 💰 Transparent billing system

### Section 5: Gallery / Portfolio
- Masonry-style image gallery using actual field photos from the PDF
- Lightbox modal on click
- Categories: Installation, Maintenance, Equipment

### Section 6: Our Team
- Team member cards:
  - G. Samraj – Executive Manager
  - R. Rinose – CT Service Manager
  - T. Sunder Raj – Project Manager
  - B. Saji – Service Manager
  - S. Ananthakrishnan – Electrical Engineer
  - C. Senthil Kumar – Mechanical Supervisor

### Section 7: Contact
- Two-column layout:
  - Left: Contact form (Name, Email, Phone, Message, Submit)
  - Right: Company address, phone, email details
- Company Info:
  - **Address:** No:8/60 E2, 5th Cross Street, Star City, Kavalkinaru, Tirunelveli District – 627 105, Tamil Nadu
  - **Phone:** K. Ramachandran — 9943431764
  - **Email:** kinetikwindpower79@gmail.com

### Footer
- Logo, copyright, social links placeholder
- Quick links to all sections

---

## 🎨 Design System

### Brand Colors (from the Kinetik logo)
| Token | Hex | Usage |
|-------|-----|-------|
| Primary Blue | `#1B3A8C` | Headers, nav, buttons |
| Accent Green | `#2ECC40` | CTAs, highlights, accents |
| Deep Navy | `#0D1B3E` | Footer, dark backgrounds |
| Light Gray | `#F5F7FA` | Alternate section backgrounds |
| White | `#FFFFFF` | Cards, main backgrounds |
| Text Dark | `#1A1A2E` | Body text |

### Typography
- **Headings:** "Outfit" (Google Fonts) — modern, geometric, professional
- **Body:** "Inter" (Google Fonts) — clean and highly readable
- **Accent/Stats:** "Space Grotesk" — for numbers and data

### Micro-Animations
- Scroll-triggered fade-in/slide-up for sections
- Counter animation for hero stats
- Hover scale on service cards
- Smooth parallax on hero background
- Hamburger menu transition

### Inspiration Sources
| Website | Key Takeaway |
|---------|-------------|
| Narayana Wind Power | Colorful service grid, hero banner style |
| Deriva Energy | Clean section alternation, professional industrial photography |
| Kinetic Wind Tech | Serif + sans-serif typography mix, startup feel |
| Suzlon | Stats/credibility bar, deep corporate navigation |

---

## 📁 File Structure

```
kinetik/
├── index.html          # Main landing page
├── style.css           # All styles
├── script.js           # Animations, menu, form handling
├── images/             # All images (PDF extracts + generated)
│   ├── kinetik-pdf-page1-img2.jpeg   (Logo)
│   ├── kinetik-pdf-page4-*.png       (Electronics module)
│   ├── kinetik-pdf-page5-*.png       (Panel rewiring)
│   ├── kinetik-pdf-page6-*.png       (Cable joint)
│   ├── ... (all 50 PDF images)
│   ├── hero-wind-turbines.png        (Generated hero)
│   ├── offshore-wind-farm.png        (Generated)
│   ├── turbine-closeup.png           (Generated)
│   ├── wind-technicians.png          (Generated)
│   ├── green-energy-grid.png         (Generated)
│   └── wind-turbine-field.png        (Generated)
├── claude.md           # This plan
└── profile             # Company profile text
```

---

## ✅ Verification Plan

### Browser Testing
- Open `index.html` in the browser and verify:
  1. All sections render correctly
  2. Navigation smooth-scrolls to each section
  3. Mobile hamburger menu works
  4. All images from the PDF load properly
  5. Counter animations trigger on scroll
  6. Contact form validates inputs
  7. Responsive layout works at 375px, 768px, and 1440px widths

### Visual Checks
- Logo from PDF displays correctly in navbar
- Service cards show the correct real field photos
- Color scheme matches the Kinetik brand identity (blue + green)
- Typography loads from Google Fonts
