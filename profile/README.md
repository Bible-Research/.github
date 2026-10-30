# Bible Study Companion — a modern Bible app you can use today

**Use the app:** <https://bibleresearch.vercel.app>
**Android APK:** <https://github.com/Bible-Research/reactive-bible/releases>
**API docs:** <https://bible-research-489314.ey.r.appspot.com/api/v1/docs/>

Bible Study Companion is a free, open-source Bible reading and study
app — multiple translations, synced audio, personal notes and public
discussion — built by volunteers who wanted a study tool that fits the
way people actually study scripture.

## What we've built

### 🗒️🫂 Notes you can organize and share

Write rich-text notes anchored to any verses, organize them in a
hierarchical tag tree, and flip notes or whole tag collections public
with one switch. Public notes get shareable links that anyone can read
— no account needed — with the full chapter one tap away for context.
See a shared collection live:
<https://bibleresearch.vercel.app/notes/tag/TAGA2BE0AE324014D5>

*Still to come:* note markers inline while reading a chapter, and
management/revocation of shared links.

### 🔈🔁 Audio that follows along

Listen to chapters in several translations — including ESV, NIV and a
Latvian text-to-speech voice — with verse-by-verse highlighting as the
audio plays, automatic chapter advance, and lock-screen controls. A
loop toggle repeats the current chapter, and verse-range looping
already works through search-result and note playlists — handy for
memorization on the go.

*Still to come:* selecting verses in the reader and looping them
directly, and playback-speed controls.

### 🔍 Search

Full-text search of the active translation, results grouped by book
with one-tap navigation to each verse — and each result can be played
or added to a note straight from the list. Press `/` anywhere to jump
to search.

*Still to come:* excluding keywords, approximate and semantic search
("fire" also finding "flame"), and book/testament filters in the UI
(the API already supports them).

### 💬 Discussion around scripture

Every public note is a conversation space: nested comment threads with
rich text and image attachments, readable by anyone and moderated by
note authors. Typing `@` inserts a scripture reference (like
`@JHN.3.16`) that links the passage directly into the discussion.

*Still to come:* private groups and group-restricted threads,
verse-anchored commentary inside the reader, @user mentions, and
notifications.

### 💻📱 Cross-platform, synced

One account, every device: a responsive web app on desktop and mobile,
plus an Android app (sideload the APK from our releases page — it
self-updates and keeps audio playing with the screen off). Your notes,
tags, comments and even your reading position sync automatically —
pick up on your phone exactly where you left off on your laptop.

*Still to come:* Play Store and iOS releases, offline mode, and
social login.

### 📓 Your notes are yours

Every note is accessible as structured JSON through our open API
(docs linked above), so your study data is never locked in.

*Still to come:* one-click export for non-technical users (CSV,
Google Sheets, Word) and print-friendly views.

## Technology stack

- **Frontend:** React + TypeScript + Vite, Capacitor for Android —
  <https://github.com/Bible-Research/reactive-bible>
- **Backend:** Python Django REST API on Google Cloud —
  <https://github.com/Bible-Research/bible_research>

## Contribute — developers and non-developers alike

**Have an idea or a feature request?** You don't need to write code to
shape this app. Tell us what would help your Bible study in
[GitHub Discussions][discussions], or reach out on
[LinkedIn](https://www.linkedin.com/in/tedis-rozenfelds-197239117/) /
[tedis.rozenfelds@gmail.com](mailto:tedis.rozenfelds@gmail.com).

**Want to build it?** UX designers, front-end and back-end developers
are all needed — browse the open issues in either repo (look for
`good first issue`), or get in touch and we'll find you a starting
point.

[discussions]: https://github.com/Bible-Research/reactive-bible/discussions
