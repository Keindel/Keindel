### Привет 👋
Я Андрей, Java-разработчик.  
- 🔭 Рассматриваю предложения о работе
- 🌱 Изучаю Алгоритмы и Структуры данных
- 📫 Связаться со мной в telegram: @andmaksimov
- ⚡ Fun fact: победитель всех танцевальных конкурсов на свадьбах друзей 🔥💃

### Примеры реализованных мной проектов:  
✅ 1. Explore With Me (https://github.com/Keindel/java-explore-with-me).  
Бэкенд приложения ExploreWithMe (англ. «исследуй со мной»). Дает возможность делиться информацией об интересных событиях и помогает найти компанию для участия в них.  
Приложение является афишей, где можно предложить какое-либо событие и набрать компанию для участия в нём.  
API разделено на 3 уровня: публичный, для зарегистрированных пользователей и административный.  
Проект состоит из двух микросервисов: основной сервис и сервис статистики. Отдельная PostgreSQL база данных для каждого сервиса, для работы с ними используется ORM фреймворк JPA Hibernate. Сервисы находятся в отдельных docker-контейнерах. Запуск приложения реализован с помощью docker-compose.  
**Стек**: REST API service with Spring-Boot, JPA Hibernate, PostgreSQL, Java 11, Lombok, Docker, Swagger.

✅ 2. ShareIt (https://github.com/Keindel/java-shareit).  
Шеринг-приложение для вещей.  
- предлагайте свой инструмент, снаряжение и любые другие вещи, которые вы готовы дать в аренду;  
- находите и берите полезные вам вещи, предложенные другими пользователями;  
- спрашивайте советы по использованию у владельца вещи и наслаждайтесь вашим опытом.  
Проект имеет микросервисную архитектуру. Запуск приложения реализован с помощью docker-compose. Реализованы Unit тесты c Mockito и интеграционные с mockMvc.  
**Стек**: REST API service with Spring-Boot, JPA Hibernate, PostgreSQL, Java 11, Lombok, Junit, MockMVC, Docker.

✅ 3. Filmorate (https://github.com/Keindel/java-filmorate).  
Соцсеть с рейтингом фильмом, основанном на оценках от пользователей. Пользователи могут добавлять друг друга в друзья.  
Работа с БД реализована с помощью JdbcTemplate.  
Дополнительный функционал, реализованный за время командной работы: пользователи могут делать ревью, лайкать, дизлайкать, получать сортировку фильмов по рейтингу; просмотр последних событий на платформе; найти фильмы по режиссеру и сортировать по году/ по лайкам; поиск фильмов по названию и/или режиссеру; система рекомендаций основанная на анализе пользователей с похожими предпочтениями и числе лайков; выполнен рефакторинг лайков в оценки, актуализирована выдача по рейтингу и популярности,
реализована новая система рекомендаций на основе анализа оценок и похожих пользователей.  
**Стек**: REST API service with Spring-Boot, Jdbc, H2-database, Java 11, Lombok, Junit.

<!--
**Keindel/Keindel** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
