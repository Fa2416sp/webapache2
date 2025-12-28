# webapache2

Минимальный и наглядный проект для развёртывания **Apache HTTP Server** в Docker.
Подходит для учебных целей, тестирования конфигураций Apache и быстрого деплоя статических сайтов.

---

## Описание проекта

`webapache2` — это простой Docker-проект, демонстрирующий работу Apache2 внутри контейнера.
Проект ориентирован на:
- обучение работе с Apache;
- понимание Docker и docker-compose;
- размещение статических сайтов (веб-визиток);
- использование как шаблон для будущих проектов.

---

## Структура проекта

```
webapache2/
├── docker-compose.yml
├── Dockerfile
├── htdocs/
│   └── index.html
├── README.md
```

---

## Требования

- Docker 20+
- Docker Compose v2+
- Linux / macOS / Windows (WSL)

---

## Быстрый старт

### Клонирование

```bash
git clone https://github.com/Fa2416sp/webapache2.git
cd webapache2
```

### Запуск

```bash
docker compose up -d --build
```

Открой в браузере: http://localhost:8080

---

## Веб-контент

Весь контент размещается в каталоге `htdocs/`.
Поддерживаются HTML, CSS, JavaScript и другие статические файлы.

---

## Управление

Остановка:
```bash
docker compose down
```

Логи:
```bash
docker compose logs -f
```

---

## Технологии

- Apache HTTP Server
- Docker
- Docker Compose

---

## Автор

https://github.com/Fa2416sp
