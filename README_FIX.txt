PMB GIRLS' HIGH — LIVE FIX

The error:
Could not find the table 'public.ghs_players' in the schema cache

means the live website is connected to a Supabase project where the GHS tables
are not currently visible/created.

IMPORTANT:
Run 01_REPAIR_DATABASE.sql in the Supabase project with this Project URL:
https://awrokogqrkqdadnxsauq.supabase.co

Then upload these website files to GitHub:
- index.html
- styles.css
- app.js
- config.js
- ghs-logo.png

The supplied official Girls' High badge is now used in the header instead of
the text GHS box.

After GitHub commits, Cloudflare Pages should redeploy automatically.
Hard refresh the live page with Ctrl+F5.
