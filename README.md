# tourist_family

## 🏛️ Namma TN Guide – Tamil Nadu Tourist Guide Generator

A personalized Tamil Nadu travel guide generator powered by **CrewAI Cloud Automation** and a verified **Supabase Database**.

### Features

- 🧭 **AI Travel Planner**: Dynamic multi-day itinerary generation customized by district, dates, hours/day, travel party size, budget tier, and interests.
- 🏛️ **Verified Attractions**: Live curated directory of regional landmarks with photos, entry fees, recommended visit durations, operating hours, and Google Maps integration.
- 👤 **Cultural Guides**: Direct directory of verified local heritage and culture guides with one-click WhatsApp contact.
- 💰 **Budget Estimator**: Automatic tiered breakdown of accommodation, food, activities, and transport expenses.
- 📋 **Export Options**: Copy Markdown, Download `.md` itinerary, or Print/Save to PDF.

### Tech Stack

- **Frontend**: Vanilla HTML5, CSS3 (Modern Responsive Grid, Glassmorphism, Theme Design System), JavaScript (ES6+)
- **Markdown & Security**: Marked.js + DOMPurify
- **Database**: Supabase (PostgREST API)
- **AI Automation**: CrewAI Cloud

### Setup

1. Copy `.env.example` to `.env`:
   ```bash
   cp .env.example .env
   ```
2. Configure your Supabase and CrewAI credentials in `.env`.
3. Open `index.html` in your browser or run a local static server:
   ```bash
   npx serve .
   ```
