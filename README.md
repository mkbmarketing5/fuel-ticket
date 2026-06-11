# FuelTicket - Digital Fuel Charge Tickets

Production-ready SaaS for small gas stations and fleets.

**Status**: Public QR ticket submission + station dashboard is functional.

## Quick Start

1. Supabase Setup:
   - Run `supabase/schema.sql`
   - Create private `receipts` bucket
   - Run `supabase/seed.sql`
2. `cp .env.local.example .env.local` (fill Supabase keys)
3. `npm install && npm run dev`

Test: `/fuel/MST001` (PIN 1234) → Dashboard `/dashboard`