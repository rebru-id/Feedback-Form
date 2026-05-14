# Rebru.id — Visitor Feedback Form

Form digital untuk mengumpulkan data visitor, minat produk, dan feedback
di exhibition booth Rebru.id.

## Tech Stack

- Frontend : HTML5 + CSS3 + Vanilla JS (single file)
- Backend : Supabase (PostgreSQL)
- Hosting : Vercel

## Features

- Visitor data collection (name, email, phone)
- Multi-select product interest tracking
- 1–5 star rating
- Comments & suggestions
- Thank you screen + reset for next visitor
- Responsive — mobile, tablet, desktop

## Project Structure

```
Feedback-Form/
├── index.html    ← single file app
├── vercel.json   ← deployment config
├── .gitignore
├── README.md
└── sql/
    ├── 001_create_tables.sql
    ├── 002_seed_products.sql
    └── 003_rls_policies.sql
```

## Database

Supabase project: eldrclunicbxtapgbcms
Tables: visitors · products · visitor_product_interests

## Deployment

Push to main → Vercel auto-deploy → production live
