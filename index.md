# Основные команды GIT

# Инициализация нового репозитория 

Откройте консоль MINGW, войдите в папку с файлами проекта и наберите команду
```
    git init
```

# Добавление файла в коммит

Создайте файл с нужным содержимым и введите команду 
```
    git add <filename>
```
# Добавление коммита

После после добавление файла в коммит введите команду
```
    git commit -m "message"
```

# Статус директории

Чтобы посмотреть статус файлов в рабочей директории введите команду
```
    git status
```

# Просмотр сохраненных коммитов 

Чтобы посмотреть список сохраненных коммитов введите команду 
```
    git log
```

# Переход между коммитами 

Для перехода к одному из раннее сохраненных коммитов введите в консоль
```
    git checkout <commit number>
```

# Возвращение к актуальному состоянию репозитория

Чтобы вернуться к актуальному состоянию файла введите команду
```
    git checkout master
```

# Коммит изменений 

После добавления всех файлов в коммит нужно ввести команду
```
    git commit -m "<commit message>"
```

# Создание новой ветки

Для создания новой ветки нужно ввести команду
```
    git branch <branch name>
```

# слияние веток 

Для слияния текущей ветки с другой веткой нужно ввести команду
```
    git merge <branch name>
```

# Перенос изменений из данной ветки на верх текущей ветки

Для такого переноса нужно перейти на ветку, куда переносим изменения (например master) и вызвать команду 
```
    git rebase <branch name>
```

# Клонирование репозитория

Для клонирования репозитория нужно ввести команду 
```
    git clone <url to repository>
```

# Сброс изменений

Для сброса изменений в текущей ветке введите команду 
```
    git reset
```