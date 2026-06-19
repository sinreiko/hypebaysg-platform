# Hypebaysg — Creative Art & Event Decoration Studio Website

> A modern, SEO-optimized Next.js website for Singapore's premier creative art and event decoration studio. Features real-time booking, admin dashboard, product management, and comprehensive SEO implementation.


<img width="350" alt="Screenshot 2026-06-19 at 8 29 21 PM" src="https://github.com/user-attachments/assets/88a23bda-7773-49fc-8092-8cb05ee9f569" />
<img width="350" alt="Screenshot 2026-06-19 at 8 30 33 PM" src="https://github.com/user-attachments/assets/cada4002-dff2-40b3-afd6-eed479c5282b" />
<img width="350" alt="Screenshot 2026-06-19 at 8 30 04 PM" src="https://github.com/user-attachments/assets/a4b32bbf-f7a5-47cb-bc46-19f8803cfc0d" />
<img width="350" alt="Screenshot 2026-06-19 at 8 31 21 PM" src="https://github.com/user-attachments/assets/d7ac1247-bc7f-4674-b8a9-9a7b49ce7ad5" />

Live at https://hypebaysg.com

## 🎨 Project Overview

Hypebaysg is a full-stack website showcasing creative services including:
- 🎈 Balloon decoration & sculpting
- 🎭 Face painting & character costumes
- 🖼️ Custom murals & Bearbrick art
- 📸 Event photography & video
- 🎪 Magic shows & entertainment
- 🛠️ Web design & workshops
- 🎪 Bouncy castle rentals
- 👜 Custom leather goods

The website combines **beautiful design**, **real-time functionality**, and **enterprise-grade SEO** to drive organic traffic and bookings.

## ✨ Key Features

### 🌐 Frontend
- **Responsive Design** — Mobile-first Tailwind CSS with fluid typography
- **Dynamic Pages** — Service pages, portfolio gallery, blog posts, product shop
- **Real-time Booking** — Google Calendar integration for live availability
- **Portfolio Gallery** — Filterable gallery with category tags
- **Blog System** — Markdown-based blog with schema markup

### 🔧 Admin Dashboard
- **Protected Routes** — Session-based admin key authentication
- **Product Management** — CRUD operations for shop products
- **Pricing Editor** — Real-time pricing updates stored in Supabase
- **Blog Editor** — Create, edit, delete blog posts with cover images

### 📊 Database & Storage
- **Supabase PostgreSQL** — Real-time data with automatic sync
- **File Storage** — Blog images and portfolio assets
- **JSON Fallback** — Graceful degradation when database unavailable
- **Environment-based Config** — Secure credential management

### 🔍 SEO & Performance
- **Dynamic Sitemap** — Auto-generates from database content
- **Schema Markup** — Organization, Service, FAQ, Breadcrumb structured data
- **Meta Tags** — OG tags, Twitter cards, canonical URLs
- **Robots.txt** — Search engine crawling configuration
- **Performance Optimized** — Next.js image optimization, lazy loading

### 📱 Integrations
- **Google Calendar API** — Live booking availability
- **Google Places Reviews** — Social proof on homepage
- **Web3Forms** — Contact form email delivery
- **WhatsApp** — Floating action button for quick messaging

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React 18, Next.js 14 (Pages Router) |
| **Styling** | Tailwind CSS 3, custom CSS utilities |
| **Database** | Supabase (PostgreSQL) |
| **Backend** | Next.js API Routes |
| **Authentication** | Session storage (client-side admin key) |
| **Deployment** | Vercel (recommended) |

## 🔐 Admin Dashboard

### Shop Management
- **Features:** CRUD products, manage images, preview before publish
- **Auth:** Session-based with admin key

### Pricing Management
- **Features:** Update service prices in real-time
- **Storage:** Synced with Supabase automatically

### Blog Editor
- **Features:** Create posts, upload cover images, manage content
- **Format:** Markdown with rich text support

## 🔍 SEO Implementation

The website includes comprehensive SEO optimization:

### On-Page SEO
- Optimized meta titles & descriptions (150-160 characters)
- Open Graph tags for social sharing
- Canonical URLs to prevent duplicate content
- H1 & H2 tags with keyword variations

### Technical SEO
- **Dynamic Sitemap** — Auto-generates from blog posts & products
- **Robots.txt** — Guides search engine crawling
- **Schema Markup** — Organization, Service, FAQ, Breadcrumb structured data
- **Performance** — Optimized images, lazy loading, Core Web Vitals

### Content Strategy
- Internal linking between services, blog, and booking
- Blog posts targeting high-intent keywords
- Service-specific content optimization
- Regular content updates for freshness

## 📊 Database Schema

### Key Supabase Tables
- `blog_posts` — Blog content with metadata
- `shop_products` — Product catalog with pricing
- `site_settings` — Global settings (pricing, hours, etc)
- `bookings` — Customer bookings (optional)

### Other Platforms
- **Netlify** — Support for Next.js with serverless functions
- **AWS Amplify** — Full AWS integration
- **Self-hosted** — Use any Node.js hosting provider

## 📚 API Endpoints

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/shop` | GET | Fetch products |
| `/api/shop` | POST | Save products (admin only) |
| `/api/blog` | GET | Fetch blog posts |
| `/api/blog` | POST | Create blog post (admin) |
| `/api/pricing` | GET | Fetch pricing |
| `/api/pricing` | POST | Update pricing (admin) |
| `/api/availability` | GET | Google Calendar availability |
| `/api/reviews` | GET | Google Places reviews |
| `/sitemap.xml` | GET | Dynamic XML sitemap |

## 🎯 Key Features Showcase

### 1. Real-time Booking Calendar
```jsx
// Integrates with Google Calendar
<AvailabilityCalendar />
```
- Live availability from Google Calendar
- Block off busy times automatically
- Mobile-responsive date picker

### 2. Portfolio Gallery
- Filterable by service category
- Lazy-loaded images
- Responsive grid layout
- Modal lightbox preview

### 3. Product Shop
- Dynamic product pages
- Customization options support
- Real-time pricing from database
- Image carousel

### 4. Blog System
- Full CRUD operations via admin dashboard
- Markdown content support
- Cover image upload
- Schema markup for SEO
- Related posts suggestions

## 🔄 Workflow

1. **Content Updates** → Admin dashboard edits
2. **Database Sync** → Supabase stores changes
3. **Auto Regeneration** → Pages rebuild with new content
4. **SEO Updates** → Meta tags & schema update automatically
5. **Sitemap Refresh** → `/sitemap.xml` generates fresh URLs
## 📄 License

This project is proprietary. All rights reserved.

## 📞 Support & Contact

- **Website:** https://hypebaysg.com
- **Email:** reikolee00@gmail.com
- **WhatsApp:** Contact via website

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Database powered by [Supabase](https://supabase.com/)
- Deployed on [Vercel](https://vercel.com/)

---

**Last Updated:** June 2026
