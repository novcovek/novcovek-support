# NovCovek Support

**[English](#english) · [Македонски](#македонски)**

Live site / Активна страница: **https://support.novcovek.com**

---

## English

Support website for **NovCovek**, a centralized healthcare platform. This repository contains the static site served at `support.novcovek.com`.

### Repository structure

| File | Purpose |
|---|---|
| `index.html` | The support page itself |
| `CNAME` | Tells GitHub Pages which custom domain serves this repo |
| `README.md` | This file |

### Deployment

The site is published with **GitHub Pages** from the `main` branch. Any commit pushed to `main` redeploys automatically — usually within a minute. Deployment status is visible under the repository's **Actions** tab.

DNS is handled at the registrar with a single `CNAME` record pointing `support` at `novcovek.github.io`.

> Do not delete the `CNAME` file. Removing it detaches the custom domain and the site reverts to the default `github.io` address.

### Running it locally

```bash
git clone https://github.com/novcovek/novcovek-support.git
cd novcovek-support
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser. Opening `index.html` directly as a file also works for simple changes.

### Contributing

Small fixes can be made directly through the GitHub web editor. For anything larger, open a branch and a pull request so the change can be reviewed before it goes live.

---

## Македонски

Веб-страница за поддршка на **NovCovek**, централизирана здравствена платформа. Ова складиште ја содржи статичната страница што се објавува на `support.novcovek.com`.

### Структура на складиштето

| Датотека | Намена |
|---|---|
| `index.html` | Самата страница за поддршка |
| `CNAME` | Му кажува на GitHub Pages кој приспособен домен ја опслужува страницата |
| `README.md` | Оваа датотека |

### Објавување

Страницата се објавува преку **GitHub Pages** од гранката `main`. Секоја промена испратена на `main` автоматски се објавува повторно — обично во рок од една минута. Статусот на објавувањето може да се види во делот **Actions**.

DNS-от е поставен кај регистраторот со еден `CNAME` запис што го насочува `support` кон `novcovek.github.io`.

> Не ја бришете датотеката `CNAME`. Нејзиното отстранување го одврзува приспособениот домен и страницата се враќа на стандардната `github.io` адреса.

### Локално стартување

```bash
git clone https://github.com/novcovek/novcovek-support.git
cd novcovek-support
python3 -m http.server 8000
```

Потоа отворете `http://localhost:8000` во прелистувач. За едноставни промени може и директно да се отвори `index.html`.

### Придонесување

Ситните измени може да се направат директно преку веб-уредувачот на GitHub. За поголеми промени, отворете нова гранка и pull request за да може измената да се прегледа пред да биде објавена.
