# CAKRA MEP — Mechanical, Electrical & Plumbing Contractor

A modern, responsive portfolio and corporate website for **CAKRA MEP**, an integrated Mechanical, Electrical & Plumbing (MEP) contractor specializing in utility engineering, building services infrastructure, and facility lifecycle reliability.

Built upon the Builderz template foundation by [HTML Codex](https://htmlcodex.com), adapted and customized specifically for MEP engineering contracting.

---

## 🏢 Business Positioning

**CAKRA MEP** delivers comprehensive engineering, procurement, installation, and testing & commissioning (T&C) solutions across commercial, industrial, healthcare, and residential developments.

### Core Disciplines
1. **Mechanical & HVAC Systems:** Central chilled water plants, variable primary pumping, air handling units (AHU), Variable Refrigerant Flow (VRF/VRV), cleanroom ventilation, and acoustic/thermal ductwork.
2. **Electrical Systems:** Medium & low-voltage substations, dry-type power transformers, main distribution switchboards (MDB), generator synchronization, busduct risers, and power factor correction.
3. **Plumbing & Sanitary Systems:** Potable water networks, multi-pump variable speed booster skids, stormwater retention, soil & waste drainage, and sewage treatment plant (STP) connections.
4. **Fire Protection Systems:** Wet and dry automatic fire sprinkler networks, landing hydrants, certified fire pump packages, standpipes, and clean agent gas suppression (FM-200 / Novec 1230).
5. **ELV & Building Systems:** Extra Low Voltage infrastructure, Building Management Systems (BMS), CCTV security, biometric access control, and structured data cabling.
6. **Testing & Commissioning (T&C):** Testing, Adjusting & Balancing (TAB), electrical dielectric/insulation tests, thermal imaging thermography, and integrated emergency scenarios.

---

## 📂 Project Structure

```
bedi-cakra-mep/
├── .gitignore               # Excludes reference template and system artifacts
├── LICENSE.txt              # Creative Commons Attribution 4.0 International License
├── README.md                # Project documentation and developer guide
├── index.html               # Main landing page with full MEP overview
├── about.html               # Company profile, engineering standards, team & FAQs
├── service.html             # Detailed breakdown of all 6 MEP service disciplines
├── team.html                # Lead engineers and discipline directors
├── portfolio.html           # Project showcases with interactive Isotope category filters
├── blog.html                # Technical articles on MEP engineering and standards
├── single.html              # Featured technical article with sidebar widgets
├── contact.html             # Office contact details and interactive inquiry form
├── css/
│   └── style.css            # Main stylesheet (color scheme: #fdbe33, #030f27, #121518)
├── img/                     # Authentic MEP engineering photography, diagrams & icons
├── js/
│   └── main.js              # Template JavaScript initialization and interactive handlers
├── lib/                     # Third-party vendor libraries (Bootstrap, Owl, Slick, etc.)
└── mail/
    ├── contact.js           # AJAX form submission handler
    ├── contact.php          # Backend PHP mail processing script
    └── jqBootstrapValidation.min.js # Form validation library
```

---

## 🛠 Technology Stack

* **Markup & Styling:** HTML5, CSS3, Bootstrap 4.4.1
* **JavaScript Library:** jQuery 3.4.1
* **Typography:** Google Fonts — *Poppins* (Weights: 100–900)
* **Iconography:** Font Awesome 5.10.0 & Custom Flaticon MEP Webfont
* **Sliders & Galleries:** Slick Carousel, Owl Carousel 2, Lightbox2
* **Animations:** WOW.js, Animate.css, jQuery Waypoints, jQuery Counter-Up, jQuery Easing
* **Filtering:** Metafizzy Isotope (category filter on `portfolio.html`)

---

## 🚀 Running Locally

This website is a static HTML5/CSS3/JavaScript project and does not require complex build steps or Node.js runtimes.

### Option 1: Direct Browser Access
Simply double-click or open any HTML file (e.g. `index.html`) in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Python)
To test smooth AJAX responses and prevent CORS restrictions:
```bash
# Python 3
python -m http.server 8000
```
Then navigate to: `http://localhost:8000`

---

## ⚖️ Licensing & Attribution

* Template creative foundation designed by [HTML Codex](https://htmlcodex.com).
* Licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
* In accordance with CC BY 4.0, the attribution backlink (`Designed By HTML Codex`) in the website footer has been retained intact.
* Third-party libraries (`lib/`) are subject to their respective open-source licenses (MIT / BSD).

