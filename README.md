# Konkou Bote 2026 — Supabase V1

1. Kreye yon project sou Supabase.
2. SQL Editor → New query → kouri `supabase/schema.sql`.
3. Authentication → Providers → aktive Email/Password ak Anonymous.
4. Authentication → Users → kreye Admin email/password.
5. Nan `supabase/schema.sql`, ranplase `admin@YOUR-DOMAIN.com` ak menm email Admin lan, epi re-kouri policies yo si sa nesesè.
6. Supabase → Settings → API → pran Project URL + anon public key.
7. Mete yo nan `supabase-config.js`.
8. Mete fichye prensipal yo sou GitHub Pages.

Pa janm mete `service_role` key oswa modpas Admin nan GitHub.

Backend sa a itilize PostgreSQL + RLS + RPC `cast_vote`. Vote a limite pa `(match_id, voter_id)`, epi RPC la verifye match la se pou dat jodi a nan timezone Haiti.

Anvan lansman final, teste tout 72 match yo, faz final yo, RLS, ak anti-abuse. Anonymous Auth pa garanti yon moun fizik pa ka kreye yon lòt identity; Phone OTP/App protection ka ajoute pita.
