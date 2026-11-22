# Thameem & Ruqaiya · Nikkah Invitation

A static invitation site with two design versions:

- `/royal` (royal.html) — Royal maroon & gold: velvet curtain intro, gold arch, scratch-to-reveal date, countdown.
- `/navy` (navy.html) — Navy blue & gold on ivory: envelope intro, lanterns, mosque skyline, ring countdown.

Nikkah: Saturday, 9 January 2027 (30 Rajab 1448 AH), onwards 11:00 AM, Jumma Masjid & Anwarul Qudisiya Marriage Hall, S.P. Pattinam.

No build step: plain HTML. Deployed on Vercel.

## Music
Both pages play `/music.mp3` from the repo root when the guest opens the invitation, with a play/pause button in the top corner.
To add or change the song, upload an mp3 named `music.mp3` to the root of this repo (GitHub → Add file → Upload files). Vercel redeploys automatically.
If the file is missing, the pages work normally and the music button stays hidden.
