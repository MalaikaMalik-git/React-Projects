# Fast React Pizza — Order pizza in seconds

A production-ready **React + Vite** SPA for browsing a pizza menu, building a cart, and placing an order with priority and geolocation. It showcases client-side routing, global state (cart), async data fetching, and polished UX.

**🔗 Live Demo:** https://fast-react-pizza-hazel-alpha.vercel.app/

## Features
- 👋 **Name capture** on landing, persisted locally (nice personalized touches throughout).
- 🍕 **Dynamic menu** (sold-out items, prices, ingredients, images).
- 🛒 **Cart** with add/remove, quantity stepper, delete & clear; sticky summary bar with total and CTA.
- 🧭 **Create order** form: phone validation, optional **priority** surcharge, and **Get position** for reverse geocoded address.
- 🔍 **Search by order ID** from the header at any time.
- 🚦 **Order status page** with badges (e.g., “PRIORITY”, “PREPARING”), ETA and price breakdown.
- 💾 Cart + user name persist across refreshes.
- 📱 Fully responsive UI with accessible controls.
- ⚠️ Thoughtful loading & error states.

---

## Tech Stack
- **React 18** + **Vite**
- **React Router** (nested routes, loaders/actions style)
- **Redux Toolkit** (cart state) + localStorage persistence
- Modern **CSS** for layout and components

---

## Routes

