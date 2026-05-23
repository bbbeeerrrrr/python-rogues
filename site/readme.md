# Веб-страница проекта
![](overall_screenshot.png)

**Автор: Головко Макар ([sibin57](https://github.com/sibin57))**


В данной папке хранится исходный код статичной веб-страницы проекта

## Запуск страницы

Чтобы просмотреть страницу, есть два варианта:
* перейдите по ссылке на уже готовую страницу: <https://bbbeeerrrrr.github.io/python-rogues/>
* самостоятельно поднять сервер hugo (описано далее)

Для запуска веб-сервера необходим Hugo **Extended** v0.90.x.

Для запуска сервера перейдите в папку web, и выполните команду 

```bash
$ hugo server
```
затем  перейдите по адресу, который вам напишет программа (*по умолчанию localhost:1313*)

## Структура сайта

Структура сайта выглядит следующим образом

- [главная страница](https://bbbeeerrrrr.github.io/python-rogues/)
	+ ["о проекте"](https://bbbeeerrrrr.github.io/python-rogues//about/) 
	+ [участники и их вклад](https://bbbeeerrrrr.github.io/python-rogues/contributors/)
	+ [блог о ходе разработки](https://bbbeeerrrrr.github.io/python-rogues//posts/)
	+ [ресурсы (ссылки на источники)](https://bbbeeerrrrr.github.io/python-rogues/links/)

# Использованные источники
Для создания страницы использовался генератор статичных веб-страниц [hugo](https://gohugo.io) и визуальная тема [terminal](https://github.com/panr/hugo-theme-termina)
