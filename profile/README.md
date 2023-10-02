# О проекте:
Платформа для коротких видео с открытым исходным кодом

# Roadmap:
  - [x] Сервис авторизации и аутентификации с использованием JWT (Spring Security)
    - [x] Регистрация новых пользователей
    - [x] Аторизация и выпуск JWT токена
  - [x] ChannelService
    - [x] Информация о пользователе
    - [x] Ресурсы пользователя (медиа), хранятся в MinIO
      - [x] Создание presignedUrl для авторизированного клиентского доступа к ресурсам в MinIO
      - [ ] Взаимодействие с сервисом обработки Media (Spring for Apache Kafka)
  - [ ] Notification Service
  - [ ] Video Service
  - [ ] Activity Service
  - [ ] Recomendation Service
  - [ ] Использование Nginx для возможности взаимодействия с MinIO изнутри и извне локальной сети

# Стек:
- Java SE 17
- Spring (Core, Boot, Web, MVC, Security, Spring for Apache Kafka)
- Minio
- PostgreSQL
- Lombok
- JJWT
- JUnit
- Docker, Docker Compose
- Nginx
- GitHub Actions, GitHub Container Registry

