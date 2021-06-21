# 🧪 Team 1 — URL Shortener 🧪
## Команда

- Ширли Акоста - shirleyacosta5@gmail.com - SHPATRI

## Дизайн документ

https://cutt.ly/UzT9k3a

### Структура приложения

Приложение состоит из нескольких модулей

- `auth` **модуль аутентификации** - отвечает за аутентификацию пользователей в системе. Вам необходимо дописать логику
  проверки токена.
- `dto` — содержит описания объектов для передачи данных внутри системы
- `logic` **бизнес логика приложения** — логика сокращения ссылок и др. Необходимо реализовтаь
- `storage` **хранилище данных** — реализация хранилища, которое будет хранить ссылки, пользователей, токены...
  Необходимо реализовать. Обратите внимание, что в рамках этого курса вам нельзя использовать готовые решения, как,
  например, базы даных.
- `views` **REST API** — модуль, в котором находятся все контроллеры приложения. В проекте вы будете использовать
  фреймворк [Micronaut](https://micronaut.io), который упрощает создание REST API.

## Среда разработки

### Java

Проект вы реализуете на языке `Java`, поэтому вам нужно
поставить [JDK](https://ru.wikipedia.org/wiki/Java_Development_Kit) 15. Для установки вы можете использовать:

- [sdkman](https://sdkman.io/) на системах с Linux/MacOS
- [AdoptOpenJDK](https://adoptopenjdk.net/) на ситемах с Windows

**К сожалению, пока что не все инструменты поддерживают последнюю версию Java (JDK 16), которая вышла буквально пару
недель назад, поэтому важно установить именно JDK 15 версии. Версию для Windows можно найти по
ссылке [AdoptOpenJDK Archive](https://adoptopenjdk.net/archive.html)**

### IDE

Для разработки рекомендуется использовать [IntelliJ IDEA Edu](https://www.jetbrains.com/idea-edu/)

### Взаимодействие с REST API

Для взаимодействия с REST API можно использовать следующие инструменты:

- [Postman](https://www.postman.com/downloads/)
- [Insomnia](https://insomnia.rest/) — чуть более простая альтернатива Postman

и другие на ваше усмотрение
