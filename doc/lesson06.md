# Занятие 6 онлайн проекта <a href="https://github.com/JavaWebinar/topjava05">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfkF5c1hiWmstT0prODdtZkVuNFlMZmdtN3J0OUcyY0lkT2NlVzlUMXRUUlk">Материалы урока</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUVZobXRzNWFzUW8">HW5: Spring Profiles. Spring Data JPA</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFV3RPZGY2V292SXc">1_ HW5_ data_ jpa.patch</a>**
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFejJ4Ykt1UzZjMnc">2_ HW5_ profiles.patch</a>**
> Для IDEA не забудте выставить Spring Profiles в `spring-db.xml`: нарпимер `datajpa, postgres`
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcVhwUTFlVDhBcEk">3_ HW5_ tests.patch</a>**
> Изменение в проекте: `DbTest` переименован в `AbstractServiceTest` и сюда перенесли `@ActiveProfiles(POSTGRES)`

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFejhtNkI0RGpVd1E">HW5: Optional</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFckpUNmJUSkp0b28">4_ HW5_ Optional_ fix_ servlet_ main.patch</a>**
-  <a href="http://javarticles.com/2013/12/spring-profiles.html">Spring Profiles</a>

-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFWkl2Uk0wWmVWcm8">5_ HW5_ Optional_ fetch_ join.patch</a>**
-  <a href="http://stackoverflow.com/questions/11938253/jpa-joincolumn-vs-mappedby">JPA JoinColumn vs mappedBy</a>
-  <a href="https://en.wikibooks.org/wiki/Java_Persistence/OneToMany#Unidirectional_OneToMany.2C_No_Inverse_ManyToOne.2C_No_Join_Table_.28JPA_2.0_ONLY.29">Unidirectional OneToMany</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFeTV0SUFfblk5NE0">Кэш Hibernate</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFSnZucnhwTG1GX3c">6_ hibernate_ cache.patch</a>**
>  JdbcUserServiceTest поломася. Требуется починить в ДЗ

-  <a href="http://habrahabr.ru/post/135176/">Уровни кэширования Hibernate</a>
-  <a href="http://habrahabr.ru/post/136375/">Hibernate Cache. Практика</a>
-  <a href="http://www.tutorialspoint.com/hibernate/hibernate_caching.htm">Hibernate - Caching</a>
-  Починка тестов: <a href="http://stackoverflow.com/questions/1603846/hibernate-2nd-level-cache-invalidation-when-another-process-modifies-the-databas">инвалидация кэша Hibernate</a>
-  Ресурсы:
   -  Подключение <a href="http://www.ehcache.org/generated/2.9.0/html/ehc-all/#page/Ehcache_Documentation_Set%2Fco-hib_about_using_ehcache_with_hibernate.html%23wwconnect_header">кэша Hibernate 2-го уровня</a>
   -  <a href="http://stackoverflow.com/questions/3663979/how-to-use-jpa2s-cacheable-instead-of-hibernates-cache">JPA2 @Cacheable vs Hibernate @Cache</a>
   -  <a href="http://habrahabr.ru/post/25140/">Распределённая система кеша ehcache</a>
   -  <a href="http://docs.jboss.org/hibernate/orm/4.3/manual/en-US/html_single/#performance-cache-mapping">Cache mappings</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVE1jWkRucm1UTjA">Spring Web</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFTnhDZGM4Z3Nxbnc">7_ spring_ web.patch</a>**

-  Добавляем в проект веб зависимости
-  Поднятие контекста Spring в веб приложении. <a href="http://www.mkyong.com/servlet/what-is-listener-servletcontextlistener-example/">ServletContextListener</a>. Задание дефолтного профиля.
-  Получение контекста Spring в веб-контейнере
-  Ресурсы:
   -  <a href="https://docs.oracle.com/javaee/6/tutorial/doc/bnafi.html">Servlet Lifecycle</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFN3k0ZVk1MnF5TjQ">JPS, JSTL, internationalization</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFMHRhNWc5NGxtdlk">8_ jsp_ jstl_ i18n.patch</a>**
-  <a href="http://www.java2ee.ru/jsp/include.html">jsp:include</a>
-  Имплементируем UserController. <a href="http://design-pattern.ru/patterns/mvc.html">Паттерн MVC</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLTB3R3pKNFNEQmM">Динамическое изменение профиля при запуске.</a>
>  -Dspring.profiles.active="datajpa,postgres"

- <a href="http://stackoverflow.com/questions/10041410/default-profile-in-spring-3-1#answer-10041835">Set profiles in Spring 3.1</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdkFRRFdYa0NoWkU">Конфигурирование Tomcat через maven plugin. Jndi-lookup.</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFM0diMHlDNmozZEE">9_ tomcat_ pool_ jndi.patch</a>**

- <a href="https://tomcat.apache.org/maven-plugin-2.0/tomcat7-maven-plugin/">Tomcat Maven Plugin</a>
- <a href="https://tomcat.apache.org/tomcat-7.0-doc/jndi-resources-howto.html"/>Tomcat JNDI Resources</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQThUX2VyQXNiTHM">Spring Web MVC</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLWp2bWZnNElEc2s">10 spring webmvc.patch</a>**

-  <a class="anchor" id="mvc"></a><a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html">Spring Web MVC</a>
-  <a href="http://design-pattern.ru/patterns/front-controller.html">Паттерн Front Controller</a>
-  Добавляем DispatcherServlet и MVC application context.
-  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/integration-testing.html#testcontext-ctx-management-ctx-hierarchies">Иерархия контекстов в Spring Web MVC</a>
-  <a href="http://www.tutorialspoint.com/spring/spring_web_mvc_framework.htm">Сценарий обработки запроса</a>. <a href="http://www.studytrails.com/frameworks/spring/spring-mvc.jsp">HandlerMappings</a>
-  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html#mvc-viewresolver-resolver">View resolving</a>: прячем jsp под WEB-INF.
-  HandlerMapping: <a href="http://www.mkyong.com/spring-mvc/spring-mvc-simpleurlhandlermapping-example/">SimpleUrlHandlerMapping</a>, <a href="http://www.mkyong.com/spring-mvc/spring-mvc-beannameurlhandlermapping-example/">BeanNameUrlHandlerMapping</a>
-  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html#mvc-config-static-resources">Маппинг ресурсов.</a>
-  Ресурсы:
   -  <a href="http://www.jpalace.org/document/34/spring-mvc-tutorial">Spring MVC Tutorial</a>
   -  <a href="http://devcolibri.com/120">Spring MVC — Hello world</a>
   -  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html">Web MVC framework</a>
   -  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html#mvc-webappctx-special-beans-tbl">Special bean types in the WebApplicationContext</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUEctTkRSMWNvRjg">Spring Internationalization</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdWtIbWNseEJXNGM">11 spring i18n.patch</a>**

-  <a href="http://simplespringtutorial.com/i18n.html">Spring Internationalization or i18n</a>
-  <a href="http://learningviacode.blogspot.ru/2012/07/reloadable-messagesources.html">Reloadable MessageSources</a>
-  <a href="http://nginx.com/resources/admin-guide/serving-static-content/">nginx: Serving Static Content</a>

## Домашнее задание HW06
    Починить InMemory и Jdbc тесты
    Добавить локализацию и jsp:include в meal*.jsp
    Починить работу meals:
    перенести функциональность MealServlet в контроллеры, разнести запросы на update/delete/.. по разным методам

Optional

    Добавить еще одну роль к ADMIN (будет 2 роли: ROLE_USER, ROLE_ADMIN)
    Добавить проверку ролей в тесты на User 
    Починить тесты Jpa
    Добавить транзакционность (DataSourceTransactionManager) и доставание ролей в JdbcUserRepositoryImpl

## Ваши вопросы
>  Кэш hibernate надстраивается над ehcache или он живет самостоятельно?

- <a href="http://mrbool.com/understanding-hibernate-caching/28721">Understanding Hibernate Caching</a>:
Hibernate supports following open-source cache implementations out-of-the-box: EHCache (Easy Hibernate Cache), OSCache (Open Symphony Cache), Swarm Cache, and JBoss Tree Cache.

> Где конфигурится интернализация для jstl? Т.е. файл, где здаются app, app_ru.properties. Достаточно указать в страницах бандл и путь в ресурсы?

`<fmt:setBundle basename="messages.app"/>` означает что ресурсы будут искаться в `classpath:messages\app(_xx)/properties`:
<a href="http://docs.oracle.com/javaee/5/jstl/1.1/docs/tlddocs/fmt/setBundle.html">Tag setBundle</a>: fully-qualified resource name, which has the same form as a fully-qualified class name.
После сборки проекта maven их можно найти в target\classes или target\topjava\WEB-INF\classes.


> Отлично, что она все пишет на том языке, который пришел в хидере запроса. А если я хочу выбрать?

Используется <a href="http://www.codejava.net/java-ee/jstl/jstl-format-tag-setlocale">JSTL Format Tag fmt:setLocale</a>. Мы переключимся на Spring i18n и переключение локалей будет реализовано в нем.

> Мы создаем бин, где получаем dataSource по имени `<jee:jndi-lookup id="dataSource" jndi-name="java:comp/env/jdbc/topjava"/>`.
Но там не указан класс, как в других dataSource? Получается по имени jdbc/topjava нам уже отдает готовый обьект dataSource и мы как бы помещаем его в бин?

Здесь используется namespace `jee:jndi-lookup`, который прячет под собой классы реализации. Сравните в http://habrahabr.ru/post/232381/ раздел Spring namespace configuration инициализацию базы через namespace jdbc и через классы.

> В плагине прописан профиль `<spring.profiles.active>tomcat,datajpa</spring.profiles.active>`, а в web.xml `<param-value>postgres,datajpa</param-value>`.
Какой же реально отрабатывает?

См видео урока "Динамическое изменение профиля при запуске". В плагине мы задаем параметры JVM запуска Tomcat


> Почему мы не используем элемент `<context:annotation-config/>` в `spring-db.xml`?

В проекте у нас сейчас 2 Spring контекста: `spring-mvc.xml (см. web.xml, DispatcherServlet)` и родительский `spring/spring-app.xml + spring/spring-db.xml (web.xml, contextConfigLocation)`.
Грубо: 2 мапы, причем для mvc доступно все что есть в родителе. Те spring-db.xml не является отдельным самотоятельным контекстом и достаточно того, что `<context:annotation-config/>` у нас есть в `spring-app.xml`.