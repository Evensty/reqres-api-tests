## Проект API автотестов reqres.in
### Используемые технологии
<p  align="center">
<code><img width="5%" title="Pycharm" src="images/logo/pycharm.png"></code>
  <code><img width="5%" title="Python" src="images/logo/python.png"></code>
  <code><img width="5%" title="Pytest" src="images/logo/pytest.png"></code>
  <code><img width="5%" title="Requests" src="images/logo/requests.png"></code>
  <code><img width="5%" title="GitHub" src="images/logo/github.png"></code>
  <code><img width="5%" title="Jenkins" src="images/logo/jenkins.png"></code>
  <code><img width="5%" title="Allure Report" src="images/logo/allure_report.png"></code>
  <code><img width="5%" title="Allure TestOps" src="images/logo/allure_testops.png"></code>
  <code><img width="5%" title="Telegram" src="images/logo/tg.png"></code>
</p>
<br> 

<!-- Тест кейсы -->

### Что проверяют тесты
API:
![This is an image](images/screenshots/api_tests.png)
WEB:
![This is an image](images/screenshots/web_tests.png)

WEB тесты - это тесты для демонстрации гибридных тестов WEB и API.
В WEB тестах используется API для авторизации, создание и удаление сущностей.
![This is an image](images/screenshots/api_web.png)

В проекте используется встроенный logger - logging:
![This is an image](images/screenshots/logger.png)

<!-- Jenkins -->

### <img width="3%" title="Jenkins" src="images/logo_stacks/jenkins.png"> Запуск проекта в Jenkins
### [Job](https://jenkins.autotests.cloud/job/Maxim_Veselov11-reqres-api-tests/)
##### При нажатии на "Собрать сейчас" начнется сборка тестов и их прохождение на сервере jenkins.
![This is an image](images/screenshots/jenkins.png)

Также мы можем посмотреть выполнение тестов в консоли перейдя во вкладку "Вывод консоли" у определенного билда
![This is an image](images/screenshots/console.png)

<!-- Allure report -->

### <img width="3%" title="Allure Report" src="images/logo/allure_report.png"> Allure report
##### После прохождения тестов, результаты можно посмотреть в Allure отчете, где так же содержится ссылка на Jenkins.
![This is an image](images/screenshots/allure_report.png)

##### Во вкладке Graphs можно посмотреть графики о прохождении тестов, по их приоритезации, по времени прохождения и др.
![This is an image](images/screenshots/graphs.png)

##### Во вкладке Suites находятся собранные тест кейсы, у которых описаны шаги.
![This is an image](images/screenshots/suites.png)


<!-- Allure TestOps -->

### <img width="3%" title="Allure TestOps" src="images/logo_stacks/allure_testops.png"> Интеграция с Allure TestOps
### [Dashboard](https://allure.autotests.cloud/project/2025/dashboards)
##### Так же вся отчетность сохраняется в Allure TestOps, где строятся аналогичные графики.
![This is an image](images/screenshots/allure_testops_dashboard.png)

#### Во вкладке со сьютами, мы можем:
- Управлять всеми тест-кейсами или с каждым отдельно
- Перезапускать каждый тест отдельно от всех тестов
- Добавлять ручные тесты

![This is an image](images/screenshots/allure_testops_suites.png)

Во вкладке Launches мы можем видить тестовые прогоны:
![This is an image](images/screenshots/allure_testops_launcher.png)


<!-- Telegram -->

### <img width="3%" title="Telegram" src="images/logo_stacks/tg.png"> Интеграция с Telegram
##### После прохождения тестов, в Telegram bot приходит сообщение с графиком и небольшой информацией о тестах.

![This is an image](images/screenshots/tg.png)