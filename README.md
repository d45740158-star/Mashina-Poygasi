# 🏁 Mashina Poygasi

Brauzerda ishlaydigan, HTML5 Canvas asosida yaratilgan 2D mashina poygasi o'yini. Bitta qurilmada botga qarshi yoki do'stingiz bilan yarishing!

**Demo:** [mashina-poygasi.netlify.app](https://mashina-poygasi.netlify.app/)

## 📖 Loyiha haqida

O'yinning maqsadi — stadion shaklidagi trassada 3 aylanani birinchi bo'lib tugatish. Trassadan chiqib ketsangiz, mashinangiz sekinlashadi, shuning uchun burilishlarda ehtiyot bo'lish kerak.

O'yin Dilshod Nabiyev tomonidan yaratilgan.

## ✨ Xususiyatlar

- 🤖 **Bot bilan o'ynash** — kompyuter tomonidan boshqariladigan raqibga qarshi yarishing
- 👥 **Do'st bilan o'ynash** — bitta qurilmada ikki kishi bab-baravar poyga qiladi
- 🎮 **Klaviatura boshqaruvi** — 1-o'yinchi uchun WASD, 2-o'yinchi uchun strelka tugmalari
- 📱 **Sensorli ekran qo'llab-quvvatlash** — mobil qurilmalarda ekranga chiqadigan boshqaruv tugmalari
- 🏎️ **Realistik fizika** — tezlanish, tormoz, ishqalanish va tezlikka bog'liq burilish
- ⏱️ **Sanoq bilan start** (3, 2, 1, KETDIK!) va aylanalar hisoblagichi (HUD)
- 🏆 **G'alaba oynasi** — natija ko'rsatiladi va qayta o'ynash imkoniyati beriladi
- 📐 **Moslashuvchan (responsive) dizayn** — turli ekran o'lchamlariga avtomatik moslashadi

## 🎮 Boshqaruv

| O'yinchi | Chapga | O'ngga | Gaz | Tormoz |
|---|---|---|---|---|
| 1-o'yinchi | `A` | `D` | `W` | `S` |
| 2-o'yinchi | `←` | `→` | `↑` | `↓` |

Sensorli qurilmalarda ekranga mos boshqaruv tugmalari avtomatik chiqadi.

## 🛠️ Texnologiyalar

- **HTML5** — sahifa tuzilishi
- **CSS3** — dizayn va animatsiyalar (Google Fonts: `Orbitron`, `Rajdhani`)
- **Vanilla JavaScript** — o'yin mantig'i va fizika
- **Canvas API** — 2D grafika va animatsiya rendering

Tashqi kutubxona yoki freymvorklardan foydalanilmagan — bitta `index.html` fayli ichida to'liq mustaqil ishlaydi.

## 🚀 Ishga tushirish

Loyiha hech qanday build jarayoni yoki server talab qilmaydi:

```bash
git clone https://github.com/d45740158-star/Mashina-Poygasi.git
cd Mashina-Poygasi
```

So'ngra `index.html` faylini istalgan brauzerda oching, yoki qulayroq ishlashi uchun mahalliy serverda ishga tushiring:

```bash
# Python bilan
python3 -m http.server 8000

# yoki Node.js bilan (http-server o'rnatilgan bo'lsa)
npx http-server
```

Keyin brauzerda `http://localhost:8000` manziliga o'ting.

## 📁 Loyiha tuzilishi

```
Mashina-Poygasi/
└── index.html   # HTML, CSS va JavaScript kodlarining barchasi shu yerda
```

## 🎯 Qanday o'ynash mumkin

1. Bosh sahifada **🤖 BOT BILAN** yoki **👥 DO'ST BILAN** rejimini tanlang
2. Sanoq (3, 2, 1, KETDIK!) tugagach, poyga boshlanadi
3. Mashinangizni boshqarib, 3 aylanani birinchi bo'lib tugating
4. G'alaba qozongach, **QAYTA O'YNASH** yoki **MENYU** tugmalaridan birini tanlang

## 📄 Litsenziya

Litsenziya haqida ma'lumot repozitoriyda ko'rsatilmagan. Agar loyihadan foydalanmoqchi bo'lsangiz, muallif bilan bog'lanib aniqlashtirish tavsiya etiladi.
