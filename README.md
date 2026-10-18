# GoRide — Ride Sharing Mobile App UI Kit

A modern, high-fidelity ride sharing mobile application interface and interactive prototype featuring ride booking, real-time driver tracking, in-app messaging & calling, wallet top-up, and full service workflows (Ride, Reserve, Rentals, and Package delivery).

---

## 🌟 Key Features

- **🚗 Interactive Ride Booking**: Destination search with autocomplete ("Where to?"), route overview, ride tier selection, and press-and-hold booking confirmation.
- **📍 Driver Matching & Arrival**: Realistic driver matching animation, live ETA countdown, vehicle details, driver rating display, and pickup PIN code.
- **🗺️ Live Trip Navigation**: Dynamic trip tracking screen with route visualization and drop-off ETA.
- **⭐ Rating & Tip Recalculation**: Post-trip summary with star rating, custom tip calculation, and automated feedback toasts.
- **💬 In-App Driver Chat & Calling**: Built-in chat interface with quick replies and simulated voice call screen.
- **💳 Digital Wallet & Auto Top-Up**: Wallet balance overview, preset top-up options, transaction history, and configurable auto top-up thresholds.
- **📦 Multi-Service Ecosystem**: Dedicated screens for On-Demand Rides, Scheduled Reservations, Hourly Rentals, and Package Deliveries.
- **🎨 Complete Figma UI Kit**: Master `.fig` file (`Ride Share Mobile App Ui Kit.fig`) included with design tokens, icons, and component libraries.

---

## 🚀 Live Demo & Deployment

- **Live URL**: Deployed with Vercel
- **GitHub Repository**: [https://github.com/ismailquadri/ride-sharing-mobile-app](https://github.com/ismailquadri/ride-sharing-mobile-app)

---

## 💻 Quick Start

To preview the prototype locally, serve the project with any static HTTP server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then open `http://localhost:8000` in your web browser or mobile simulator.

---

## 📁 Project Structure

```
.
├── FIGMA/
│   └── Ride Share Mobile App Ui Kit.fig      # Master Figma design file
├── HTML/
│   ├── assets/                               # Vehicle renders, avatars, and map textures
│   ├── components/                           # Design tokens, icon definitions, and styles
│   ├── uploads/                              # App preview assets
│   ├── index.html                            # Bundled interactive prototype
│   └── support.js                            # Prototype runtime engine
├── index.html                                # Root application entrypoint
├── vercel.json                               # Vercel deployment & routing config
├── .gitignore                                # Git ignore patterns
└── README.md                                 # Project documentation
```

---

## 📄 License

This project is licensed under the MIT License.
