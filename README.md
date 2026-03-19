# La lettre de l'iA

                ┌────────────────────┐
                │    Next.js App     │
                │ (Frontend + API)   │
                └────────┬───────────┘
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   PostgreSQL       Redis Queue     External APIs
   (Supabase)        (Jobs)        (AI, Telegram…)
        │                │
        ▼                ▼
   Data Storage      Workers (Crawler + AI)
