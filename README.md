# IELTS Band 6 · 词汇通

**A bilingual (English / 中文) vocabulary app for IELTS learners up to Band 6.0 — with sound.**
**为备考雅思（6分及以下）的中文学习者设计的双语词汇应用，配有真人级语音。**

🔗 **Open the app:** https://dwang055.github.io/IELTS_Band6_Vocabulary/

Part of the **Words That Think · 品词坊 · 以词启思** family of offline learning apps.

---

## What it does

- **1,253 words and phrases** in **21 topic units**, each with IPA, an English definition, a Chinese definition, a source sentence and an example sentence (both with Chinese translations).
- **Sound for everything:** every word and every sentence has a 🔊 button, read by Microsoft Edge neural voices (Sonia and Ryan, UK English).
- **Learn:** one card per word, with the target word highlighted in each sentence.
- **Flashcards:** spaced repetition (five boxes) for one unit or all units.
- **Listen & Type:** hear a word, read the Chinese hint, and type it letter by letter.
- **Unit Review:** three short texts per unit in different styles (essay, news report, interview, dialogue and more) that use **every word of the unit**. Play them sentence by sentence or all at once, turn Chinese on or off, hide the text for listening practice, or hide the target words as a gap-fill.
- **Works offline** once loaded. No account, no tracking. Progress is saved in your own browser.
- **Light and dark mode**, and it works on phones and tablets.

## How to use it

1. Open the link above (Microsoft Edge or Chrome works best).
2. Choose a unit, read the **Learn** cards, and tap 🔊 to listen.
3. Practise with **Flashcards** and **Listen & Type**.
4. Finish each unit with its **Unit Review** texts.

Tip: on a phone, tap the screen once if the first sound does not play — some browsers wait for a tap.

## For the repository owner

```
index.html     the whole app (single file, no external dependencies)
audio/         4,409 mp3 files made with Edge TTS (about 95 MB)
README.md      this file
INFO.md        content details, sources and notes
```

If the `audio/` folder is missing, the app still speaks using the best voice on the device, and the top bar says so.

To rebuild the audio, keep `audio_manifest.json` and `gen_audio.py` (not needed on the website) and run:

```
pip install edge-tts
python gen_audio.py
```

## Units

| Unit | Topic | 主题 | Words | Review texts |
|---|---|---|---:|---:|
| 1 | Growing Up | 成长 | 51 | 3 |
| 2 | Mental and Physical Development | 身心发展 | 60 | 3 |
| 3 | Keeping Fit | 保持健康 | 70 | 3 |
| 4 | Lifestyles | 生活方式 | 70 | 3 |
| 5 | Student Life | 学生生活 | 64 | 3 |
| 6 | Effective Communication | 有效沟通 | 51 | 3 |
| 7 | On the Move | 旅行与迁移 | 49 | 3 |
| 8 | Through the Ages | 历史长河 | 39 | 3 |
| 9 | The Natural World | 自然世界 | 52 | 3 |
| 10 | Reaching for the Skies | 探索太空 | 57 | 3 |
| 11 | Design and Innovation | 设计与创新 | 85 | 3 |
| 12 | Information Technology | 信息技术 | 53 | 3 |
| 13 | The Modern World | 现代世界 | 54 | 3 |
| 14 | Urbanisation | 城市化 | 63 | 3 |
| 15 | The Green Revolution | 绿色革命 | 66 | 3 |
| 16 | The Energy Crisis | 能源危机 | 37 | 3 |
| 17 | Talking Business | 商业与工作 | 73 | 3 |
| 18 | The Law | 法律与犯罪 | 78 | 3 |
| 19 | The Media | 媒体 | 62 | 3 |
| 20 | The Arts | 艺术 | 88 | 3 |
| 21 | Reference & Writing | 参考与写作 | 31 | 3 |

## Credits

- Word list: based on the *IELTS Vocabulary Up to Band 6.0* unit list supplied by the author. Definitions, Chinese translations, IPA, example sentences and review texts were written for this app and should be reviewed by a teacher before classroom use.
- Voices: Microsoft Edge neural text-to-speech (en-GB-SoniaNeural, en-GB-RyanNeural).
- Built by **Daniel Wang · Words That Think**.

© 2026 Daniel Wang · Words That Think · For educational use.
