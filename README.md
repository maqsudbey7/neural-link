# Neural Link — nur fidget o'yinchog'i

**UZ** · Bolalar va kattalar uchun tinchlantiruvchi fidget o'yinchoq: qo'lingiz minglab nurga aylanadi, chimdib to'plang va qo'yib yuboring — portlaydi. Hammasi brauzerda, video qurilmadan chiqmaydi.
**EN** · A calming fidget toy for kids and grown-ups: your hand turns into thousands of lights — pinch to gather, let go to burst. Runs in the browser; video never leaves the device.

## Qanday o'ynaladi / How to play

| | UZ | EN |
|---|---|---|
| ✋ | qo'lni ko'rsating — zarrachalar qo'lingizni qoplaydi va kechikmasdan ergashadi | show your hand — particles coat it and follow without lag |
| 🤏 | bosh va ko'rsatkich barmoqni qising — nur shari to'planadi; qancha uzoq ushlasangiz shuncha kuchli; qo'yib yuborsangiz portlaydi | pinch — gather a ball of light; hold longer for a bigger burst; let go to explode |
| 🚀 | nur sharini ushlab turib qo'lni tez silkiting — shar otilib ketadi va rang-barang salyut bo'lib portlaydi | hold the ball and flick — it flies and bursts into fireworks |
| 👏 | ikki qo'l bilan qarsak — butun ekran bo'ylab kamalak zarba to'lqini | clap — a rainbow shockwave across the screen |
| ✨ | barmoq tez harakatlansa — orqasidan nurli iz qoladi | fast fingers leave glowing light trails |
| 👆 | kamera bo'lmasa: ekranga bosib torting, qo'yib yuboring | no camera: press and drag on the screen, then release |
| ⚡ | O'yin → Zaryad: kaftni ochib ushlang — nur kaftga so'riladi (0→100% ZARYADLANDI, uzoqroq — MEGA), musht qiling — katta portlash, ekran silkinadi; MEGA dan keyin syurpriz rasm (🦄 🚀 🐼 …) | Play → Charge: hold an open palm to charge (100% → CHARGED, longer → MEGA), make a fist to blast; MEGA reveals a surprise picture |
| 🫶 | yurak qiling — "SEVGI"; 🤝 ikki kishi kaftlarini yaqinlashtirsa ham yurak chiqadi | make a heart; two people bringing palms together also makes one |
| ✍️ | so'z yozing (`coffee`, `sevgi`, `yulduz`…) — nurlar o'sha narsaga aylanadi; ✊ musht — tarqaladi | type a word — the light becomes it; fist scatters it |
| ✦ | Shakl menyusi: 3D shakllar, qo'l bilan aylantiring va kattalashtiring | Shape menu: 3D shapes you rotate and resize by hand |

O'ng menyu: o'yin · shakl · rang · fon (tungi osmon / kamera) · surat · video · ⋯ (ovoz, til, qo'l skeleti, yengil rejim, kamera).

## Deploy

GitHub'ga push qilinsa, Vercel avtomatik yangilaydi (Framework: **Other**, build yo'q). Kamera faqat **https** yoki `localhost`da ishlaydi. Lokal: `npx serve .`

## Texnik

MediaPipe HandLandmarker (Web Worker) · Three.js (bitta WebGL kontekst, maxsus zarracha sheyderi) · One Euro filtri + kechikishni taxminlash · Web Audio · PWA.
