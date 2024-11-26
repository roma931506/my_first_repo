# my_first_repo
Делаем fork репозитория, в которой потом хотим сделать pull request. Ищем кнопку Fork на странице репозитория https://git@github.com:gulden-geekbrains/version_control.git
Выполняем команду клонирования из своей fork-копии
git clone git@github.com:*YOURE_GITHUB*/version_control.git
Создаем новую ветку и вносим необходимые изменения в файл
git checkout -b updatereadme
vim README.md
git add README.md
git commit -m "Добавили инструкцию как создать pull request"
Делаем push
git push --set-upstream origin updatereadme
Переходим на свою страницу репозитория. Выбираем ветку updatereadme и жмем кнопку Compare & pull request

Далее добавили текст через браузер.

Добавили текст локально.

Добавили текст в новой ветке new_branch

<<<<<<< HEAD
Добавил локальный конфликт
=======
Решаем конфликт в версии браузера

>>>>>>> 18a53f539bf9ff47ec73786932a8b9877962ad70
