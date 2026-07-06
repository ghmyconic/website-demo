Bright-World NGO Website

Project Information

Student Name: Abraham Mensah  
Index Number: BC/ITS/25/204  
Course: WebTech & Concept - Midsemester Project  
Institution: Takoradi Technical University  
Submission Date: 20th July 2026  



Project Overview

This is a professional, fully responsive website for a fictional environmental NGO called Bright-World.
The website was developed using HTML5 and CSS only, without any JavaScript frameworks, CSS preprocessors,
or JavaScript at all, meeting all the technical requirements of the midsemester project.

Design Update: "Liquid Glass" Redesign

The site was redesigned around a frosted-glass, pill-shaped "bubble" visual language (inspired by modern
iOS-style interfaces) while keeping the original brand palette — green, blue, and yellow. Everything below
is achieved with pure CSS (backdrop-filter, gradients, transitions) and no JavaScript.

What changed:
- Navigation bar: rebuilt as a floating, frosted-glass pill bar with a gradient hover/active state and a
  pure-CSS (checkbox hack) hamburger menu for mobile — no JavaScript required.
- Buttons: pill-shaped with a glossy gradient, soft shadow, and a lift/press animation on hover and click.
- Cards, stat tiles, tables and form panels: restyled as frosted glass "bubbles" with rounded corners and
  hover lift effects.
- New Google Fonts pairing (Quicksand for headings, Inter for body text) for a friendlier, more modern feel.
- Footer redesigned with a dark glass gradient and a curved top edge.

Bugs fixed:
- About Us page said the foundation was "Founded in 2026" but then referenced "the past 16 years" —
  corrected to 2010 to match the founding date already used in the site footer and Donate page.
- Projects page had an invalid stray `<p color>` attribute on the Coastal Cleanup card — removed.
- Gallery page had a broken/truncated `alt` attribute (a line break inside the quotes) on one image —
  fixed to a proper, descriptive alt text ("Environmental Sustainability").
- Logo alt text was inconsistent across pages ("Bright-World Logo" vs "Bright-World Initiative Logo") —
  standardized to "Bright-World Foundation Logo" everywhere.
- The Core Values list on the About page relied on the browser's default bullet styling, which breaks once
  a site-wide CSS reset is introduced — explicit list styling was added so it displays correctly.

New content added:
- Newsletter signup section on the Home page.
- FAQ accordion on the Donate page (built with native `<details>`/`<summary>`, so it needs no JavaScript)
  covering tax receipts, recurring donations, payment methods, and fund usage.
- A floating "Donate Now" quick-action bubble visible on every page except Donate itself.
- "Back to top" links in every page footer.
- Meta description tags on every page for better SEO and link previews.
- `aria-current="page"` on the active navigation link on every page, both for accessibility and so the
  current page is visually highlighted in the nav bar.
- `autocomplete` attributes on name/email/phone form fields across the Contact, Donate, and Volunteer
  forms for a smoother experience with browser autofill.


Features Implemented

HTML5 Semantic Elements
- `<header>` - Navigation and branding
- `<nav>` - Navigation menu
- `<main>` - Primary content
- `<section>` - Content sections
- `<footer>` - Footer with contact and links
- `<table>` - Data presentation
- `<form>` - Contact, volunteer, and donation forms
- `<details>` / `<summary>` - FAQ accordion (no JavaScript)
- `<img>` - Image elements
- `<a>` - Hyperlinks
- `<ul>`, `<li>` - Lists

CSS Features
- Flexbox Layout - Navigation bars, card layouts, button groups
- CSS Grid - Project cards, gallery grid, stats section
- Responsive Design - Media queries for mobile, tablet, and desktop
- Glassmorphism - backdrop-filter blur on nav, cards, forms, tables, footer
- Hover Effects - Interactive buttons and cards
- Transitions & Animations - Smooth hover states and transformations
- Pure-CSS mobile navigation menu (checkbox hack, no JavaScript)
- Card Components - Styled project and testimonial cards
- Shadows & Rounded Corners - Modern visual styling
- External Stylesheet - All styles in `css/style.css`
- CSS Variables - Color scheme and spacing management

Responsive Breakpoints
- Desktop: 1200px and above
- Tablet: 768px - 991px
- Mobile: Below 768px
- Small Mobile: Below 480px



Project Structure

ngo_website/
├── index.html              # Home page
├── about.html              # About Us page
├── projects.html           # Projects/Programs page
├── gallery.html            # Gallery page
├── volunteer.html          # Volunteer registration page
├── donate.html             # Donation page
├── contact.html            # Contact page
├── css/
│   └── style.css           # Main stylesheet
└── images/
    └── (place your project images here — file names are referenced directly in the HTML,
         e.g. "Bright world.png", "Community Development.png", "costal.jpg", etc.)


Color Scheme

- **Primary Color:** #2e7d32 (Green)
- **Secondary Color:** #1565c0 (Blue)
- **Accent Color:** #fbc02d (Yellow)
- **Text Color:** #2b2f2c (Dark Gray)
- **Light Background:** #f4f7f5
- **White:** #ffffff


Requirements Compliance

HTML5 Only - No JavaScript used  
CSS Only - No Bootstrap, Tailwind, or preprocessors  
Semantic HTML - Proper use of header, nav, main, section, footer  
Responsive Design - Works on desktop, tablet, and mobile  
Flexbox & Grid - Both layout methods demonstrated  
Forms - Contact, volunteer, and donation forms included  
Tables - Data table in About Us page  
Seven Pages - Home, About, Projects, Gallery, Volunteer, Donate, Contact  
Professional Design - Modern, clean, glass-bubble visual identity  
Student Information - Name and index number in header of all pages  


Credits

Designed and Developed by: Abraham Mensah  
Index Number: BC/ITS/25/204  
Course: WebTech & Concept  
Date: 2026


License

This project is submitted as coursework for Takoradi Technical University and is for educational purposes only.
