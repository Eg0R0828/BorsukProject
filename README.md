# BorsukProject

### Визуализация нахождения пути в лабиринте:
Генерируется декартовый лабиринт с закрашенным ячейками, изображение которого визуализировано. Пользователь выбирает точку входа. После нажатия на кнопку Решить появляется найденный путь. После этого визуализируется самый короткий найденный путь. Есть возможность пошагово пройти по шагам алгоритма нахождения пути. При невозможности найти выход из лабиринта пользователь получает уведомление.

- [ ] Выбор размера лабиринта
- [ ] Выбор конкретной точки выхода
- [ ] Возможность сохранять и загружать конфигурацию из файла
- [ ] Просмотр посещенных алгоритмом вершин

### Алгоритм и структуры данных:
Основная структура данных - матрица.
#### Матрица:
+ 0 - Пустая клетка
+ 1 - Стенка
+ 2, 3, ... - Номер пути
+ s - Старт
+ f - Финиш
#### Алгоритм
+ Используется алгоритм заливки

### Входные данные
+ Начальная и конечная точка
+ Размер лабиринта
+ Экземпляр лабиринта (опционально)
#### Выходные данные:
Визуальный вывод лабиринта:
+ Анимация поиска пути
+ Конечный пройденный маршрут;
+ Возможность выбора другово маршрута

### Правила работы с репозиторием
1. Каждая задача - отдельная ветка
2. Создание ветки 
	- git pull 
	- git checkout -b Issue_name
	В мастер мержить ЗАПРЕЩЕНО.
3.  После подготовки файлов - коммит
	- git add -A
	- git commit -m "Comment"
4. Отправление изменений на сервер
	- git push
5. Создание Pull Request с названием close #(issue_number) и необходимыми комментариями. 
	Если задача недовыполнена - использовать префикс WIP в пулл-реквесте

### План разработки
1. 1-я неделя. 
	Подготовка основного кода программы
	+ Анализ задачи и выбор алгоритма, исходных данных и используемых структур данных;
2. 2-я неделя. 
	Завершение работы над проектом
	+ Создание gui;
	+ Реализация алгоритма поиска;
	+ Объединение всех задач в единую программу;
	+ Тестирование.

### GUI
Примерный вид интерфейса
![Imgur](https://pp.userapi.com/c852036/v852036125/15f1af/i--SzLRpnx0.jpg)
![Imgur](https://pp.userapi.com/c852036/v852036125/15f266/_H6qoOMGlSg.jpg)

### Примерное распределение ролей
1. [Трушников Андрей](https://github.com/AndersonGH)
	- Создание гуи
	- Написание отчета
2. [Вологдин Максим](https://github.com/makkksx)
	- Программирование основной логики
3. [Тарасенко Егор](https://github.com/Eg0R0828)
	- Тестирование
	- Менеджер по интеграции
