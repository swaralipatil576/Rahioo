# Rahioo
AI-powered smart trip planner web app that helps users compare routes, generate smart itineraries, optimize budgets, discover hidden gems, and plan seamless end-to-end travel experiences.


Key Features

Smart Travel Planning

Multi-modal transport comparison (flight, train, bus)

Best / Cheapest / Fastest route selection

Optimized travel suggestions


AI Itinerary Generator

Day-wise, time-based itinerary

Activities, travel steps, and food stops

Personalized recommendations


Stay Recommendations

Budget-based hotel suggestions

Ratings, distance, and pricing insights

Eco-friendly options


Food & Exploration

Local food recommendations

Popular attractions + hidden gems

Nearby places discovery


Budget Optimization

Cost breakdown (travel, stay, etc.)

Smart savings tips

Budget tracking insights


Real-Time Enhancements (Planned / Partial)

Weather integration

Live location suggestions

API-based real data integration

Tech Stack

Frontend

Next.js 14 (App Router)

Tailwind CSS

shadcn/ui

Zustand (State Management)

React Query


Backend

Node.js / Next.js API Routes

PostgreSQL (Supabase)

Prisma ORM

Redis (Caching)


APIs & Integrations

Google Places / Mapbox (Location data)

OpenWeatherMap (Weather)

Amadeus API (Transport - planned)

OpenAI / Claude (AI Itinerary generation)

 Project Structure

smart-trip-planner/
├── src/
│   ├── app/            # App Router pages
│   ├── components/     # UI components
│   ├── lib/            # Utilities & API logic
│   ├── stores/         # Zustand state
│   └── types/          # Type definitions
├── prisma/             # Database schema
├── public/             # Static assets
├── .env                # Environment variables
├── package.json
└── tailwind.config.ts

Setup Instructions

1. Clone Repository

git clone https://github.com/your-username/raahioo.git
cd raahioo

2. Install Dependencies

npm install

3. Setup Environment Variables

Create a .env file:

# Auth
NEXTAUTH_SECRET=
NEXTAUTH_URL=

# Database
DATABASE_URL=

# APIs
OPENAI_API_KEY=
OPENWEATHERMAP_API_KEY=
NEXT_PUBLIC_MAPBOX_TOKEN=

# Cache
REDIS_URL=


---

4. Run Development Server

npm run dev

Open in browser:

http://localhost:3000

 Core Screens

Home / Explore – Search + AI planning

Trip Options – Route comparison

Transit Detail – Journey breakdown

Smart Itinerary – Day-wise travel plan

 Future Enhancements

Full real-time transport APIs

Payment integration (Stripe)

AI personalization engine

Offline itinerary access

Mobile app version

 Contributors

Aditya Raj Singh

Swarali Patil

Team Members

 Vision

To build a complete digital travel concierge that replaces multiple travel apps with one intelligent, seamless platform.
