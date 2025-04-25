# Семёновых Екатерина Вячеславовна 6381 группа 26.04.2025
# **Итоговая контрольная работа**

 

 **Информация о проекте**

 Необходимо организовать систему учета для питомника в котором живут домашние и Pack animals.

 

**Как сдавать проект**

 

Для сдачи проекта необходимо создать отдельный общедоступный репозиторий(Github, gitlub, или Bitbucket). Разработку вести в этом репозитории, использовать пул реквесты на изменения. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно. Программа, может использоваться в различных системах, поэтому необходимо разработать класс в виде конструктора

 

# **Задание**

 

**Операционные системы и виртуализация (Linux)**

 

1\. Использование команды cat в Linux

   \- Создать два текстовых файла: "Pets"(Домашние животные) и "Pack animals"(вьючные животные), используя команду \`cat\` в терминале Linux. В первом файле перечислить собак, кошек и хомяков. Во втором — лошадей, верблюдов и ослов.

   \- Объединить содержимое этих двух файлов в один и просмотреть его содержимое.

   \- Переименовать получившийся файл в "Human Friends"(.

Пример конечного вывода после команды “ls” :

Desktop Documents Downloads  HumanFriends.txt  Music  PackAnimals.txt  Pets.txt  Pictures  Videos

 

2\. Работа с директориями в Linux

   \- Создать новую директорию и переместить туда файл "Human Friends".

 

3\. Работа с MySQL в Linux. “Установить MySQL на вашу вычислительную машину ”

   \- Подключить дополнительный репозиторий MySQL и установить один из пакетов из этого репозитория.

 

4\. Управление deb-пакетами

   \- Установить и затем удалить deb-пакет, используя команду \`dpkg\`.

 

5\. История команд в терминале Ubuntu

   \- Сохранить и выложить историю ваших терминальных команд в Ubuntu.

В формате: Файла с ФИО, датой сдачи, номером группы(или потока)

 

**Объектно-ориентированное программирование**

 

6\. Диаграмма классов

   \- Создать диаграмму классов с родительским классом "Животные", и двумя подклассами: "Pets" и "Pack animals".

В составы классов которых в случае Pets войдут классы: собаки, кошки, хомяки, а в класс Pack animals войдут: Лошади, верблюды и ослы).

Каждый тип животных будет характеризоваться (например, имена, даты рождения, выполняемые команды и т.д)

Диаграмму можно нарисовать в любом редакторе, такими как Lucidchart, Draw.io, Microsoft Visio и других.

 

7\. Работа с MySQL (Задача выполняется в случае успешного выполнения задачи “Работа с MySQL в Linux. “Установить MySQL на вашу машину”

 

7.1. После создания диаграммы классов в 6 пункте, в 7 пункте база данных "Human Friends" должна быть структурирована в соответствии с этой диаграммой. Например, можно создать таблицы, которые будут соответствовать классам "Pets" и "Pack animals", и в этих таблицах будут поля, которые характеризуют каждый тип животных (например, имена, даты рождения, выполняемые команды и т.д.).

7.2   \- В ранее подключенном MySQL создать базу данных с названием "Human Friends".

   \- Создать таблицы, соответствующие иерархии из вашей диаграммы классов.

   \- Заполнить таблицы данными о животных, их командах и датами рождения.

   \- Удалить записи о верблюдах и объединить таблицы лошадей и ослов.

   \- Создать новую таблицу для животных в возрасте от 1 до 3 лет и вычислить их возраст с точностью до месяца.

   \- Объединить все созданные таблицы в одну, сохраняя информацию о принадлежности к исходным таблицам.

 

Пример заполненной таблицы для теста:

Лист "Pets"

| ID | Name | Type | BirthDate | Commands |
| ----- | ----- | ----- | ----- | ----- |
| 1 | Fido | Dog | 2020-01-01 | Sit, Stay, Fetch |
| 2 | Whiskers | Cat | 2019-05-15 | Sit, Pounce |
| 3 | Hammy | Hamster | 2021-03-10 | Roll, Hide |
| 4 | Buddy | Dog | 2018-12-10 | Sit, Paw, Bark |
| 5 | Smudge | Cat | 2020-02-20 | Sit, Pounce, Scratch |
| 6 | Peanut | Hamster | 2021-08-01 | Roll, Spin |
| 7 | Bella | Dog | 2019-11-11 | Sit, Stay, Roll |
| 8 | Oliver | Cat | 2020-06-30 | Meow, Scratch, Jump |

 

 Лист "PackAnimals"

| ID | Name | Type | BirthDate | Commands |
| ----- | ----- | ----- | ----- | ----- |
| 1 | Thunder | Horse | 2015-07-21 | Trot, Canter, Gallop |
| 2 | Sandy | Camel | 2016-11-03 | Walk, Carry Load |
| 3 | Eeyore | Donkey | 2017-09-18 | Walk, Carry Load, Bray |
| 4 | Storm | Horse | 2014-05-05 | Trot, Canter |
| 5 | Dune | Camel | 2018-12-12 | Walk, Sit |
| 6 | Burro | Donkey | 2019-01-23 | Walk, Bray, Kick |
| 7 | Blaze | Horse | 2016-02-29 | Trot, Jump, Gallop |
| 8 | Sahara | Camel | 2015-08-14 | Walk, Run |

 

 

 

 

8\. ООП и Java

   Создать иерархию классов в Java, который будет повторять диаграмму классов созданную в задаче 6(Диаграмма классов) .

 

9\. Программа-реестр домашних животных

	Написать программу на Java, которая будет имитировать реестр домашних животных.

Должен быть реализован следующий функционал:

	

	9.1. Добавление нового животного

    	Реализовать функциональность для добавления новых животных в реестр.      

 Животное должно определяться в правильный класс (например, "собака", "кошка", "хомяк" и т.д.)

    	

 

   9.2. Список команд животного

    	\- Вывести список команд, которые может выполнять добавленное животное (например, "сидеть", "лежать").

    	

	9.3. Обучение новым командам

    	\- Добавить возможность обучать животных новым командам.

  9.4 Вывести список животных по дате рождения

 

9.5. Навигация по меню

    	\- Реализовать консольный пользовательский интерфейс с меню для навигации между вышеуказанными функциями.

    	

10\. Счетчик животных

Создать механизм, который позволяет вывести на экран общее количество созданных животных любого типа (Как домашних, так и вьючных), то есть при создании каждого нового животного счетчик увеличивается на “1”.

   
# Решение:

## 1-2 
```

 k@k-VirtualBox:\~$ cd Pitomnik/

k@k-VirtualBox:\~/Pitomnik$ cat \> Pets.txt

Собака

Кошка

Хомяк

k@k-VirtualBox:\~/Pitomnik$ cat \> PackAnimals.txt

Лошадь   	 

Верблюд

Оcел

k@k-VirtualBox:\~/Pitomnik$ cat Pets.txt PackAnimals.txt \> Animals.txt

k@k-VirtualBox:\~/Pitomnik$ cat Animals.txt

Собака

Кошка

Хомяк

Лошадь

Верблюд

Оcел

k@k-VirtualBox:\~/Pitomnik$ mv Animals.txt HumanFriends.txt

k@k-VirtualBox:\~/Pitomnik$ ls

HumanFriends.txt  PackAnimals.txt  Pets.txt  
k@k-VirtualBox:\~/Pitomnik$ mkdir PetsDirectory

k@k-VirtualBox:\~/Pitomnik$ mv HumanFriends.txt PetsDirectory/

k@k-VirtualBox:\~/Pitomnik$ cd PetsDirectory/

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ ls

HumanFriends.txt
```
## 3\. k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ sudo apt-get update
```
\[sudo\] пароль для k:

http://ru.archive.ubuntu.com/ubuntu jammy InRelease

http://ru.archive.ubuntu.com/ubuntu jammy-updates InRelease \[128 kB\]                                                      	 

http://repo.mysql.com/apt/ubuntu jammy InRelease                                                                          	 

http://security.ubuntu.com/ubuntu jammy-security InRelease \[129 kB\]                                                       	 

https://ppa.launchpadcontent.net/deadsnakes/ppa/ubuntu jammy InRelease                                   	 

http://ru.archive.ubuntu.com/ubuntu jammy-backports InRelease                                            	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages \[703 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages \[2 062 kB\]

http://security.ubuntu.com/ubuntu jammy-security/main i386 Packages \[544 kB\]             	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main Translation-en \[356 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 c-n-f Metadata \[17,8 kB\]	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/restricted amd64 Packages \[2 499 kB\]	 

http://security.ubuntu.com/ubuntu jammy-security/main amd64 Packages \[1 844 kB\]                      	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/restricted Translation-en \[430 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe i386 Packages \[733 kB\]         	 

http://security.ubuntu.com/ubuntu jammy-security/main Translation-en \[298 kB\]      	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 Packages \[1 125 kB\]  	 

http://security.ubuntu.com/ubuntu jammy-security/main amd64 c-n-f Metadata \[13,3 kB\]     	 

http://security.ubuntu.com/ubuntu jammy-security/restricted amd64 Packages \[2 439 kB\]       	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe Translation-en \[262 kB\]               	 

http://security.ubuntu.com/ubuntu jammy-security/restricted Translation-en \[420 kB\]                  	 

http://security.ubuntu.com/ubuntu jammy-security/universe amd64 Packages \[906 kB\]             	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 c-n-f Metadata \[26,1 kB\]    	 

http://security.ubuntu.com/ubuntu jammy-security/universe i386 Packages \[629 kB\]        	 

http://security.ubuntu.com/ubuntu jammy-security/universe Translation-en \[177 kB\]

http://security.ubuntu.com/ubuntu jammy-security/universe amd64 c-n-f Metadata \[19,3 kB\]

Получено 15,8 MB за 6с (2 451 kB/s)                                                                                             	 

Чтение списков пакетов… Готово

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ sudo apt-get intstall mysql-server

E: Неверная операция intstall

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ sudo apt-get install mysql-server

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Уже установлен пакет mysql-server самой новой версии (8.0.39-1ubuntu22.04).

Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 0 пакетов, и 44 пакетов не обновлено.

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ mysql \--version

mysql  Ver 8.0.39 for Linux on x86\_64 (MySQL Community Server \- GPL)
```
## 4\.
```
k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ sudo apt-get install cowsay

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Предлагаемые пакеты:

  filters cowsay-off

Следующие НОВЫЕ пакеты будут установлены:

  cowsay

Обновлено 0 пакетов, установлено 1 новых пакетов, для удаления отмечено 0 пакетов, и 44 пакетов не обновлено.

Необходимо скачать 18,6 kB архивов.

После данной операции объём занятого дискового пространства возрастёт на 93,2 kB.

http://ru.archive.ubuntu.com/ubuntu jammy/universe amd64 cowsay all 3.03+dfsg2-8 \[18,6 kB\]

Получено 18,6 kB за 0с (47,5 kB/s)

Выбор ранее не выбранного пакета cowsay.

(Чтение базы данных … на данный момент установлено 229806 файлов и каталогов.)

Подготовка к распаковке …/cowsay\_3.03+dfsg2-8\_all.deb …

Распаковывается cowsay (3.03+dfsg2-8) …

Настраивается пакет cowsay (3.03+dfsg2-8) …

Обрабатываются триггеры для man-db (2.10.2-1) …

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ cowsay "Приветствую\!"

 \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\< Приветствую\! \>

 \---------------

    	\\   ^\_\_^

     	\\  (oo)\\\_\_\_\_\_\_\_

        	(\_\_)\\   	)\\/\\

            	||----w |

            	|| 	||

k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ sudo apt-get remove cowsay

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Следующие пакеты будут УДАЛЕНЫ:

  cowsay

Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 1 пакетов, и 44 пакетов не обновлено.

После данной операции объём занятого дискового пространства уменьшится на 93,2 kB.

Хотите продолжить? \[Д/н\] y

(Чтение базы данных … на данный момент установлено 229866 файлов и каталогов.)

Удаляется cowsay (3.03+dfsg2-8) …

Обрабатываются триггеры для man-db (2.10.2-1) …
``` 
## 5\.  
``` 
k@k-VirtualBox:\~/Pitomnik/PetsDirectory$ history \> history.txt

1573  cd Pitomnik/

 1574  cat \> Pets.txt

 1575  cat \> PackAnimals.txt

 1576  cat Pets.txt PackAnimals.txt \> Animals.txt

 1577  cat Animals.txt

 1578  mv Animals.txt HumanFriends.txt

 1579  ls

 1580  mkdir PetsDirectory

 1581  mv HumanFriends.txt PetsDirectory/

 1582  cd PetsDirectory/

 1583  ls

 1584  sudo apt-get update

 1585  sudo apt-get intstall mysql-server

 1586  sudo apt-get install mysql-server

 1587  mysql \--version

 1588  sudo apt-get install cowsay

 1589\* cowsay "Здарова отец

 1590  sudo apt-get remove cowsay

 1591  history \> history.txt

```
## 6\.

![](diagram.png)
## 7\. 
```
mysql\> CREATE DATABASE HumanFriends;

Query OK, 1 row affected (0,14 sec)

mysql\> USE HumanFriends;

Database changed

mysql\>	CREATE TABLE Pets (

	\-\>    	ID INT AUTO\_INCREMENT PRIMARY KEY,

	\-\>    	Name VARCHAR(50),

	\-\>    	Type VARCHAR(20),

	\-\>    	BirthDate DATE,

	\-\>    	Commands TEXT

	\-\>	);

Query OK, 0 rows affected (0,31 sec)

mysql\>

mysql\>	CREATE TABLE PackAnimals (

	\-\>    	ID INT AUTO\_INCREMENT PRIMARY KEY,

	\-\>    	Name VARCHAR(50),

	\-\>    	Type VARCHAR(20),

	\-\>    	BirthDate DATE,

	\-\>    	Commands TEXT

	\-\>	);

Query OK, 0 rows affected (0,26 sec)

mysql\>    

mysql\> INSERT INTO Pets (Name, Type, BirthDate, Commands) VALUES

	\-\> ('Fido', 'Dog', '2020-01-01', 'Sit, Stay, Fetch'),

	\-\> ('Whiskers', 'Cat', '2019-05-15', 'Sit, Pounce'),

	\-\> ('Hammy', 'Hamster', '2021-03-10', 'Roll, Hide'),

	\-\> ('Buddy', 'Dog', '2018-12-10', 'Sit, Paw, Bark'),

	\-\> ('Smudge', 'Cat', '2020-02-20', 'Sit, Pounce, Scratch'),

	\-\> ('Peanut', 'Hamster', '2021-08-01', 'Roll, Spin'),

	\-\> ('Bella', 'Dog', '2019-11-11', 'Sit, Stay, Roll'),

	\-\> ('Oliver', 'Cat', '2020-06-30', 'Meow, Scratch, Jump');

Query OK, 8 rows affected (0,17 sec)

Records: 8  Duplicates: 0  Warnings: 0

mysql\> INSERT INTO PackAnimals (Name, Type, BirthDate, Commands) VALUES

	\-\> ('Thunder', 'Horse', '2015-07-21', 'Trot, Canter, Gallop'),

	\-\> ('Sandy', 'Camel', '2016-11-03', 'Walk, Carry Load'),

	\-\> ('Eeyore', 'Donkey', '2017-09-18', 'Walk, Carry Load, Bray'),

	\-\> ('Storm', 'Horse', '2014-05-05', 'Trot, Canter'),

	\-\> ('Dune', 'Camel', '2018-12-12', 'Walk, Sit'),

	\-\> ('Burro', 'Donkey', '2019-01-23', 'Walk, Bray, Kick'),

	\-\> ('Blaze', 'Horse', '2016-02-29', 'Trot, Jump, Gallop'),

	\-\> ('Sahara', 'Camel', '2015-08-14', 'Walk, Run');

Query OK, 8 rows affected (0,05 sec)

Records: 8  Duplicates: 0  Warnings: 0

mysql\> DELETE FROM PackAnimals WHERE Type \= 'Camel';

Query OK, 3 rows affected (0,03 sec)

mysql\> CREATE TABLE CombinedAnimals AS

	\-\> SELECT \* FROM Pets

	\-\> UNION ALL

	\-\> SELECT \* FROM PackAnimals;

Query OK, 13 rows affected (0,17 sec)

Records: 13  Duplicates: 0  Warnings: 0

mysql\> CREATE TABLE YoungAnimals AS

	\-\> SELECT

	\-\> 	ID,

	\-\> 	Name,

	\-\> 	Type,

	\-\> 	BirthDate,

	\-\> 	Commands,

	\-\> 	FLOOR(DATEDIFF(CURDATE(), BirthDate)/30) AS AgeInMonths

	\-\> FROM

	\-\> 	CombinedAnimals

	\-\> WHERE

	\-\> 	DATEDIFF(CURDATE(), BirthDate) BETWEEN 365 AND 1095;

Query OK, 0 rows affected (0,23 sec)

Records: 0  Duplicates: 0  Warnings: 0

mysql\> CREATE TABLE AllAnimals AS

	\-\> SELECT

	\-\> 	'Pets' AS Category,

	\-\> 	ID,

	\-\> 	Name,

	\-\> 	Type,

	\-\> 	BirthDate,

	\-\> 	Commands

	\-\> FROM

	\-\> 	Pets

	\-\> UNION ALL

	\-\> SELECT

	\-\> 	'PackAnimals' AS Category,

	\-\> 	ID,

	\-\> 	Name,

	\-\> 	Type,

	\-\> 	BirthDate,

	\-\> 	Commands

	\-\> FROM

	\-\> 	PackAnimals

	\-\> UNION ALL

	\-\> SELECT

	\-\> 	'CombinedAnimals' AS Category,

	\-\> 	ID,

	\-\> 	Name,

	\-\> 	Type,

	\-\> 	BirthDate,

	\-\> 	Commands

	\-\> FROM

	\-\> 	CombinedAnimals

	\-\> UNION ALL

	\-\> SELECT

	\-\> 	'YoungAnimals' AS Category,

	\-\> 	ID,

	\-\> 	Name,

	\-\> 	Type,

	\-\> 	BirthDate,

	\-\> 	Commands

	\-\> FROM

	\-\> 	YoungAnimals;

Query OK, 26 rows affected (0,19 sec)

Records: 26  Duplicates: 0  Warnings: 0
```


