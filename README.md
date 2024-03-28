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
SECRET_KEY="admin"  (ключ для входа в панель администрации)
```

5. Запустить приложение в Prod

```
npm run start:prod
```

6. Ссылка на хостинг сайта

http://217.25.92.196:3000/ (главная страница)
http://217.25.92.196:3000/admin/login (вход в панель администратора)
