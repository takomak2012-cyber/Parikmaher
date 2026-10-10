# Парикмахер — сайт приложения

Сайт-страница мобильного приложения «Парикмахер» (записи клиентов, график работы, цены, отчёты).

- Сайт: https://takomak2012-cyber.github.io/Parikmaher/
- Приложение в RuStore: https://rustore.ru/catalog/app/ru.parikmaher.app
- Политика конфиденциальности: https://takomak2012-cyber.github.io/Parikmaher/privacy.html

## Структура

```
index.html            главная страница
privacy.html          политика конфиденциальности
assets/style.css      стили (тёмная тема в палитре приложения)
assets/icon-512.png   иконка приложения 512×512 (та же, что в приложении и в RuStore)
assets/screen-*.png   скриншоты экранов приложения (главный, настройки, выбор времени, отчёты)
```

Сайт статический, внешних зависимостей нет, публикуется через GitHub Pages из корня репозитория.

## Как обновить

Внести правки в `index.html` / `privacy.html` / `assets/` и выполнить:

```
git add -A
git commit -m "Обновление сайта"
git push
```

GitHub Pages опубликует изменения автоматически в течение минуты-двух.

## Контакты поддержки

Сайт и политика конфиденциальности ссылаются на страницу поддержки:
https://github.com/takomak2012-cyber/Parikmaher/issues
