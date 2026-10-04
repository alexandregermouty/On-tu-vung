# Ôn tiếng Việt

Alexandre's personal Vietnamese-learning PWA, built around the material in **ALEXANDRE.docx** with a Southern Vietnamese focus.

**Learn to belong.**

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
