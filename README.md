<!----- Conversion time: 1.115 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Wed Sep 18 2019 01:01:48 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=1sIorEva0JHPGjUlZBihoiGIootksj8HqQUjW8Vota0c
----->
## 3. Работа с удаленными репозиториями и GitHub


### Цель работы

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.


### Задания для выполнения



1. Зарегистрироваться на сайте github.com
2. Установить на компьютере программу Git
3. Форкнуть данный репозиторий в свой аккаунт
4. Склонировать созданный удаленный репозиторий в директорию ~/git/test
![image](https://user-images.githubusercontent.com/70855182/138612497-f2b8685e-5010-4b37-9f75-e97f3b6d1246.png)

5. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием

![image](https://user-images.githubusercontent.com/70855182/138612744-b8508c1d-9ee7-4762-bf87-a7b557cde4ba.png)

7. Фиксируем скрипт в репозитории (делаем коммит)

![image](https://user-images.githubusercontent.com/70855182/138612942-d80c5df8-d770-4001-bfbc-e22f29ae11e0.png)
![image](https://user-images.githubusercontent.com/70855182/138612954-4d0a863c-9571-4fa0-8f98-ddae7f38bcec.png)

9. Обновляем удаленный репозиторий репозиторий (делаем пуш)

![image](https://user-images.githubusercontent.com/70855182/138613954-45340dc4-f976-4d4a-a394-534f6379ce8d.png)

11. Через текстовый редактор добавить любую новую строку с комментарием

![image](https://user-images.githubusercontent.com/70855182/138613960-b9dcd3fa-380f-47c1-b90e-e7bd248e66dc.png)

13. Сделать коммит

![image](https://user-images.githubusercontent.com/70855182/138613968-bb7db613-f6dc-4737-936b-2fd79369df76.png)

15. Вности синтаксическую ошибку в скрипт

![image](https://user-images.githubusercontent.com/70855182/138613977-04a1fdbe-235a-4c9c-a31f-49b1aeb8680c.png)

17. Сделать коммит ошибочного скрипта

![image](https://user-images.githubusercontent.com/70855182/138613986-bd193671-b1b9-48e8-bc76-da9dc4a87c98.png)

19. Откатываем до последней рабочей версии

![image](https://user-images.githubusercontent.com/70855182/138613992-d8765b57-edae-44c6-b35f-a99a885a79ab.png)
![image](https://user-images.githubusercontent.com/70855182/138614000-222ec396-945e-4597-94e9-2a3961b82a49.png)

21. Просмотреть историю коммитов

![image](https://user-images.githubusercontent.com/70855182/138614007-d0d41b1f-d0ae-4105-9c2b-68e47cf28113.png)


23. Добавить несколько коммитов произвольного содержимого

![image](https://user-images.githubusercontent.com/70855182/138614135-ed33fdee-45f7-4933-921f-0ed9a7ca53e5.png)
![image](https://user-images.githubusercontent.com/70855182/138614169-7f4a202a-53b0-4dd3-a06b-94da94f01643.png)

25. Создать пулл реквест в данный репозиторий


### Контрольные вопросы



1. Зачем нужен облачный хостинг репозиториев?

   Облачный хостинг репозиториев необходим, чтобы к репозиторию имели доступ сразу несколько человек.
2. Какими основными функциями обладает сайт github.com?

   Сайт github.com позволяет загружать репозитории, клонировать их, делать ответвления, делиться репозиториями.
3. Как организовать командную работу над открытым проектом?

   В главное ветке main находится основная рабочая версия. Из главного репозитория разработчики могут делать ответвления и работать над определенной частью проекта. Когда работа закончена, делается пулл реквест в ветку main для последующего слияния или корректировки. 


3. Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.

![image](https://user-images.githubusercontent.com/70855182/138615145-8176c5b7-11a0-4a69-b46f-f0496140ba18.png)
![image](https://user-images.githubusercontent.com/70855182/138615177-f6eab261-57a3-4db4-8375-6525bec91682.png)
![image](https://user-images.githubusercontent.com/70855182/138615202-0b47c062-2e49-4de2-96e7-5ca7d0060949.png)

<!-- Docs to Markdown version 1.0β17 -->
