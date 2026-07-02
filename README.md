# Hotel Portfolio

Портфолио цифрового гостевого гида для отелей, апарт-отелей и курортных объектов.

## Что внутри

- `index.html` — главная страница портфолио.
- `demos/boutique/` — демо для бутик-отеля.
- `demos/apart/` — демо для апарт-отеля.
- `demos/spa/` — демо для курортного СПА-отеля.
- `first-leads-sochi.csv` — стартовая база из 25 лидов.
- `client-outreach.md` — скрипты первых сообщений.
- `sales-pipeline.md` — воронка и статусы продаж.

## Локальный просмотр

Из папки `outputs`:

```bash
python3 -m http.server 8766
```

Затем открыть:

```text
http://localhost:8766/hotel-portfolio/index.html
```

## Бесплатная публикация

### Netlify

1. Открыть Netlify.
2. New site from Git.
3. Выбрать репозиторий `hotel-portfolio`.
4. Build command оставить пустым.
5. Publish directory: `.`
6. Deploy.

### Vercel

1. Открыть Vercel.
2. Add New Project.
3. Выбрать репозиторий `hotel-portfolio`.
4. Framework Preset: Other.
5. Build command оставить пустым.
6. Output directory оставить пустым или `.`.
7. Deploy.

## GitHub Pages

GitHub Pages включен для репозитория, но деплой GitHub сейчас падает на стороне сервиса с ошибкой:

```text
Deployment failed, try again later.
```

Код сайта собирается корректно; проблема не в файлах проекта.

