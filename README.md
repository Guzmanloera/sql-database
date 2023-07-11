# sql-database
  Урок 1. Установка СУБД, подключение к БД, просмотр и создание таблиц
Создайте таблицу с мобильными телефонами, используя графический интерфейс. Заполните БД данными (поля и наполнение см. в презентации)
Выведите название, производителя и цену для товаров, количество которых превышает 2
Выведите весь ассортимент товаров марки “Samsung”

Урок 2. SQL – создание объектов, простые запросы выборки
Используя операторы языка SQL, создайте табличку “sales”. Заполните ее данными.
Для данных таблицы “sales” укажите тип заказа в зависимости от кол-ва : меньше 100 - Маленький заказ; от 100 до 300 - Средний заказ; больше 300 - Большой заказ.
Создайте таблицу “orders”, заполните ее значениями. Выберите все заказы. В зависимости от поля order_status выведите столбец full_order_status: OPEN – «Order is in open state» ; CLOSED - «Order is closed»; CANCELLED - «Order is cancelled»
Чем NULL отличается от 0?

Урок 3. SQL – выборка данных, сортировка, агрегатные функции
Работаем с таблицей staff (скрипт создания в материалах к уроку)
1. Отсортируйте данные по полю заработная плата (salary) в порядке: убывания; возрастания
2. Выведите 5 максимальных заработных плат (salary)
3. Посчитайте суммарную зарплату (salary) по каждой специальности (роst)
4. Найдите кол-во сотрудников с специальностью (post) «Рабочий» в возрасте от 24 до 49 лет включительно.
5. Найдите количество специальностей
6. Выведите специальности, у которых средний возраст сотрудников меньше 30 лет
