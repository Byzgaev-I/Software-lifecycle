# Домашнее задание "Жизненный цикл ПО"   

---

### Подготовка к выполнению

Получить бесплатную версию Jira.  
Настроить её для своей команды разработки.  
Создать доски Kanban и Scrum.  
Дополнительные инструкции от разработчика Jira.  

### Основная часть

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:  
  
Open -> On reproduce.  
On reproduce -> Open, Done reproduce.  
Done reproduce -> On fix.  
On fix -> On reproduce, Done fix.  
Done fix -> On test.  
On test -> On fix, Done.  
Done -> Closed, Open.  
  
Остальные задачи должны проходить по упрощённому workflow:  
  
Open -> On develop.  
On develop -> Open, Done develop.  
Done develop -> On test.  
On test -> On develop, Done.  
Done -> Closed, Open.  
Что нужно сделать:  

1) Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done.  
2) Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done.  
3) При проведении обеих задач по статусам используйте kanban.  
4) Верните задачи в статус Open.  
5) Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.  
6) Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.  

### Выполнение задания:

Зарегистровался в Jira.  
Создал доски Kanban и Scrum.  

Создание Workflow для Bug:  
Задачи типа bug должны проходить жизненный цикл:  
  
Open -> On reproduce.    
On reproduce -> Open, Done reproduce.    
Done reproduce -> On fix.  
On fix -> On reproduce, Done fix.  
Done fix -> On test.  
On test -> On fix, Done.  
Done -> Closed, Open.  






































