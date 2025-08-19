# SmileScore — GitHub Pages (Вариант A, один файл)

Позитивная оценка улыбки прямо в браузере. Всё локально, без серверов.
Публикуется одним файлом `index.html` (React + Tailwind + Framer Motion через CDN).

## Быстрый деплой через веб‑интерфейс GitHub
1. Создайте публичный репозиторий (например, `smilescore`).
2. Загрузите **в корень** репозитория файлы из этого архива:
   - `index.html`
   - `.nojekyll` (опционально, но рекомендуем)
   - `README.md` (для удобства)
3. Включите GitHub Pages: **Settings → Pages**
   - **Build and deployment → Source:** *Deploy from a branch*
   - **Branch:** `main` • **Folder:** `/ (root)` → **Save**
4. Откройте сайт: `https://<ваш-логин>.github.io/<имя-репо>/`

## Важно (камера):
- Камера работает только в **безопасном контексте**: HTTPS (GitHub Pages) или `http://localhost`.
- При первом открытии дайте сайту разрешение на доступ к камере.
- На iOS: Настройки → Safari → Камера — разрешить; в настройках сайта включить доступ.

## Локальная проверка
```bash
python -m http.server 8000
# или
npx serve
```
Откройте `http://localhost:8000` — камера на localhost разрешена.

## Обновления
Правьте `index.html` → коммитьте → `git push` — GitHub Pages автоматически переопубликует сайт.