# NEURAL LINK `// particles in your hand`

**UZ** · Minglab nurli zarrachalar qo'lingizga ergashadi. Yurak qilsangiz — yurakka, so'z yozsangiz — o'sha narsaga aylanadi. Hammasi brauzerda, video qurilmadan chiqmaydi.
**EN** · Thousands of glowing particles follow your hand, become a heart when you make one, and turn into any word you type. Runs in the browser; video never leaves your device.

## Qanday ishlaydi / How it works

| | UZ | EN |
|---|---|---|
| ✋ | qo'lni harakatlantiring — zarrachalar ergashadi; kaftni ochsangiz tarqaladi, musht qilsangiz to'planadi | move your hand — particles follow; open palm spreads them, fist gathers them |
| 🫶 | ikki qo'l bilan (yoki 🫰 barmoq bilan) yurak qiling — urib turgan yurak va "SEVGI" | make a heart with two hands (or 🫰 fingers) — a beating heart appears |
| ✍️ | pastga so'z yozing (`coffee`, `sevgi`, `yulduz`, `кофе`, emoji…) — zarrachalar o'sha narsa va so'zga aylanadi | type a word — particles become its emoji and the word |
| ✊ | musht — so'z tarqab ketadi | fist — the word scatters |
| 🌀 | shakl tanlang (Shar, Kub, Yulduz, DNK, Halqa, Galaktika) — kaft ustida 3D shakl; bilak bilan aylantiring, 🤏 bilan kattalashtiring, ikki qo'l bilan cho'zing | pick a shape — a 3D particle shape above your palm; twist to rotate, pinch to resize, two hands to stretch |

O'ng menyu: shakl · rang · fon (kamera / qora) · qo'l skeleti · surat · video · ⋯ (ovoz, til, kamera). Surat va videolarda `NEURAL LINK · sayt` belgisi bor, telefonda **↗ ULASHISH** tugmasi chiqadi.

Ekranda xato chiqsa, uning matni yuqorida qizil oynada ko'rinadi.

## Deploy

GitHub'ga push qilinsa, Vercel avtomatik yangilaydi (Framework: **Other**, build yo'q). Kamera faqat **https** yoki `localhost`da ishlaydi. Lokal: `npx serve .`

## Texnik

MediaPipe HandLandmarker (Web Worker) · Three.js (bitta WebGL kontekst, maxsus zarracha sheyderi) · One Euro filtri + kechikishni taxminlash · Web Audio · PWA.
