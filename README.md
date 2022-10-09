## Api Absensi Lab

Simple CRUD API for laboratorium absence system.

## Installation

clone this project

```bash
git clone https://github.com/hiseulgi/api-absensi-lab.git
```
copy .env.example to .env

```bash
cp .env.example .env
```

install composer

```bash
composer install
```

generate key

```bash
php artisan key:generate
```

migrate database

```bash
php artisan migrate
```

## Usage

run server

```bash
php artisan serve
```

## API Endpoint

### User
- GET All   : `http://127.0.0.1:8000/api/user`
- GET by id : `http://127.0.0.1:8000/api/user/{id}`
- POST      : `http://127.0.0.1:8000/api/user/`
- PUT       : `http://127.0.0.1:8000/api/user/{id}`
- DELETE    : `http://127.0.0.1:8000/api/user/{id}`

### Absensi
- GET All   : `http://127.0.0.1:8000/api/absensi`
- GET by id : `http://127.0.0.1:8000/api/absensi/{id}`
- POST      : `http://127.0.0.1:8000/api/absensi/`
- PUT       : `http://127.0.0.1:8000/api/absensi/{id}`
- DELETE    : `http://127.0.0.1:8000/api/absensi/{id}`