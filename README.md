Домашнее задание N01
====================
от *23.10.2021*

Задача 1
--------
**Terraform**
![Terraform](/terraform.png)

**Bash**
![Bash](/bash.png)

**Markdown**
![Markdown](/markdown.png)

**Yaml**
![Yaml](/yaml.png)

**Jsonnet**
![Jsonnet](/jsonnet.png)

Задача 2
--------
**Жизненный цикл задачи**

1. Согласуем/дорабатываем совместно с заказчиком ТЗ на новую фичу и сроки посредством менеджера.
2. Менеджер уточняет выполнимость ТЗ и сроков с разработчиками. Если возникли вопросы - возвращаемся к пункту 1.
3. Разработчики будят DevOps`а
4. DevOps совместно с разработчиками предварительно оценивает потребные ресурсы и инструментарий для решения задачи.
5. DevOps подбирает оптимальную конфигурацию системы для решения задачи, прикидывает уровни доступа людей и машин друг к другу.
6. DevOps разворачивает потребную для разработчиков инфраструктуру (рабочие станции, сервисы, тестовые "песочницы"). Если у разработчиков возникают вопросы - возвращаемся к пункту 4.
7. Разработчики начинают писать код новой фичи.
8. С появлением первых работающих строк кода разработчики привлекают к делу QA-команду и DevOps`а, дабы львиная доля новых тестов шла автоматом и на выделенных под это дело тестовых серверах.
9. Если возникают проблемы в коде, возврат к пункту 7.
10. Если фича готова и тесты пройдены, выложить бета-релиз на отдельный сервер для ознакомления представителя заказчика с результатами работы.
11. Если у заказчика возникли вопросы и/или пожелания по внедряемой фиче - возвращаемся к пункту 1.
12. Если вопросов нет - выкладываем релиз в продакшен.
13. У заказчика возникли новые идеи и пожелания - переходим к пункту 1.

P.S. Возможно, я сильно неправ, но я сисадмин и опыт программирования у меня исключительно в одиночку - когда ты и программист, и QA, и менеджер, и всё остальное.
