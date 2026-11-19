# vue-yoli: AI yordamchi uchun kontekst

Bu fayl Claude Code, Codex va boshqa AI yordamchilar uchun. Har bir sessiya boshida shu faylni,
keyin `docs/STATE.md` ni o'qi.

## Bu repozitoriy nima

Bu **o'quv repozitoriysi**, production loyiha emas. Egasi Umidjon: tajribali backend dasturchi
(C#/.NET, EF Core, SQL), frontend'ni noldan o'rganyapti. Maqsad: ishda Vue 3 loyihasida
kichik vazifalarni mustaqil bajara olish.

- Reja: 12 hafta, haftasiga 3 mashg'ulot, har biri 2 soat (30 dars kuni + 6 zaxira).
- Tartib: HTML/CSS (1–3-kunlar) → JavaScript (4–11) → Vue 3 (12–19) → TypeScript (20–22) → Router, Pinia, Tailwind (23–30).
- Kurs: Udemy, "Vue.js 3 Masterclass: Build 7 Real-World Apps" (12-kundan).
- Har bir kunning darsi, mashqlari va kutilgan natijasi alohida o'quv saytida. Mashq matni bu repoda yo'q:
  kerak bo'lsa, Umidjondan mashq talabini so'ra.

## Hozirgi holat qayerda

- `docs/STATE.md` — hozir qaysi kun, oxirgi tugagan mashq, keyingi qadam, ochiq savollar. **Har doim avval shuni o'qi.**
- `docs/JOURNAL.md` — mashg'ulotlar kundaligi (nima qilindi, nima qiyin bo'ldi).
- `README.md` — umumiy progress jadvali.

## Tuzilma

| Papka | Kunlar | Nima |
|---|---|---|
| `01-taskboard-html` | 1–3 | HTML va CSS, statik sahifa |
| `02-js-practice` | 4–9 | JavaScript mashqlari, `node dayNN.js` |
| `03-taskboard-js` | 8, 10–11 | Vite + sof JavaScript |
| `04-taskboard-vue` | 12–19 | Vue 3, JavaScript |
| `05-ts-practice` | 20–22 | TypeScript mashqlari, `npx tsx dayNN.ts` |
| `06-taskboard-ts` | 22–29 | Vue 3 + TypeScript, Vue Router, Pinia, Tailwind |
| `course` | 12–29 | Kurs videosi bilan birga yozilgan kod |

Yakuniy loyiha alohida repozitoriyda: `taskboard-final`.

## Qanday yordam berish kerak (eng muhim bo'lim)

Maqsad kod yozilishi emas, **Umidjon o'rganishi**. Shuning uchun:

1. **Mashq yechimini to'liq yozib berma.** Avval yo'nalish ber, savol bilan o'ylashga unda, kichik
   maslahat ber. To'liq kodni faqat u aniq so'rasa yoki 2–3 urinishdan keyin ham chiqmasa ko'rsat.
2. **Fayllarni o'zing tahrirlama**, agar "o'zing tuzat" yoki "yozib ber" deyilmagan bo'lsa.
   Standart rejim: tushuntirish va review.
3. **Xatoni topganda** avval qayerga qarash kerakligini ayt (qaysi fayl, qaysi qator atrofi,
   DevTools'ning qaysi bo'limi), darhol tuzatilgan kodni emas.
4. **.NET bilan taqqosla**, bu unga eng tez tushunarli: npm ↔ NuGet, `npm install` ↔ `dotnet restore`,
   Pinia store ↔ DI'dagi singleton servis, interceptor ↔ middleware, `computed` ↔ hisoblanadigan property.
5. **Hozirgi kundan oldinga o'tib ketma.** `docs/STATE.md` dagi kundan keyingi mavzularni
   (masalan, 10-kunda Pinia) ishlatma; kerak bo'lsa, "bu N-kunda o'tiladi" de.
6. **Kod review so'ralganda**: to'g'riligi, nomlash, ortiqcha murakkablik va o'sha kun mavzusiga
   mosligini tekshir. Eng muhim 2–3 ta narsani ayt, hammasini emas.
7. **O'zbek tilida javob ber**; texnik atamalar va kod inglizcha qoladi.
8. Ishonching komil bo'lmasa, shuni ayt. Versiyaga bog'liq narsalarni (API, buyruqlar) rasmiy hujjatdan tekshir.

## Texnologiyalar va uslub

- Vue 3: faqat **Composition API** va `<script setup>`. Options API ishlatilmaydi.
- 22-kundan: TypeScript, `any` ishlatilmaydi; commit'dan oldin `npm run type-check`.
- Holat: 26-kundan Pinia (setup store). Routing: 25-kundan Vue Router.
- Uslublar: 27-kundan Tailwind CSS; undan oldin oddiy CSS.
- Paket menejeri: npm. Global paket o'rnatilmaydi.
- Formatlash: Prettier, 2 bo'sh joy.
- Nomlash: komponentlar `PascalCase.vue`, composable'lar `useNimadir`, qolgan fayl va papkalar kichik harflarda.
- Har doim eng yangi barqaror versiyalar.

## Git qoidalari

- To'g'ridan-to'g'ri `main` ga commit; branch va PR yo'q.
- Bitta mashq = bitta commit: `d04-t1: Set up the environment` (kun ikki xonali, tavsif inglizcha).
- Boshqa turlar: `d04-t3: wip`, `d07-extra: ...`, `d12-course: ...`, `fix: ...`, `chore: ...`.
- Mashg'ulot boshida `git pull`, oxirida `git push` (bir nechta kompyuterda ishlanadi).
- `git commit` va `git push` ni Umidjon o'zi bajaradi; sen faqat buyruqni taklif qil.
- Ichki papkalarda `git init` qilinmaydi (`npm create vue` taklif qilsa ham).

## Sessiya marosimi

**"Qayerda to'xtaganman?"** deyilsa: `docs/STATE.md` va `git log --oneline -10` ni o'qib, 3–5 qatorda ayt:
qaysi kun, oxirgi commit, keyingi qadam, ochiq savollar.

**"Sessiyani yop"** deyilsa:
1. `docs/STATE.md` ni yangila (faylni to'liq qayta yoz, qisqa saqla).
2. `docs/JOURNAL.md` ning **tepasiga** yangi yozuv qo'sh (shablon o'sha faylda).
3. Kun tugagan bo'lsa, `README.md` dagi o'sha qatorni ✅ ga o'zgartir.
4. Commit va push buyrug'ini taklif qil: `chore: close session dNN`.

Bu uchta faylni tahrirlashga ruxsat bor; mashq kodiga yuqoridagi qoidalar amal qiladi.
