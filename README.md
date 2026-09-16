# Ôn tiếng Việt — Alexandre's training system

A single standalone HTML file. Open `index.html` in any browser and it works.
Serve it over https (GitHub Pages) and it also installs to a phone home screen
and keeps your progress between sessions.

## Updating an existing install

Upload `index.html` and `sw.js` to the same repository, keeping the filenames.
The service-worker cache is `vivu-v3`, so the old cached copy is discarded on
first load. Close the installed app completely and reopen it once after
uploading. Your review history survives — it is keyed to the site origin, not
to the file.

Progress from the previous version is imported automatically the first time
this version loads: old Leitner boxes become recognition mastery, and XP and
streak carry over.

## Audio

Everything spoken uses the system text-to-speech voice. For the southern accent
install **Vi Vu** (RHVoice) and set RHVoice as the system engine:

Android → install RHVoice → choose Tiếng Việt → install Vi Vu →
Settings → Accessibility → Text-to-speech output → RHVoice.

The 🔊 panel in the app shows which voice it found.

## What is in the file

- `index.html` — the whole application: course content, learning engine, interface
- `sw.js` — offline cache
- `manifest.webmanifest`, `icon-*.png` — install metadata

Course content lives in the first two blocks of the script and carries no
application logic, so new lessons can be added without touching the engine.
