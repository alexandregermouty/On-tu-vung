# Ôn tiếng Việt

Alexandre's personal Vietnamese-learning PWA, built around the material in **ALEXANDRE.docx** with a Southern Vietnamese focus.

**Learn to belong.**

## What is new in v15 — calmer, aligned layout

- **Fits the phone exactly.** The bottom bar was 24 px wider than the screen, which made Android zoom the whole page out and pushed everything off the edges. It now sits 12 px in from each side, and every screen has a single 20 px margin on the left and right.
- **One header row.** The page title (Hôm nay, Bài học, Khóa học…) sits beside the logo with a short subtitle, instead of a second large heading underneath.
- **New icons.** All hand-drawn icons are replaced with [Phosphor Icons](https://phosphoricons.com) (MIT licence), light weight for the interface and duotone for lesson tracks.
- **Decoration removed.** The cement-tile pattern, tone-mark emblems, dividers, background watermarks and falling confetti marks are gone. Cards are plain solid surfaces.
- **Today** is one main action card, a short "Tiếp tục" list, four practice tiles and three numbers.
- **Lessons** is a single vertical path with numbered steps, all on the same left edge.
- **Results** use a simple progress ring.

Icons: Phosphor Icons © Phosphor Icons, MIT licence.

## What is new in v14 — visual redesign

### Foundations
- The two typefaces are now actually loaded: Be Vietnam Pro (made for Vietnamese diacritics) for every Vietnamese word, Newsreader for titles and English glosses.
- Colour has meaning. The accent (gold in dark mode, lacquer red in light mode) is reserved for the one main action and for your progress. Jade means correct or done, coral means wrong, blue means listening.
- Grammar roles keep fixed colours everywhere — who, verb, question word, time word and place — in patterns, in fill-the-gap blanks, in answers and in the word list.
- Four text sizes and three spacing steps; no small capital labels; fewer Vietnamese/English label pairs.
- Every emoji is replaced by one drawn line-icon set (about 120 icons) that looks the same on every device; the navigation uses it too.
- A light "rice paper" theme with ink-dark text and lacquer-red accents. It follows the phone, or can be fixed in Settings.

### Identity
- The six tone marks are the visual signature: the loading animation, the dividers between tracks, the results gauge, and each track emblem, where the track's illustration is the "letter" and its tone mark sits above it like a diacritic.
- Cards read as layered lacquer: darker body, a fine edge and a soft inner glow.
- Each track has a line illustration (a café stool and glass for situations, a ceremony tray for the wedding, river and mountain for work, a conical hat for Southern speech, a scooter for directions).
- A very faint Saigon cement-tile pattern sits behind the header and the Today card.

### Screens
- Today is one clear next-step card with an illustration, three round buttons (review, next lesson, lessons due), a thin line of numbers and wrapping shortcuts; the old overflow is gone.
- The Lessons path has track emblems, a gentle colour scene per track, a lacquer-gold seal on finished lessons and a slowly pulsing ring on lessons due. Studio's games and visual maps now live at the bottom of Lessons.
- A lesson's visuals are swiped one at a time like stories, each with a single title line.
- Exercises are full screen (no header), with larger answer tiles, a colour wash on correct and wrong, and feedback in a bottom sheet showing the sentence with each word's tone mark beneath it; "Vì sao?" is one line that expands.
- Results show a filling tone-mark gauge, the fourteen steps as a staircase with climbed steps lit, and stars that land.
- Flashcards use the full height, show the word's tone marks large, and sort by swipe: left for "again", right for "I know it".
- Course and Classes use the same cards as Lessons: topics as tiles, classes as date tiles with topic badges.
- Progress is drawn: a word garden, a chart of the six tones, a twenty-week calendar heatmap and one ring per track; the detailed numbers sit in a fold-out.
- Review, Listen, Speak, Weak spots, Words and Content share the new style and lose their subtitles.

### Feel
- One motion rule: quick 200 ms ease-in, sideways slides inside a lesson, fades between sections, bounce only for stars and celebrations.
- Light vibration on answers and tile taps, and a synthesized đàn bầu-like pluck for correct and a muted wood block for wrong — both switchable in Settings.
- Full-screen celebrations only for big moments: finishing a track, a 7-, 14-, 30-, 60-, 100- or 365-day streak, and a perfect challenge run.

## What is new in v13

### Learning design
- Finished lessons come back for review on a growing interval (2, 5, 12 days and so on). Due lessons show a ↺ badge, their stars fade, and Today and the Lessons tab offer a mixed "Ôn bài học" review.
- Lesson answers now also count in the main review engine whenever the word exists in the course, so they feed Review, Weak spots and Progress.
- A wrong answer explains itself: a specific reason for natural-versus-unnatural sentences, the meaning of the word you chose against the right one, and the course's own contrast line for the concept.
- Every three or four lessons, a mixed review lesson (Ôn tập) interleaves them. The last review in each track adds a short reading with comprehension questions.
- Lessons not yet done offer a three-question quick check; a perfect score marks the lesson as known and schedules it for review.

### Visuals
- Statement-to-question patterns animate: the answer is struck out and the question word drops into its slot (↻ replays it).
- Flashcards show the tone shapes of each word and an icon for concrete words; tiles and opposite pairs use icons too.
- The Lessons tab has a path view (default) alongside the grid.

### New exercise types
The ladder now has 14 steps in four stages (notice, understand, write, use): recognise, listen, match, recall, choose, fill in, fix the mistake, build, converse and read, type, dictation, transform or write the question, translate, and speak (speech recognition where the browser supports it). A six-second-per-question speed round follows any lesson.

### Content
- Three new tracks: Everyday situations (café, directions, rides, shopping, weather, feelings), Family and wedding (family members, meeting her family, the wedding, toasts) and Talking about work (your job, meetings, climate and water).
- Five new grammar lessons: đang … thì, cũng · vẫn · còn, để, cho, được.
- Conversation turns, question-writing and sentence transformations added to the existing lessons; 13 short readings.
- A "Lớp học" track drafts a lesson from each dated class (vocabulary plus its course examples), including classes added later through Content.

### Audio
- On any flashcard, "Ghi âm" records a native speaker saying the word. Recordings are stored on this device and replace the synthetic voice everywhere in the app.

## What is new in v12

- New **Lessons** tab (Bài học): 60 short lessons on one theme each, in 10 tracks — questions, time and frequency, past/now/future, pronouns, sentence building, verbs, adjectives, particles, numbers and Southern speech. The dated weekly classes are unchanged.
- Each lesson opens with visuals instead of paragraphs: frequency scales, a question mind map, aspect timelines, comparison columns, colour-coded sentence patterns, clocks, a day bar, a position diagram and North → South word maps. Every Vietnamese word can be tapped to hear it.
- Flip flashcards follow, then a nine-step exercise ladder that gets harder at each step: recognise → listen → match → recall → choose the natural sentence → fill the gap → build the sentence → type → translate. Mistakes come back in a short repair round at the end.
- Lessons earn up to three stars. Completed lessons unlock a Challenge mode that skips the easy steps.
- Today, Course and Classes screens carry less text; Today links straight to the next lesson.
- Lesson sentences come from the course material already in the app.

## What is new in v11

- **Exercises only** opens practice directly. Returning classes offer Challenge mode by default; reviewing the cards remains available.
- 119 original beginner-to-intermediate extension examples and 31 focused tasks add new everyday contexts: work, cafés, shopping, family, schedules and routines.
- Practice now mixes typed gaps, sentence building, question transformations, error correction, short readings, conversation replies, listening when available, and personal writing.
- Each linked structure receives practice. Example history prioritizes unseen contexts and changes formats when material returns. Smaller pools still repeat for consolidation.
- Whole-sentence alternatives can be compared with a model and self-assessed for partial credit; fixed-gap answers remain checked.
- The October 1 class and its new vocabulary are included from the updated ALEXANDRE document. Future-dated homework is not presented as a completed class.
- Existing learning progress is retained. Vocabulary-only imported lessons also support direct practice.

### Language references

The new extension sentences and reading passages are original teaching examples, not quotations or transcribed conversations. Their patterns were checked against:
- [HowToVietnamese — beginner grammar](https://howtovietnamese.com/vietnamese-basic-grammar-beginners/): pronouns, word order and questions.
- [HowToVietnamese — everyday conversation](https://howtovietnamese.com/vietnamese-easy-conversation-phrases/): Southern-oriented everyday situations and natural question/answer patterns.
- [Michigan State University, Basic Vietnamese — chapter 6 grammar](https://openbooks.lib.msu.edu/vietnamese/chapter/u6-grammar/): chưa, đã and rồi.

Validation: script syntax; course coverage and plan integrity across 24 lessons; accepted answer variants; typed submission and alternative-wording paths; returning-class direct entry; vocabulary-only imports; audio-enabled plans.

## What is new in v10

- Class review, concept help and correction cards now lead with one short rule, a visual pattern or comparison, and one spoken example.
- Longer notes and additional examples remain available in an expandable section.
- Vocabulary review cards are simpler, and the Pedagogical Studio text is shorter.
- The question visual map is available from the related concept cards.

## What is new in v9

- Weekly classes now open with a structured review of every linked concept and vocabulary item before practice.
- Class practice moves from meaning recognition to Vietnamese recall, rule checks, sentence completion and building, listening (when a voice is available), and written production. Missed items return at the end of the class.
- The 27 September class is included, with fuller explanations for open questions, `chưa` questions, ownership, duration and frequency, plus vocabulary from the class notes.
- Question and context-adjective explanations now give usable patterns, examples and contrasts.

## What is in v8

- New circular tone-mark logo throughout the app, browser favicons and installable phone icons.
- Mobile-first Today and study views.
- Independent spaced-repetition schedules for recognition, recall, listening, context and production.
- Tone-aware Vietnamese typing feedback.
- Content Manager for adding future weekly classes without rewriting the application or losing progress.
- **Pedagogical Studio** with visual maps for tones, syllable construction, pronouns, sentence structure, open questions and aspect.
- New active games: Smart Flashcards, Pronoun Compass, Classifier Sort, Particle Mood, Question Map, Context Words, Sound Detective and Time & Money.
- Expanded course material for peer pronouns, vowel combinations, consonant groups, location phrases, conversational particles, prices/payment, ordinal numbers, clock-time vs duration and additional uses of `đã`.
- Extra course sentences, dialogues and situation-based speaking prompts.

## GitHub Pages deployment

This is a static application; there is no build step.

1. Put every file from this folder at the root of `alexandregermouty/On-tu-vung`.
2. In GitHub open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Once GitHub Pages publishes, open `https://alexandregermouty.github.io/On-tu-vung/`.

All application URLs are relative, so the app works under the `/On-tu-vung/` project path.

## Phone installation

### iPhone / iPad

Open the GitHub Pages site in Safari → **Share** → **Add to Home Screen**. `apple-touch-icon.png` is used as the home-screen icon.

### Android

Open the site in Chrome → browser menu → **Install app** or **Add to Home screen**. Android uses the PWA manifest, including a maskable icon for adaptive icon shapes.

## Branding files

- `logo.png` — transparent circular mark used inside the app.
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `favicon-48.png` — browser icons.
- `apple-touch-icon.png` — iOS home-screen icon.
- `icon-192.png`, `icon-512.png` — standard PWA icons.
- `icon-maskable-512.png` — Android adaptive icon with safe padding.
- `icon-1024.png` — high-resolution source app icon.

The installed-app icons intentionally use the app's lacquer-green background rather than transparency because iOS and Android app-icon masks are more predictable on a solid field.

## Updating course material

Use **More → Content** in the app. A weekly class can be entered manually, pasted in bulk, or imported as CSV/JSON. Course content and learner history use separate storage, so updating a translation or adding a class does not reset prior mastery.

## Updating the app

`sw.js` uses a versioned cache. Bump the `CACHE` string on future releases so installed PWAs fetch fresh assets.

Learner progress stays in browser local storage / IndexedDB and is not stored in this repository.
