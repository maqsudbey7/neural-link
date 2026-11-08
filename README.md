# Neural Link — tinchlantiruvchi nur zarrachalari

**UZ** · Bolalar va kattalar uchun asabni tinchlantiruvchi o'yinchoq: minglab yumshoq nur zarrachalari qo'lingizga ergashadi, nafas mashqi bilan birga kattalashib-kichrayadi. Hammasi brauzerda, video qurilmadan chiqmaydi.
**EN** · A calming toy for kids and grown-ups: thousands of soft light particles follow your hand and breathe with you. Runs in the browser; video never leaves the device.

## Qanday ishlaydi / How it works

| | UZ | EN |
|---|---|---|
| 🌬️ | ◎ tugmasi — nafas mashqi: 4 s nafas oling, 2 s ushlab turing, 6 s sekin chiqaring; nur shari siz bilan birga nafas oladi | ◎ button — breathing: in 4 s, hold 2 s, out 6 s; the glowing ball breathes with you |
| ✋ | qo'lni harakatlantiring — zarrachalar ergashadi; kaftni ochsangiz tarqaladi, musht qilsangiz to'planadi | move your hand — particles follow; open palm spreads them, fist gathers them |
| 🫶 | ikki qo'l bilan (yoki 🫰 barmoq bilan) yurak qiling — urib turgan yurak va "SEVGI" | make a heart with two hands (or 🫰 fingers) — a beating heart appears |
| ✍️ | pastga so'z yozing (`coffee`, `sevgi`, `yulduz`, `кофе`, emoji…) — zarrachalar o'sha narsa va so'zga aylanadi | type a word — particles become its emoji and the word |
| ✊ | musht — so'z tarqab ketadi | fist — the word scatters |
| 🌀 | shakl tanlang (Shar, Kub, Yulduz, DNK, Halqa, Galaktika) — kaft ustida 3D shakl; bilak bilan aylantiring, 🤏 bilan kattalashtiring, ikki qo'l bilan cho'zing | pick a shape — a 3D particle shape above your palm; twist to rotate, pinch to resize, two hands to stretch |

O'ng menyu: nafas · shakl · rang (6 ta yumshoq palitra) · fon (tungi osmon / kamera) · qo'l skeleti · surat · video · ⋯ (ovoz, til, kamera). Surat va videolarda `NEURAL LINK · sayt` belgisi bor, telefonda **↗ ULASHISH** tugmasi chiqadi.

Ekranda xato chiqsa, uning matni yuqorida qizil oynada ko'rinadi.

## Deploy

GitHub'ga push qilinsa, Vercel avtomatik yangilaydi (Framework: **Other**, build yo'q). Kamera faqat **https** yoki `localhost`da ishlaydi. Lokal: `npx serve .`

## Texnik

MediaPipe HandLandmarker (Web Worker) · Three.js (bitta WebGL kontekst, maxsus zarracha sheyderi) · One Euro filtri + kechikishni taxminlash · Web Audio · PWA.
