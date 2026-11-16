# Outlet performance dashboard

Single-page dashboard (`index.html`) showing sales vs target per outlet and week.
Data and sign-in come from Supabase (project "outlet performance").

## Deploy on Vercel

1. In Vercel choose **Add New > Project** and import this GitHub repository.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Click **Deploy**. No environment variables are needed.

## Notes

- The Supabase URL and publishable key are in `index.html`. The publishable key is meant to be public;
  access is controlled by Row Level Security in Supabase.
- Users sign in with a username and password (stored in Supabase Auth). Admins can add users from the
  **Users** button.
- Change the initial sample passwords and turn off public sign-ups in Supabase before real use.
