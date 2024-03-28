# Миграция сервиса на Nest.js

## Инструкция по развертыванию на Node.js 18 LTS

1. Установить Nest js

```
npm i -g @nestjs/cli
```

2. Установить все бибилиотеки

```
npm install
```

3. Собрать приложение Nest

```
npm run build
```

4.  Создать файл .env в корне

```
PORT=3000
HOST="http://localhost:3000"
DB_NAME="store.db"
SECRET_KEY="dfhyw"  (абсолютно любой ключь для входа в панель администрации)
```

5. Запустить приложение в Prod

```
npm run start:prod
```

6. Ссылка на хостинг сайта

http://2760717-rt05646.twc1.net/ (главная страница)
http://2760717-rt05646.twc1.net/admin/login (вход в панель администратора)
