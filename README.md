# Vue yo'li

> Backend (.NET) dasturchidan full stack tomon:
> **HTML/CSS → JavaScript → Vue 3 → TypeScript → Router, Pinia**

| Reja               | 12 hafta · haftasiga 3 mashg'ulot · 2 soatdan |
| :----------------- | :-------------------------------------------- |
| **Hajm**           | 30 dars kuni + 6 zaxira mashg'ulot + 5 test   |
| **Kurs**           | Udemy: Vue.js 3 Masterclass (12-kundan)       |
| **Boshlangan**     | YYYY-MM-DD                                    |
| **Yakuniy loyiha** | alohida repozitoriy: `taskboard-final`        |

---

## Papkalar

| Papka               |  Kunlar  | Mavzu                             |
| :------------------ | :------: | :-------------------------------- |
| `01-taskboard-html` |   1–3    | HTML va CSS                       |
| `02-js-practice`    |   4–9    | JavaScript mashqlari              |
| `03-taskboard-js`   | 8, 10–11 | Vite + sof JavaScript             |
| `04-taskboard-vue`  |  12–19   | Vue 3                             |
| `05-ts-practice`    |  20–22   | TypeScript mashqlari              |
| `06-taskboard-ts`   |  22–29   | Vue 3 + TypeScript, Router, Pinia |
| `course`            |  12–29   | Kurs videosi bilan yozilgan kod   |

### Ishga tushirish

```bash
# 01: VS Code'da index.html → o'ng tugma → Open with Live Server

# 02 va 05: bitta faylni ishga tushirish
node day04.js
npx tsx day20.ts

# 03, 04, 06: loyiha papkasi ichida
npm install
npm run dev
```

---

## Commit qoidasi

Bitta mashq = bitta commit. Kun oxirida bitta `git push`.

```text
d04-t1: Set up the environment     4-kun, 1-mashq
d04-t3: wip                        tugamagan mashq
d07-extra: rewrite array tasks     zaxira mashg'ulot
d12-course: can you drive          kurs videosi bilan yozilgan kod
fix: d10 render bug                avvalgi kundagi xatoni tuzatish
chore: update README progress      mashqqa bog'liq bo'lmagan o'zgarish
```

---

## Progress

Belgilar: ⬜ boshlanmagan · 🟨 jarayonda · ✅ tugagan

### 1-bosqich · HTML/CSS minimumi

| Kun | Mavzu                                         | Hafta | Holat |
| :-: | :-------------------------------------------- | :---: | :---: |
| 01  | HTML: sahifa skeleti, teglar, forma, jadval   |   1   |  ⬜   |
| 02  | CSS: selektorlar, box model, ranglar          |   1   |  ⬜   |
| 03  | Flexbox, Grid va mini loyiha                  |   1   |  ⬜   |
|  +  | Zaxira: mini loyihani namunasiz qayta yig'ish |   2   |  ⬜   |
| T1  | 1-bosqich testi (20 savol, o'tish 16)         |   2   |  ⬜   |

### 2-bosqich · JavaScript

| Kun | Mavzu                                             | Hafta | Holat |
| :-: | :------------------------------------------------ | :---: | :---: |
| 04  | O'zgaruvchilar, tiplar, shartlar, sikllar         |   2   |  ⬜   |
| 05  | Funksiyalar va arrow funksiyalar                  |   2   |  ⬜   |
| 06  | Obyektlar, massivlar, destructuring, spread       |   3   |  ⬜   |
| 07  | Massiv metodlari: map, filter, find, reduce       |   3   |  ⬜   |
|  +  | Zaxira: massiv metodlari mashqlarini qayta yozish |   3   |  ⬜   |
| 08  | Modullar, npm va Vite                             |   4   |  ⬜   |
| 09  | Async: Promise, async/await, fetch                |   4   |  ⬜   |
| 10  | DOM va hodisalar                                  |   4   |  ⬜   |
|  +  | Zaxira: 9–10-kunlarning tugamagan mashqlari       |   5   |  ⬜   |
| 11  | JavaScript mini loyihasi                          |   5   |  ⬜   |
| T2  | 2-bosqich testi (20 savol, o'tish 16)             |   5   |  ⬜   |

### 3-bosqich · Vue Masterclass, 1–4-loyihalar

| Kun | Mavzu                                     | Hafta | Holat |
| :-: | :---------------------------------------- | :---: | :---: |
| 12  | Vue'ga kirish va 1-loyiha: Can You Drive? |   5   |  ⬜   |
| 13  | 2-loyiha: rasm galereyasi                 |   6   |  ⬜   |
| 14  | 3-loyiha: Task Manager                    |   6   |  ⬜   |
| 15  | 4-loyiha: komponentlar, 1-qism            |   6   |  ⬜   |
| 16  | 4-loyiha: komponentlar, 2-qism            |   7   |  ⬜   |
| 17  | 4-loyiha: ma'lumot yuklash                |   7   |  ⬜   |
| 18  | 4-loyiha: optimistik UI va xatolar        |   7   |  ⬜   |
| 19  | Composable'lar                            |   8   |  ⬜   |
| T3  | 3-bosqich testi (20 savol, o'tish 16)     |   8   |  ⬜   |

### 4-bosqich · TypeScript

| Kun | Mavzu                                 | Hafta | Holat |
| :-: | :------------------------------------ | :---: | :---: |
| 20  | Asosiy tiplar va interface            |   8   |  ⬜   |
| 21  | Generic va utility tiplar             |   8   |  ⬜   |
| 22  | Narrowing va Vue bilan ishlatish      |   9   |  ⬜   |
| T4  | 4-bosqich testi (15 savol, o'tish 12) |   9   |  ⬜   |

### 5-bosqich · Vue Masterclass, 5–7-loyihalar

| Kun | Mavzu                                       | Hafta | Holat |
| :-: | :------------------------------------------ | :---: | :---: |
| 23  | 5-loyiha: TypeScript, transition, tab'lar   |   9   |  ⬜   |
| 24  | 5-loyiha: Teleport, KeepAlive, umumiy holat |   9   |  ⬜   |
|  +  | Zaxira: 18 va 24-kunlardan qolgan mashqlar  |  10   |  ⬜   |
| 25  | 6-loyiha: Vue Router                        |  10   |  ⬜   |
| 26  | 6-loyiha: Pinia, 1-qism                     |  10   |  ⬜   |
| 27  | 6-loyiha: Pinia, 2-qism                     |  11   |  ⬜   |
| 28  | 7-loyiha: Trello doskasi, 1-qism            |  11   |  ⬜   |
| 29  | 7-loyiha: Trello doskasi, 2-qism            |  11   |  ⬜   |
| 30  | Yakuniy loyiha                              |  12   |  ⬜   |
|  +  | Zaxira: yakuniy loyiha (doska va modal)     |  12   |  ⬜   |
|  +  | Zaxira: yakuniy loyiha (sifat va testlar)   |  12   |  ⬜   |
| T5  | Umumiy test (30 savol, o'tish 24)           |  12   |  ⬜   |

---

## Eslatmalar

Tushunmagan joylar va qayta ko'rish kerak bo'lgan mavzular.

| Sana | Kun | Eslatma |
| :--- | :-: | :------ |
|      |     |         |
