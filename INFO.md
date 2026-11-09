# INFO — IELTS Band 6 · 词汇通

Technical and content notes for teachers and for anyone who maintains this app.

## 1. Content at a glance

| Item | Count |
|---|---:|
| Units | 21 |
| Words and phrases | 1,253 |
| Unit Review texts | 63 (three per unit) |
| Review sentences | 649 |
| Audio files | 4,409 (words 1,253 · source sentences 1,253 · example sentences 1,253 · review sentences 649 · one test clip) |

Each word entry contains: `word`, `pron` (IPA), `pos`, `def_en`, `def_zh`, `quote_en` / `quote_zh` (source sentence), `ex_en` / `ex_zh` (example sentence), `chapter`, `id` and `unit`.

## 2. Where the words come from

- Units 1–20 follow the unit list of *IELTS Vocabulary Up to Band 6.0* (PDF wordlist, transcribed by reading the page images because the OCR text was unreliable).
- The text version of the list was compared against it, and 13 extra words were added from it (for example *wildlife*, *lift*, *surf*, *unforeseen*, *disjointed*).
- **Unit 21 · Reference & Writing** collects the reference vocabulary that the list names for its "Units 21–25" (dictionary and language terms, chart and trend words, letter-writing terms). The list gives no full wordlist for those units.
- A word appears in only one unit. Where a word is listed under several units, it is kept in the first one.

## 3. How the sentences were made

- Every source sentence and example sentence contains the **exact headword**, so highlighting and gap-fill work correctly.
- Every Unit Review set uses **every word of its unit** at least once. This was checked by a script before release; some sentences are therefore slightly formal or packed.
- The Chinese is written to explain the English naturally rather than word for word.

## 4. Audio

- Voices: `en-GB-SoniaNeural` (words, sentences, narration), `en-GB-RyanNeural` (the second speaker in dialogues).
- Words are read at -10% speed and sentences at -5%.
- Files are named by id: `w0001.mp3` (word), `w0001_q.mp3` (source sentence), `w0001_e.mp3` (example), `r_unit1_p1_01.mp3` (review sentence).
- The app plays the mp3 if it exists and otherwise uses the device voice.

## 5. Progress and privacy

- Progress (flashcard boxes, settings) is stored in the browser's `localStorage` on the learner's own device.
- Nothing is sent anywhere. Clearing browser data, or changing the repository name or web address, resets progress.

## 6. Known limits

- The Chinese, IPA and example sentences were written by an AI assistant and have not had a full teacher review.
- The Unit 21 words are reference terms, not an official IELTS wordlist.
- No synonyms/antonyms data is included yet.
- There is no export/backup button for progress yet.
- First sound on some phones needs one tap.

## 7. Ideas for later

- Progress export and import (JSON).
- A short quiz at the end of each unit review.
- A shadowing mode (listen, pause, repeat).
- Synonyms and antonyms for each word.

## 8. Version

Version 1.0 · November 2026 · © Daniel Wang · Words That Think
