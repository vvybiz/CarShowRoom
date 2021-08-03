# CarShowRoom (WPF)

Тестовое задание:
Для принятия стратегических решений автомобильному дилеру требуется получить представление об объемах продаж. Дилер продает автомобили разных марок, моделей, цветов и комплектаций.

Требуется:
•	спроектировать таблицы БД
•	подготовить тестовые данные для не менее чем 1000 заказов за 5 лет
•	разработать приложение с использованием WPF для отображения суммы продаж каждой модели за выбранный год
•	предусмотреть возможность экспорта в Excel

Сборка тестового задания:	
1.	Предоставлен архив CarShowRoom.zip, он содержит следующие файлы:
CarShowRoom - create objects.sql – SQL запрос для создания БД на MS SQL Server;
CarShowRoom - create procedure.sql - SQL запрос для создания необходимой процедуры;
CarShowRoom - load data.sql - SQL запрос для заполнения данными БД;
CarShowRoom - drop all objects.sql - SQL запрос для удаления созданных объектов;
Папка WpfCarShowRoom содержит разработанную программу C# 

2.	Сборка тестового задания:
Запускаем SQL Server Management Studio, создаем базу данных с наименованием CarShowRoom.
Запускаем: 1.CarShowRoom - create objects.sql; 2.CarShowRoom - create procedure.sql; 3.CarShowRoom - load data.sql; для заполнения БД необходимыми данными.
Запускаем проект WpfCarShowRoom.sln и изменяем строку подключения к базе данных
(string connectionString = "Data Source=_______; Initial Catalog=CarShowRoom; Connect Timeout=15; Integrated Security=True"; ), сохраняем и собираем проект.

3.	Запускаем собранное приложение CarShowRoom:
Выбираем необходимой год для отчета, запускаем отчет, сохраняем данные в Excel 
				

