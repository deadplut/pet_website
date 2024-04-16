# pet_website



## Установка и запуск проекта


### Команды для создания ssh ключа
1. при вызове первой команды заменить your_email@example.com на твой email
2. При вызове 1 команды по умолчанию задать, где хранить ssh ключ, (задать пароль какой хочешь) 
3. 3-я команда выведет ssh ключ, скопируй и отправь его мне

```bash
ssh-keygen -t rsa -b 4096 -C your_email@example.com          
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
```

### копирование проекта
```bash
git clone git@github.com:deadplut/pet_website.git
```

### Подготовка окружения и установка зависимостей.

```bash
python3.12 -m venv .venv
source .venv/bin/activate
```

### Следующие команды выполняются для установки зависимостей
```(.venv) $ 
pip install -U pip
pip install -r requirements.txt
```

### Запуск сайта
```(.venv) $ 
./manage.py runserver
```


## Словарь терминов:

bash - терминал

(.venv) - виртуальное окружение

### Команды Git для постоянного пользования

```bash
git pull                                        # для загрузки из удаленного репозитория обновлений
git commit -a -m'Комментарий к коммиту'         # создание сохранения с комментарием к нему
git push                                        # загрузка сохранений в онлайн
```

