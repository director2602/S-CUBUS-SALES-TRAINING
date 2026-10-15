# S-CUBUS Counsellor Academy

Static training site: five animated counselling lessons with Hinglish role plays, a quiz after each lesson, parent objection bank, team scoreboard and manager scorecard.

- Hosting: Render static site (publish directory `.`)
- Scores: Supabase table `public.academy_scores` (row-level security: everyone can read; each device can only update its own row via its device token).
- Characters and voices are AI-generated.
