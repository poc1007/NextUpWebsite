# NextUp Website

This public repository hosts only NextUp's Privacy Policy, Support page and private support-inbox interface. It intentionally contains no Swift source code, Supabase migrations, secrets, tokens, user data or private project history.

The Supabase publishable key in `assets/config.js` is designed for browser use. All support messages are written through a protected Edge Function, and the inbox is accessible only to the designated NextUp support administrator through Supabase authentication and Row Level Security.
