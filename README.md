## Project setup VueJS

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Project setup Laravel

```
composer install
```

### Copy file .env.example to .env

```
copy .env.example .env
```

```
Dengan cara manual, buat file baru dengan nama .env, buka file .env.example copy semua isi nya, lalu pastekan ke file .env
```

### Generate Key

```
php artisan key:generate
```

### Buat Database di phpMyAdmin

```
buat database di MySQL
lalu ubah nama database di file .env sesuai dengan nama database yang kamu buat

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=rental <-- ubah nama database disini
DB_USERNAME=root
DB_PASSWORD=

Jalankan
php artisan migrate
```

### Jalankan Serve
```
php artisan serve
```

```
Buka browser jalankan http://localhost:8000/sewa

Lakukan Register lalu login
```