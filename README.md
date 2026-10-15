# S-CUBUS Counsellor Academy

Counsellor training site: five animated counselling lessons with read-aloud role plays, a quiz after each lesson, parent objection bank, team scoreboard, manager scorecard and team logins.

- Hosting: Render static site (publish directory `.`)
- Login and scores: Supabase (`academy_users`, `academy_sessions`, `academy_results`), reached only through `academy_*` RPC functions; tables are not directly readable.
- Characters and voices are AI-generated.
