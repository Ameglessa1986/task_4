# <span style="color:red">Настройка Git</span>

У GIT есть настройка пользователя, от которого будет идти работа. Это разумная и необходимая вещь, так как когда создается коммит, GIT берет именно эту информацию для поля Author.

Чтобы настроить имя пользователя и пароль для всех проектов, нужно прописать следующие команды:

````
git config --global user.name ”Ivan Ivanov”
git config --global user.email ivan.ivanov@gmail.com
````

Если есть необходимость для конкретного проекта поменять автора, можно убрать --global, и так получится:

````
git config user.name ”Ivan Ivanov”
git config user.email ivan.ivanov@gmail.com
````

[<<Главное меню](./readme.md)
