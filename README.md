# 📼 daily cassette

a little thing i made for someone special.

every day i'd open this file, add a song that reminded me of her that day,
and write a small note — a lyric, a feeling, whatever felt right.
she'd open the page and find a vintage cassette showing that day's song,
with the reels spinning when it played.

past songs collect quietly at the bottom, so she could scroll back
through every day i thought of her.

no framework, no backend. just a single html file i'd update and redeploy each morning.
the whole point was the ritual of it — picking a song, writing two lines, and knowing
she'd see it.

---

built with vanilla html/css/js + the caveat font from google fonts.
songs are hardcoded in a `SONGS` array with a date, title, artist, mp3 path, and a note.
the page automatically shows today's entry and archives the rest.
