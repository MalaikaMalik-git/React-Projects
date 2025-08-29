# WorldWise — Track Your Footsteps Around the World

A clean **React** single-page app to log cities you’ve visited on an interactive map, add notes/dates, and browse your trips by city or country.  
Built as a fundamentals project (routing, global state, maps, forms, async), and deployed on **Netlify**.

**🔗 Live Demo:** https://worldwise790.netlify.app/

## Features
- 🗺️ **Interactive map** (Leaflet) to select locations and visualize added cities  
- ➕ **Add city** with name, country code, date visited, and notes  
- 📚 **Cities & Countries views** to browse your list by city or grouped by country  
- 🧭 **Use my position** – optional geolocation to move the map to your current location  
- 🔐 **Simple demo auth** (fake auth context) with protected app routes  
- 🚦 Proper loading/empty/error states and optimistic UI  
- 🎨 Minimal, responsive styling

---

## Tech Stack
- **React** + **React Router** (SPA routing & protected routes)
- **Leaflet** + **react-leaflet** (maps)
- **Context / custom hooks** for global state (auth, geolocation, URL position)
- **JavaScript**, **CSS**
- **Netlify** for hosting (SPA redirect)
