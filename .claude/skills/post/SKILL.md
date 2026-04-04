---
name: post
description: Generate a social media post for any nail salon or restaurant client
user-invocable: true
argument-hint: [client-name] [platform]
---

# Social Media Post Generator

Generate a social media post. Follow this workflow:

1. **Ask which client** (if not in $ARGUMENTS): French Nails, Belgravia, American Nail Bar, Best Nail FW, Palazzo, Bellagio, NO1 Nail Bar, or House BBQ
2. **Ask the platform** (if not in $ARGUMENTS): Facebook, Instagram, TikTok, YouTube Shorts
3. **Ask the content type**: Transformation, Promo, Seasonal, Customer Appreciation, Giveaway, General
4. **Ask for any specific details** (promo info, service to highlight, etc.)

Then generate:

- **Hook** (first line — must stop the scroll)
- **Caption** (short, punchy, human-sounding — NOT AI-corporate)
- **Hashtags** (max 5, include local SEO)
- **Call to action** (call, book, visit)
- **Suggested visual** (what image/video to pair with it)

ALWAYS follow the client's style from the Client Style Engine in CLAUDE.md. Never mix tones between clients.
