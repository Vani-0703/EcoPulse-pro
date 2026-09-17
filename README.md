# EcoPulse Pro

A Vercel-ready Next.js sustainability command center. It runs with demo data and browser localStorage, so there is **no Supabase, database, backend, API key, or environment variable required**.

## Vercel deployment

1. Open Vercel and choose **Add New → Project**.
2. Import `Vani-0703/EcoPulse-pro` from GitHub.
3. Framework preset: **Next.js** (auto-detected).
4. Root directory: `.`
5. Build command: `next build` (or leave the default).
6. Output directory: leave blank/default. **Do not set it to `public`.**
7. Environment variables: none required.
8. Click **Deploy**.

The app includes Overview, Impact, Goals and Activity views. Goal changes and activity events persist in the browser with localStorage. This architecture avoids the previous `Failed to fetch`/Supabase dependency problem and is suitable for a static-first Vercel deployment.
