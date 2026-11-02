# Сайт Евгения Ергонова — GitHub Pages

Готовый статический сайт ведущего мероприятий и вокалиста. Главная страница находится в `index.html`, изображение обложки и аудиозапись — в `assets/`.

## Как создать репозиторий и опубликовать сайт

1. Войдите в GitHub и нажмите **+ → New repository**. Назовите репозиторий `evgeniy-ergonov`. Для бесплатной публикации GitHub Pages используйте публичный репозиторий; исходники сайта будут видны всем.
2. Создайте репозиторий. Можно добавить README при создании, затем загрузить файлы сайта через **Add file → Upload files**.
3. Распакуйте архив на компьютере. Загрузите содержимое папки сайта в корень репозитория: `index.html`, `.nojekyll`, папку `assets` и этот `README.md`. Не загружайте только ZIP и не создавайте дополнительную вложенную папку вокруг файлов.
4. Нажмите **Commit changes**.
5. Откройте **Settings → Pages**. В **Build and deployment** выберите **Deploy from a branch**, ветку `main`, папку `/(root)` и нажмите **Save**.
6. Дождитесь сборки Pages. Ссылка появится в разделе **Settings → Pages**; для проекта обычно она имеет вид `https://ВАШ-ЛОГИН.github.io/evgeniy-ergonov/`.

## Как обновить сайт

Замените в репозитории нужные файлы на новые версии, сохраняя имена и расположение `assets`. Нажмите **Commit changes** — GitHub Pages автоматически пересоберёт сайт. Обновление может появиться не сразу; при проверке страницы обновите браузер без кэша.

## Полезно знать

- Структура должна оставаться такой: `index.html`, `.nojekyll`, `README.md`, `assets/evgeniy-hero.png`, `assets/kakaya-pogoda-vnutri.mp3`.
- Если появляется 404, проверьте, что `index.html` лежит именно в корне выбранной папки публикации, а в Pages выбраны `main` и `/(root)`.
- Контакт для заявок пока не задан: перед продвижением сайта добавьте рабочий телефон, email или ссылку на соцсеть.

## Официальные инструкции GitHub

- [Создание нового репозитория](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [Настройка источника публикации GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
