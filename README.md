# DriveTech EVO

A premium single-page web application built to showcase master-level European luxury car services. Designed with a high-end, responsive layout featuring fluid background video, elegant dark-mode graphics, glassmorphic panels, and smooth scroll transitions.

---

## 🚗 Core Features

- **Responsive Hero Section**: Autoplaying, muted, and loop-enabled local high-resolution MP4 video background.
- **Modern Casing Layout**: Clear, clean Pascal Case (Title Case) heading hierarchy for enhanced typography.
- **Concierge Actions**: Integrated click-to-call, pre-filled WhatsApp click-to-chat links, and direct Instagram routing.
- **Embedded Dark Map**: Styled dark-themed map embedding featuring the official DriveTech EVO workshop location in Chennai.
- **Premium CSS Styling**: Fully separated, clean CSS rules covering custom animations, scrollbars, and scroll-reveal interactions.

---

## 📂 Folder Structure

```
drivetechevo/
├── assets/
│   └── drivetech_herobg.mp4    # High-quality local hero background video
├── index.css                   # Custom stylesheets and scrollbar settings
├── index.html                  # Main page markup and Tailwind-driven components
└── README.md                   # Project documentation
```

---

## 🛠️ Configuration and Assets

### Video Background
- **Path**: `assets/drivetech_herobg.mp4`
- Set as a native HTML5 video with `autoplay loop muted playsinline preload="auto" object-cover`.

### Stylesheet
- Main design variables, transitions, and scrollbar classes are hosted in `index.css` and linked inside `index.html`.

### Contact Details
- **Phone & WhatsApp**: `+91 80560 62022`
- **Pre-filled message**: *"Hi DriveTech EVO, I would like to inquire about booking a service for my vehicle."*
- **Instagram**: [https://www.instagram.com/drivetechevo/](https://www.instagram.com/drivetechevo/)
- **Google Maps**: [DriveTech EVO Location](https://maps.app.goo.gl/uQgqFZ6e9ApAF6cA7) (Injambakkam, Chennai)

---

## 💻 Local Development

Since this is a static website, you can run it using any simple local server:

Using python:
```bash
python -m http.server 8000
```

Using Node (npx):
```bash
npx http-server -p 8000
```
Open `http://localhost:8000/` in your browser.
