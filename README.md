# Underwater World Exploration — V5

## Main change
Saturday Ocean Club is now a dedicated child-facing page: `ocean-club.html`.

### V5 design
- Dedicated `🐠 Ocean Club` item in the top navigation
- Strong homepage banner so children/parents can see the club immediately
- Child-friendly language for ages 7–11
- More visual emoji, but used as navigation/learning cues rather than decoration everywhere
- Games, mini challenges, sea-animal prompts and hands-on activity language
- Public location: condo function room near Lakeside MRT, Singapore
- Exact condo details remain private until a parent has registered
- `activities.html` and `register.html` removed to simplify the flow

## Google Form
The JOIN button currently points to the Google Forms homepage as a placeholder.
Create the actual Google Form, copy its public response URL, then replace:
`https://forms.google.com/`
inside `ocean-club.html` with the real form URL.

Suggested Google Form fields:
1. Parent / Guardian Name
2. Child's First Name
3. Child's Age
4. Parent's WhatsApp / Mobile
5. Which Saturday session would you like to join?
6. Anything we should know?

## Deployment
Replace repository files with the V5 files, commit to `main`, and push origin.
Cloudflare Pages should redeploy automatically.
