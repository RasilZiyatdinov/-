Участники: Зиятдинов Р. А., Неволин С. Д., Ушаков А. С.
Группа: АСУ-19-1б, РИС-19-1б

## 1 Введение
### 1.1 Наименование программы
Наименование программы – "мои посетители".

### 1.2 Краткая характеристика области применения
Программа предназначена для отслеживания посетителей некоторой области (например, команаты) с целью отслеживания истории появления объектов.

## 2 Основания для разработки
Основанием на разработки послужил проект по дисциплине "Интернет вещей"

## 3 Назначение разработки
Программа будет отслеживать историю посетителей помещения.

## 4 Требования к программе или программному изделию
### 4.1 Требования к функциональным характеристикам
Проект: отслеживание посетителей комнаты. 
Камера в ноутбуке будет фиксировать объекты которые заходят в комнату (объект может быть собакой, кошкой и человеком) и заносить их в базу данных. Пользователь может посмотреть в какое время появлялся объект и его фотографию.
Фотография отправляется пользователю на почту.

### 4.2 Условия эксплуатации
Программа запускается на компьютере пользователя. База данных и сайт находится на этом же компьютере.

Руководство по запуску веб приложения.

1. Установить переменную среды FLASK_APP с помощью команды: 
```
set FLASK_APP=microblog.py
```
для linux set заменить на export

2. Активировать виртуальную среду. 
Для windows: 
```
venv\Scripts\activate
```
Для linux: 
```
source venv/bin/activate
```
3. Запустить: 
```
flask run
```

Скрипт распознования объектов запускается отдельно с помощью команды:
```
python real_time_object_detection.py
```

### 4.3 Требования к составу и параметрам технических средств
Компьютер должен включать в себя:
1. процессор x86 с тактовой частотой, не менее 1 ГГц;
2. оперативную память объемом, не менее 1 Гб;
3. монитор, мышь, клавиатура, веб-камера;
4. подключение к Интернету

## 5 Требования к программной документации
Предварительный состав программной документации:
1. техническое задание;
2. программа;
3. руководство пользователя;

## 6 Стадии и этапы разработки
Разработка должна быть проведена в 3 стадии:
1. анализ задачи
2. технический проект
3. испытания
