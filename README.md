# Отчет по лабораторным работам по курсу "Проектирование информационных систем"

## Выполнил студент группы [ИДБ-15-13](https://github.com/stankin/design-2018/wiki/list-idb-15-13) Бармина Валерия.

### Лабораторная работа №1

#### Создание IDEF0-диаграммы "Обновление приложения мо методологии Agile" в RAMUS (программное средство разработки структурно-функциональных моделей)

* IDEF0-диаграмма в развернутом виде:

![none](https://github.com/lerchicperch/Labs/blob/master/model.png)

* [IDEF0-диаграмма в формате .rsf](https://github.com/lerchicperch/Labs/blob/master/Lab1.rsf)

#### Создание диаграммы классов и диаграммы прецедентов в PLANTUML (программное средство автоматической генерации UML-диаграмм)

* [Текст](https://github.com/lerchicperch/Labs/blob/master/Текст%20Диаграммы%20классов.txt) и рисунок диаграммы классов <br>
![none](https://github.com/lerchicperch/Labs/blob/master/Диаграмма%20классов.png) 

* [Текст](https://github.com/lerchicperch/Labs/blob/master/Текст%20Диаграммы%20прецедентов.txt) и рисунок диаграммы классов <br>
![none](https://github.com/lerchicperch/Labs/blob/master/Диаграмма%20прецедентов.png) 
***

### Лабораторная работа №2 - определение подсистемы и надсистемы.
***
* Диаграмма IDEF0 - А0 "Cоздавать дизайн-макет web-сайта"

![none](https://github.com/lerchicperch/Labs/blob/master/Lab2/lab2%20(idef0%20A0).png)

* Диаграмма IDEF0 - декомпозиция А0 в А1-А2-А3 по принципу Plan-Do-Check

![none](https://github.com/lerchicperch/Labs/blob/master/Lab2/lab2%20(idef0%20A1%2C%20A2%2C%20A3).png)

* Диаграмма DFD - декомпозиция А3 "Сборка макета"

![none](https://github.com/lerchicperch/Labs/blob/master/Lab2/lab2%20(DFD).png)

* [Диаграммы второй лабораторной работы в формате .rsf](https://github.com/lerchicperch/Labs/blob/master/Lab2/Lab2.rsf)
***

### Лабораторная работа №3
***
#### Определение способов существования информации
 Цель: Разработка информационной системы приема и выполнения заказов на разработку дизайнов<br>
Точка зрения: Директор/Teamlead дизайн-студии<br>
Область моделирования: Потоки данных дизайн-студии<br>
 * Диаграмма DFD - Главный контекст модели
 ![none](https://github.com/lerchicperch/Labs/blob/master/Lab3/lab3%20(DFD%20process).png)
 * Диаграмма DFD - А0. Работа дизайн-группы
 ![none](https://github.com/lerchicperch/Labs/blob/master/Lab3/lab3%20(DFD%20A0).png)
 * Диаграмма DFD - декомпозиция в А2. Прием заказов
 ![none](https://github.com/lerchicperch/Labs/blob/master/Lab3/lab3%20(DFD%20A2).png)
 *  Диаграмма DFD - декомпозиция в А3. Создание дизайна
 ![none](https://github.com/lerchicperch/Labs/blob/master/Lab3/lab3%20(DFD%20A3).png)
 [Диаграммы третьей лабораторной работы в формате .rsf](https://github.com/lerchicperch/Labs/blob/master/Lab3/Lab3.rsf)
 * ERD-диаграмма
 ![none](https://github.com/lerchicperch/Labs/blob/master/Lab3/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG)
***
### Лабораторная работа №4
***
### Определение основных средств автоматизации
Определение требований к модели
* Формальное определение объекта моделирования (процесса) - разработка дизайна
* Формальное определение точки зрения (владелец, руководитель) - владелец информационного ресурса (инвестор/спонсор)
* Формальное определение цели моделирования (вопросы к модели) - выделение процессов, требующих улучшения путем автоматизации.
* Формальное определение темы курсового проекта (наименование информационной системы) - Информационная система для поддержки совместной работы над дизайн-проектами.

### Разработка диаграмм в RAMUS

* Контекстная диаграмма А0 - "Разработка дизайна"

![A0](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A0).png)

* Декомпозиция диаграммы уровня А0 (А1-А5) на пять блоков

![A1-А5](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A1-A5).png)

* Декомпозиция блока А1 "Создание проекта"

![A11-A13](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A11-A13).png)

* Декомпозиция блока А3 "Подборка концепции дизайна"

![A31-A34](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A31-A34).png)

* Декомпозиция блока А4 "Создание графики"

![A41-A44](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A41-A44).png)

* Декомпозиция блока А5 "Сборка макета"

![A51-A54](https://github.com/lerchicperch/Labs/blob/master/Lab4/IDEF0(A51-A54).png)

### Примечания к работе

> В модели могут быть автоматизируемые и неавтоматизируемые процессы. Только от автоматизируемых процессов можно перейти к DFD. 

> В курсовой нужно посчитать эффективность автоматизации хотя бы по одному показателю ( в сравнении с неавтоматизированными процессами(блоками))

> Определить тип системы (сайт)

> Определить масштабы работы или какие-либо целевые характеристики системы в цифрах (какое количство человек может обслуживать, и т.д.) и доказать, что система этим характеристикам удоветворяет, а также определить, должна ли меняться система при изменении этих цифр. 

> Норма для курсовой - 5-6 idef0. К ним необходимы цель, название процесса и обоснование. 

### Лабораторная работа №5
***

### Определение основных средств автоматизации
* Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование):
  - Рабочие станции (электронные устройства);
  - Сервер приложений;
  - Сервер БД.
* Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные):
  - Многоуровневые (трехуровневые).
* Определение допустимых видов хранилищ и их размещения:
  - Внутренняя память устройства.
  - База данных на сервере БД.

### Разработка диаграмм в RAMUS - декомпозиция всех автоматизируемых блоков в DFD

* Декомпозиция блока А11 "Создание проекта и добавление участников"

![A11](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A11.png)

* Декомпозиция блока А12 "Заполнение инфо о проекте и базовой документации"

![A12](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A12.png)

* Декомпозиция блока А13 "Создание общего чата и календаря"

![A13](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A13.png)

* Декомпозиция блока А33 "Подбор цветовой палитры"

![A33](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A33.png)

* Декомпозиция блока А34 "Составление мудборда"

![A34](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A34.png)

* Декомпозиция блока А53 "Проверка соответствия"

![A53](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A53.png)

* Декомпозиция блока А54 "Сбор документации"

![A54](https://github.com/lerchicperch/Labs/blob/master/Lab5/DFD_A54.png)


### Лабораторная работа №6 - подготовка диаграмм UML курсового проекта
***
### Завершение идентификации всех потоков

* Построение ERD (диаграммы классов без атрибутов) для всех потоков с помощью инструента PlantUml
![Data](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram%20date.png)

* Загрузка модели и диаграммы классов в репозиторий
(Смотреть [файл диаграммы](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram%20date.png) и [текст для построения диаграммы](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_date%20text.txt) в PlantUml)

### Завершение идентификации всех ролей

* Построение ERD (диаграммы классов без атрибутов) для всех ролей с помощью инструента PlantUml
![Roles](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_roles.png)

* Загрузка модели и диаграммы классов в репозиторий
(Смотреть [файл диаграммы](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_roles.png) и [текст для построения диаграммы](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_roles.txt) в PlantUml)

### Завершение идентификации всех модулей

* Построение ERD (диаграммы классов без атрибутов) для всех модулей с помощью инструента PlantUml
![Modules](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_modules.png)

* Загрузка модели и диаграммы классов в репозиторий
(Смотреть [файл диаграммы](https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_modules.png) и [текст для построения диаграммы] (https://github.com/lerchicperch/Labs/blob/master/Lab6/Diagram_modules%20text.txt) в PlantUml)

* Завершение редактирования readme.md.
