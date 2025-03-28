# **Проект "Исследование коллекции советской фалеристики развлекательной и спортивной сфер, которая хранится в Эрмитаже"**
## **Цель:** изучить коллекцию советской фалеристики Эрмитажа в области развлечений и спорта.
#### [Ссылка на исследование](https://colab.research.google.com/drive/1DEDiqUjxTpM4ffV4KB3oIV05SUYY-Kc5?usp=sharing)
#### Выгрузим все данные о значках СССР, которые содержатся в "Эрмитаже". Всего оказалось 18577.
#### С помощью сводной таблицы мы узнаем, когда информация о значках СССР была загружена в систему Министерства Культуры. Это происходило с 2017-05-23 по 2023-08-31.
#### Выведем количество уникальных значений, чтобы узнать, сколько в датафрейме неповторяющихся значков. Их оказалось 15836. 
#### С помощью моды стало известно, что самый популярный значок - значок окончившего школу ВВС - РККА.
#### Создадим признак "topic", в котором будет выводиться "Развлекательная сфера", если в признаке "data_name" содержится "Телевидение", "Радио", "Пресса", "Музеи", "Театры", в ином случае будет выводиться "False". 
#### Выведем датафрейм, в котором содержатся значки только развлекательной сферы. Их оказалось 134. 
#### Выведем частотную таблицу для названий значков, чтобы узнать количество повторяющихся значков в развлекательной сфере. Сделаем вывод, что чаще всего значки развлекательной сферы упоминаются один раз и не более трех. 
#### Выведем гистограмму по частотной таблице для названий значков в развлекательной сфере. 
#### Создадим признак "topic", в котором будет выводиться "Спортивная сфера", если в признаке "data_name" содержится "Спорт", "Турнир", "Чемпионат", "Матч", "Спортсмен", "Соревнование" в ином случае будет выводиться "False". 
#### Выведем датафрейм, в котором содержатся значки только спортивной сферы. Их оказалось 189. 
#### Выведем частотную таблицу для названий значков, чтобы узнать количество повторяющихся значков в спортивной сфере. Сделаем вывод, что чаще всего значки спортивной сферы упоминаются один раз и не более двух. 
#### Выведем гистограмму по частотной таблице для названий значков в спортивной сфере.
# **Выводы**
#### 1. В Эрмитаже значков спортивной сферы хранится больше, чем значков развлекательной сферы. 
#### 2. Преимущественно значки хранятся в одном экземпляре, однако некоторые могут храниться в трех. 

#### **Свободная лицензия** 

#### **Автор:** Капитова Валерия 
