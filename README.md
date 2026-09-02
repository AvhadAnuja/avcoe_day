# 🎄 Xmas Countdown

A festive, animated Christmas countdown website built with plain HTML, CSS, and JavaScript. This was created as a learning project to practice front-end development and Git/GitHub workflows.

## ✨ Features
- Live countdown timer (days, hours, minutes, seconds) that automatically counts down to the next upcoming December 25th
- Animated background with floating particles and falling snowflakes
- Sticky header with scroll-based styling and scroll-spy navigation (highlights the active section as you scroll)
- Responsive mobile navigation menu
- Sections for About, Upcoming Events, and Holiday Traditions
- Newsletter signup form (front-end only, with a confirmation message)
- Fully responsive layout for desktop and mobile

## 🛠 Tech Stack
- HTML5
- CSS3 (custom properties, animations, responsive design)
- Vanilla JavaScript (no frameworks or build tools)
- Google Fonts (Syne, Space Grotesk)

## 📂 Project Structure
```
avcoe_day-main/
├── index.html                          # Main page markup
├── templatemo-605-xmas-countdown.css   # Styles
├── templatemo-605-countdown-scripts.js # Countdown logic & interactivity
├── images/                             # Section images
└── README.md
```

## ▶️ Getting Started
No build tools or dependencies are required — it's a static site.

1. Clone the repository
   ```bash
   git clone https://github.com/AvhadAnuja/avcoe_day.git
   cd avcoe_day
   ```
2. Open `index.html` directly in your browser, **or** serve it locally for the best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000` in your browser.

## 📝 Notes
- The countdown always targets the next December 25 at 6:00 PM — once one Christmas passes, it automatically starts counting toward the following year.
- Section images are placeholders and can be swapped out with your own photos in the `images/` folder (keep the same filenames, or update the `src` paths in `index.html`).
- The newsletter form is a front-end demo only — it does not send real emails or store submissions. Connect it to a backend or a service like Mailchimp/Formspree to make it functional.

## 🙏 Credits
Base design adapted from the [TemplateMo 605 Xmas Countdown](https://templatemo.com/tm-605-xmas-countdown) template, customized and extended for learning purposes.

## 👤 Author
**Anuja Avhad**
[GitHub](https://github.com/AvhadAnuja) · [Email](mailto:avhadanuja23@gmail.com)
