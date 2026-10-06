# Арсенал недвижимость

Статический сайт компании «Арсенал недвижимость» (arsned.ru). Публикуется через GitHub Pages из ветки `main`.

Структура:

- `index.html`: главная страница
- `assets/styles.css`: стили
- `assets/logo.svg`, `assets/logo-light.svg`: логотип для светлого и тёмного фона
- `assets/favicon.svg`, `assets/favicon.ico`, `assets/apple-touch-icon.png`: иконки

Значения в квадратных скобках (`[ЦЕНА]`, `[ВАШ ТЕЛЕФОН]` и т. п.) это заглушки, их нужно заменить реальными данными. Пока сайт закрыт от индексации тегом `noindex` в `index.html`.

Локальный просмотр:

```bash
python3 -m http.server 8000
```
