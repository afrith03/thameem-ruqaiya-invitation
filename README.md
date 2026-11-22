# Thameem & Ruqaiya · Nikkah Invitation

A static invitation site with two design versions:

- `/royal` (royal.html) — Royal maroon & gold: velvet curtain intro, gold arch, scratch-to-reveal date, countdown.
- `/navy` (navy.html) — Navy blue & gold on ivory: envelope intro, lanterns, mosque skyline, ring countdown.

Nikkah: Saturday, 9 January 2027 (30 Rajab 1448 AH), onwards 11:00 AM, Jumma Masjid & Anwarul Qudisiya Marriage Hall, S.P. Pattinam.

No build step: plain HTML. Deployed on Vercel.

## Adding music later
Each page has an `AUDIO SLOT` comment near the top of `<body>`. Add `<audio id="bgm" src="/music.mp3" loop preload="auto"></audio>` there and put `music.mp3` in the repo root; it starts playing when the guest opens the invitation.
