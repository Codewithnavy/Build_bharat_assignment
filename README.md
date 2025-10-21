Based on your MGNREGA project repository, here's a short and objective README:

***

# MGNREGA District Performance Dashboard

A production-ready web application enabling rural citizens to track MGNREGA district performance across Uttar Pradesh without technical expertise.

## About

Built for the Build for Bharat assignment, this platform makes government MGNREGA data accessible to low-literacy rural populations through a visual-first, mobile-optimized interface.

**Live Demo:** [build-bharat-assignment.vercel.app](https://build-bharat-assignment.vercel.app)

## Key Features

- **Auto-location Detection** - Automatically identifies user's district using geolocation
- **Visual Performance Metrics** - Color-coded indicators (green/yellow/red) instead of complex numbers
- **Hindi + English Support** - Bilingual interface with simple, jargon-free language
- **Historical Trends** - Compare current and past performance data
- **District Comparisons** - See how your district ranks against others in UP
- **Mobile-First Design** - Large touch-friendly buttons optimized for rural connectivity

## Tech Stack

- **Frontend:** React, TypeScript, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (with Redis caching)
- **Deployment:** Vercel
- **Data Source:** MGNREGA Open Government Data API

## Architecture Highlights

- Local data caching to handle government API downtime
- Scheduled daily data sync jobs
- Reverse geocoding for district detection
- Progressive Web App (PWA) with offline capability
- Optimized for low-bandwidth networks

## Project Structure

```
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/          # Main application pages
│   ├── utils/          # Helper functions
│   └── styles/         # Global styles
├── public/             # Static assets
└── README.md
```

## Design Principles

- **Low-Literacy Focus:** Icon-based navigation, minimal text
- **Accessibility:** WCAG 2.1 AA compliant
- **Performance:** Lazy loading, optimized assets
- **Scalability:** Ready for millions of concurrent users

