# NEURAL LINK `// holograms in your hand`

**UZ** · Gologrammani qo'lingizda ushlang — barmoqlar bilan kattalashtiring, bilak bilan aylantiring. Hammasi brauzerda, video qurilmadan chiqmaydi.
**EN** · Hold a hologram in your hand — resize it with your fingers, spin it with your wrist. Runs in the browser; video never leaves your device.

## Qanday o'ynaladi / How to play

| Imo | UZ | EN |
|---|---|---|
| ✋ | qo'lni ko'rsating — shakl kaft ustida paydo bo'ladi | show your hand — a hologram appears above your palm |
| 🤏 | bosh va ko'rsatkich barmoqni yozing / yaqinlashtiring — kattalashadi / kichrayadi | spread / pinch thumb and index — resize |
| 🔄 | bilakni buring — shakl aylanadi | twist your wrist — spin it |
| 🙌 | ikki qo'l — cho'zib kattalashtiring | two hands — stretch it |
| ✌️ | V belgisini ushlab turing — keyingi shakl | hold the V sign — next shape |
| ✊ | musht — yashirish (kaftni ochsangiz qaytadi) | fist — hide (open palm brings it back) |

Pastdagi maslahat foydalanuvchi hali sinamagan narsani bittadan ko'rsatadi.

## O'ng menyu / Right menu

Shakl (6 ta: globus, tesserakt, yadro, spiral, reaktor, atom) · Rang (6 palitra) · **Zaryad/Repulsor** (ochiq kaft → musht = zarba to'lqini, standart o'chiq) · **Portal** (☝️ bilan havoda doira) · **Plazma** (ikki qo'l orasida) · Yuz to'ri · Ko'rinish (ODDIY / TUNGI / MATRITSA) · Surat · Video · ⋯ (ovoz, til, kamera)

Har bir surat va videoda `NEURAL LINK · sayt-manzili` belgisi bo'ladi; telefonda **↗ ULASHISH** tugmasi chiqadi. Sozlamalar qurilmada eslab qolinadi.

Klaviatura: `1–6` shakl · `C` rang · `V` ko'rinish · `S` surat · `R` video · `P` portal · `B` zarba

## Deploy

```bash
cd neural-link
git init && git add . && git commit -m "Neural Link"
git branch -M main
git remote add origin https://github.com/<user>/neural-link.git
git push -u origin main
```
Vercel: [vercel.com/new](https://vercel.com/new) → **Import** → Framework: **Other** → **Deploy**. Kamera faqat **https** yoki `localhost`da ishlaydi. Lokal: `npx serve .`

## Texnik

MediaPipe (HandLandmarker, FaceLandmarker, ImageSegmenter — Web Worker'da) · Three.js + bloom · GLSL shader · One Euro filtri + kechikishni taxminlash · Web Audio · PWA.
