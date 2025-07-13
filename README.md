# CraftRadar – Real-Time Artisan Locator & Local Skills Network

**CraftRadar** is a mobile-first, web-based platform that helps people discover trusted, nearby artisans and skilled craftworkers in real time. From plumbers and electricians to tailors and furniture makers, CraftRadar connects communities with local talent through a simple, map-powered interface.

> “CraftRadar — Find Local Skilled Help, Fast.”

---

## The Problem

In many communities—especially across emerging markets—skilled artisans and informal workers are under-discovered, under-booked, and underpaid due to a lack of digital exposure. Meanwhile, people needing urgent repairs or services often don’t know where to find **trusted**, **available** professionals nearby.

Problems we solve:
- Inaccessibility of verified artisans when you need them
- Lack of location intelligence in traditional directories
- No transparent way to compare service quality (ratings)
- Skilled workers without digital platforms to grow their craft

---

## The Solution

**CraftRadar** helps users:
- Discover **available, verified artisans** nearby on a live map
- **Request a job** directly through the platform
- **Rate artisans** after each job to build trust
- See **ratings, skills, and distance** before booking

**Artisans** can:
- Register with their skills and profile
- Get **admin-verified** to go live
- Share their **live location** when online
- View incoming job requests and manage availability

**Admins** can:
- Review artisan applications
- Approve or reject signups
- Moderate service quality and visibility

---

## 🌐 Live Demo

> Hosted on Netlify
> https://craftradar.netlify.app/

---

## Features

| Feature | Description |
|--------|-------------|
| 🗺️ **Live Map View** | See available artisans nearby in real time using Google Maps |
| 📋 **Verified Profiles** | Artisans are admin-approved before going public |
| 🧑‍🎨 **Skill Directory + Custom Input** | Choose from predefined craft skills or enter your own (max 15 characters) |
| 📥 **On-Demand Job Requests** | Request an artisan and view ETA (simulated) |
| ⭐️ **Rating System** | Submit a 1–5 star rating and optional comment post-job |
| 🧑‍💼 **Admin Panel** | View and manage artisan applications and status |
| 📱 **Mobile-First Design** | Optimized for mobile with clean modals and map experience |

---

## Tech Stack

| Tech | Purpose |
|------|---------|
| **Google Maps Platform** | Maps SDK, Geolocation API, Directions API |
| **Bolt.new + React + Tailwind CSS** | Mobile-first frontend UI |
| **Supabase** | Backend DB, auth, and real-time data |
| **Vite** | Lightweight build setup |
| **ShadCN UI** | Beautiful reusable components |

---

## Artisan Skills Supported

Plumber, Electrician, Carpenter, Tailor, Painter, Mason, Roofer, Upholsterer, Mechanic, AC Technician, Hairdresser, Auto Electrician, Furniture Maker, Cleaner, Welder
Custom	Any skill entered (max 15 characters)

---

## Potential Use Cases
-Homeowners needing urgent repairs
-Remote areas where skilled labor is present but unsearchable
-Tourists or visitors needing language-independent service access
-Governments and NGOs promoting skilled job access in underserved communities

---

## Social Impact
CraftRadar supports:
-Digital empowerment of informal workers
-Job creation and local economic visibility
-Trust and transparency in community services
-Skill discovery in rural and underserved areas
-Promotes trust and safety through vetting and proximity-based discovery
-Bridges digital inequality by giving artisans a simple mobile dashboard
-Reduces downtime and household disruptions through on-demand service

---

## Future Enhancement	

✅ MVP	Map view, registration, admin approval, job request, ratings
🔜 Next	Real-time location sync, chat, Stripe wallet/payments
🔜 Expansion: Multilingual support, government/NGO collaboration
🔜 App Store	Deploy as a native PWA or React Native app

---

## Security & Privacy
-Location is shared only when artisan goes online
-Admins validate all artisan profiles before public visibility
-No PII is exposed publicly without approval

---

## Environment Variables

Create a `.env` file with the following:

```env
VITE_GOOGLE_MAPS_API_KEY=your_maps_api_key
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_public_key

---

📄 License
MIT License
CraftRadar is an original product and brand concept by Adewale Ogabi.
Forks and use permitted with attribution. Branding may not be reused commercially.
