# BEKIUZ FORGE

**BEKIUZ FORGE** — Bekiuz Company uchun brauzer ichida ishlaydigan, shablon asosidagi sayt yaratuvchi.

🌐 Live website: https://bekiuz.github.io/bekiuz-nexus/

## Nimalar ishlaydi?

- Promptga qarab mos sayt turini tanlaydi: fast food, IT/agency, portfolio, academy, do‘kon va tadbir.
- 6 ta tayyor shablon — bir bosishda almashtirish.
- Jonli preview: matn, brend nomi, tugma va ranglarni o‘zgartirish.
- Desktop va mobil preview rejimi.
- Sahifa bo‘limlarini ko‘rsatish/yashirish.
- Tayyor saytni bitta HTML fayli sifatida yuklab olish.
- Joriy loyiha brauzerning localStorage xotirasiga saqlanadi.
- Mobil va desktop ekranga mos boshqaruv paneli.
- Build vositasi yoki server talab qilmaydi.

## Tez boshlash

1. Saytni oching.
2. Promptga saytingiz qanday bo‘lishini yozing yoki shablon tanlang.
3. **Sayt yaratish** tugmasini bosing.
4. Chap tomonda matn, rang va bo‘limlarni sozlang.
5. Preview orqali natijani tekshirib, **HTML yuklash** ni bosing.
6. Yuklab olingan HTML fayl brauzerda mustaqil ochiladi va o‘z saytining manba kodi bilan birga keladi.

## Hozirgi chegaralar

Bu versiya tashqi AI modeliga ulanmagan. Prompt matnidan kalit so‘zlar orqali shablon va rang uslubi tanlanadi; erkin AI kod generatsiyasi emas. Preview ichida ko‘rsatilgan tugmalar demo saytdagi bo‘limlarga olib boradi, lekin buyurtmalar yoki formalar serverga yuborilmaydi. HTML faylni internetda hammaga chiqarish uchun GitHub Pages, boshqa statik hosting yoki o‘z domeniga yuklash kerak.

## Rejaga olingan takomillashtirishlar

1. AI API ulab, foydalanuvchi yozgan talabga mos HTML/CSS generatsiyasi.
2. Ko‘proq dizayn shablonlari va section editor.
3. Rasmlarni yuklash, shrift va spacing boshqaruvi.
4. Bir nechta sahifali sayt yaratish va ZIP sifatida eksport qilish.
5. Publish tugmasi orqali hostingga joylash.
6. Aloqa formasi, buyurtma va analytics uchun ixtiyoriy integratsiyalar.

## Fayllar

- `index.html` — butun Forge ilovasi va shablonlarni yasaydigan generator.
- `forge-mark.svg` — Forge belgisi.
- `.github/workflows/deploy-pages.yml` — GitHub Pages avtomatik deploy.
