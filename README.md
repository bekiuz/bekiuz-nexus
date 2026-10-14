# BEKIUZ NEXUS

Bekiuz Company uchun o‘zbek tilidagi interaktiv raqamli portfolio.

## Xususiyatlar

- Moslashuvchan, telefon va kompyuter ekranlariga mos dizayn
- Canvas orqali chiziladigan animatsiyali raqamli yadro
- 6 ta bosiladigan yo‘nalish va o‘zgaradigan tafsilot paneli
- Nari AI, Zuxrash AI, Modern Academy Bot va Oazis Fast Food loyihalari
- Loyihalarni kategoriya bo‘yicha filtrlash
- Mahalliy terminal: `help`, `about`, `projects`, `status`, `contact`, `clear`, `nexus`
- `Ctrl+K` yoki `⌘K` bilan tezkor qidiruv
- Build vositasi talab qilinmaydi — sayt to‘g‘ridan-to‘g‘ri `index.html` dan ishlaydi

## GitHub Pages orqali chiqarish

1. Repository ichida **Settings → Pages** bo‘limini oching.
2. **Build and deployment → Source** qismida **GitHub Actions** ni tanlang.
3. **Actions** bo‘limida `Deploy BEKIUZ NEXUS to GitHub Pages` workflow ishga tushishini tekshiring.
4. Deploy muvaffaqiyatli tugagach, Actions logida yoki Settings → Pages bo‘limida berilgan saytingiz havolasini oching.

Workflow `main` branchga yangi commit tushganda avtomatik ishga tushadi.

## Muhim

Terminal, qidiruv va yo‘nalish kartalari brauzer ichidagi demo funksiyalaridir. Bu versiya tashqi AI modeliga yoki Telegram bot serveriga API orqali ulanmagan. Loyiha kartalari portfolio ko‘rinishida berilgan va har birining holati alohida tekshirilishi kerak.

## Fayllar

- `index.html` — sahifa, dizayn va JavaScript bitta faylda
- `.github/workflows/deploy-pages.yml` — GitHub Pages deploy workflow
- `nexus-mark.svg` — brauzer belgisi
