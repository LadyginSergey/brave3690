# Подсказки по командной строке

Команда смены директории
```sh
cd "C:\Users\User\Desktop\study\git"
```
Команда отображения текущей директории Mac0s, Linux
```sh
pwd
```

Листинг текущей директории Windows:
```sh
dir
```
Linux, Mac0s:
```sh
ls
```

Удаление файла в windows
```sh
del <filename>
```

в Linux, Mac0s:
```sh
rm <filename>
```

Показывает историю изменений
```sh
git log
```
Ключ --graph для log


Показывает последние изменения
```sh
git diff
```

Отображение всех веток
```sh
git branch
```

Перемещение по веткам
```sh
git chekout <branch_name>
```


объединить ветки
```sh
git merge
```


<<<<<<< HEAD
Удаление определенной ветки
```sh
git branch -d <имя ветки>
```
отправить изменения в удаленный репозиторий
```
git push
```

Клонирования ветки по ссылке
```
git clone "ссылка на гитхаб"
```

Выполняет выборку, а затем слияние или перебазировку для интеграции извлекаемых фиксаций в текущую локальную ветвь.
```
Git pull
```