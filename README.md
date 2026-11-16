# Greenroom: файли сайту

Статичний сайт без збирання: один файл `index.html`.
Фото рослин і відео головного блоку підвантажуються з Cloudinary (res.cloudinary.com/mhrw0qgv),
шрифти Fraunces, DM Sans і Satisfy з Google Fonts.

Відео головного блоку вже зациклене й обрізане (hero-room.mp4); для телефона Cloudinary віддає зменшену копію через `w_854,q_auto:good` у посиланні.
Не видаляйте ці файли з Cloudinary, інакше сайт втратить фото й відео.

## Як задеплоїти

- **Netlify (найпростіше):** відкрийте app.netlify.com/drop і перетягніть туди папку `greenroom-site`.
- **Vercel:** імпортуйте папку чи репозиторій на vercel.com (Framework: Other, без команди збирання).
- **GitHub Pages:** покладіть `index.html` у корінь репозиторію, далі Settings → Pages → Deploy from a branch → `main` / root.
- **Cloudflare Pages:** Create project → Direct Upload → завантажте папку.

## Що замінити перед запуском

- Пошту, телефон, адресу шоуруму (вул. Садова, 14) у футері та в позначці на відео.
- Посилання на Instagram, Telegram і Facebook і нікнейм @greenroom.plants.
- Відгуки, оцінку 4,9 і кількість замовлень: зараз це приклади.
- Кошик лише рахує суму: оплата й оформлення замовлення не підключені.
