# Motimori

**A little world, entirely yours.**

Motimori is an early social-app prototype inspired by modern community and media platforms, with an original identity and a responsive mobile-first interface.

## Included in this prototype
- Email/password signup and sign-in via Supabase Auth
- Discover feed and text posts
- Basic profile editing
- Dark/light theme preference
- A first pass at private activity-history settings
- Responsive desktop and mobile navigation

## Stack
- Single-page HTML/CSS/JavaScript
- Supabase JS client (Auth + Postgres)
- Google Fonts

## Setup
1. Create a Supabase project.
2. Apply the Motimori database schema and row-level security policies for the profile, settings, posts, follows, friend requests, conversations, members, messages, likes and bookmarks tables.
3. Set the Supabase project URL and **publishable** client key in `index.html`.
4. Serve the repository root as a static site, or connect this repository to Vercel.

## Prototype limitations
Communities, direct messaging, friend/follow flows, post likes/replies, media uploads, and full privacy enforcement are not implemented end-to-end yet. The current interface includes placeholders for some of these features. Review and harden all Supabase RLS policies before real users or sensitive data are onboarded. Never put a Supabase service-role key in client code.
