# Hush website

Статичний сайт для застосунку Hush: головна, підтримка, політика конфіденційності, умови використання,
англійською (корінь) і українською (`uk/`). Без збірки й залежностей, лише HTML і один `style.css`.

Сторінки, потрібні App Store Connect:

- Privacy Policy URL: `https://sarann-cmyk.github.io/hush-web/privacy.html`
- Support URL: `https://sarann-cmyk.github.io/hush-web/support.html`
- Terms of Use: `https://sarann-cmyk.github.io/hush-web/terms.html` (або стандартна Apple EULA)

Посилання в застосунку задані в `Hush/Modules/Subscription/Services/AppLinks.swift`.

## Публікація (GitHub Pages)

1. Створити публічний репозиторій `hush-web` на GitHub.
2. `git remote add origin https://github.com/Sarann-cmyk/hush-web.git && git push -u origin main`
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
4. Через хвилину-дві сторінки відкриваються за адресами вище без логіну.

Контактна пошта й дата «Останнє оновлення» лежать у тексті сторінок; при змінах оновлюй обидві мови.
