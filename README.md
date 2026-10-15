# Travel Mate - Incredible India Tourism & Vacation Website 🌴

A modern, responsive travel website featuring India's top tourist destinations including beaches, historical forts, and tropical rainforests. Built with **pure HTML5, CSS3, and Vanilla JavaScript** (no external frameworks or build dependencies).

---

## 🌟 Key Features

- **Iconic Indian Destinations**: Showcases top tour spots across India:
  - **Beaches**: Goa (Palolem Beach), Andaman & Nicobar (Radhanagar Beach), Lakshadweep (Bangaram Coral Atoll).
  - **Historical Forts**: Amer Fort & Citadel (Jaipur, Rajasthan).
  - **Forests & Wildlife**: Western Ghats Rainforest & River Safari (Wayanad, Kerala).
  - **Backwaters**: Alleppey Houseboat Cruise (Kerala).
- **Interactive Discover Carousel**: Smooth, touch-friendly image slider powered by Swiper.js.
- **Special Offers & Discounts**: Curated limited-time package deals with discount badges (`30% OFF`, `25% OFF`, `40% OFF`), pricing breakdowns, and perks.
- **Interactive Reservation Modal**: Accessible booking popup that automatically pre-populates with the chosen destination.
- **Contact Concierge Section**: Direct support cards (Phone, Email, Office address) and an interactive travel inquiry form.
- **Instant Toast Notifications**: Smooth feedback toasts for reservation requests, newsletter subscriptions, and contact messages without page reload.
- **Dark & Light Mode**: Seamless theme switching with user preference saved in browser `localStorage`.
- **Smooth Navigation & Scroll Spy**: Active link highlighting that tracks user scroll position across sections.
- **100% Mobile-First Responsive**: Hand-crafted CSS Grid and Flexbox layouts optimized for mobile, tablet, and desktop screens.

---

## 🛠️ Technology Stack

- **HTML5**: Semantic markup, accessible labels (`aria-*`), SEO meta tags.
- **CSS3 (Vanilla)**: CSS Custom Properties (Variables), Flexbox, CSS Grid, media queries, keyframe animations, glassmorphism.
- **JavaScript (Vanilla)**: DOM manipulation, event handling, modal management, form validation, theme persistence with `localStorage`.
- **Libraries (CDN)**:
  - [Remix Icon](https://remixicon.com/) (modern lightweight vector icons)
  - [Swiper.js](https://swiperjs.com/) (touch slider)
  - [ScrollReveal.js](https://scrollrevealjs.org/) (scroll-triggered animations)

---

## 📂 Project Structure

```
Travel Mate/
├── index.html              # Main HTML webpage
├── README.md               # Project documentation
├── assets/
│   ├── css/
│   │   ├── styles.css      # Core styles & dark theme
│   │   └── swiper-bundle.min.css
│   ├── js/
│   │   ├── main.js         # Navigation, modal, forms, theme logic
│   │   ├── scrollreveal.min.js
│   │   └── swiper-bundle.min.js
│   ├── img/                # High-res destination images
│   │   ├── goa.jpg         # Goa beach & sunset
│   │   ├── fort.jpg        # Amer Fort, Jaipur
│   │   ├── andaman.jpg     # Radhanagar beach, Andaman
│   │   ├── forest.jpg      # Wayanad rainforest, Kerala
│   │   ├── kerala.jpg      # Alleppey backwaters houseboat
│   │   └── lakshadweep.jpg # Bangaram island lagoon
│   └── video/
│       └── video.mp4       # Interactive video tour
```

---

## 🚀 How to Run Locally

No build tools or installation needed!

1. Clone or download this repository.
2. Double-click or open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Alternatively, serve with any local HTTP server:
   ```bash
   # Using Python
   python -m http.server 3000

   # Or using Node.js
   npx serve .
   ```
4. Visit `http://localhost:3000` in your browser.

---

## 📝 License & Copyright

© 2026 Travel Mate. All rights reserved.
