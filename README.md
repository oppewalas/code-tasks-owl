# Задание №1 Дополнительное
## Числа Фибоначчи - кролики
Дополнительно, по желанию, по согласованию с преподавателем и на повышенную оценку, можно реализовать функцию *rabbits*, возвращающую количество пар кроликов в популяции на заданный месяц, при условии, что кролики имеют определенную продолжительность жизни.

При этом необходимо выбрать структуру данных, которую целесообразно использовать для решения задачи и обосновать свой выбор в комментариях к pull request с решением задачи.

## Примечания  
- Разработку вести в отдельной ветке, созданной на основе данной. В названии ветки префикс main заменить на название команды. 
- Корректность работы реализованных функций проверить запустив файл test.py с модульными тестами. 
- Если зависимости проекта установлены, можно запустить:
    * автоматическую сортировку импортов в исходном коде `python -m isort .`
    * автоматическое форматирование исходного кода `python -m black .`
    * проверку синтаксиса и форматирования `python -m flake8 . --max-complexity=10 --max-line-length=88 --exclude .venv`.
  
## Числа Фибоначчи  
**Числа Фибоначчи** — элементы числовой последовательности, в которой первые два числа равны 0 и 1 (либо 1 и 1), а каждое последующее число равно сумме двух предыдущих чисел. Названы в честь средневекового математика Леонардо Пизанского (известного как Фибоначчи).

Последовательность Фибоначчи можно задать двумя единицами и интерпретировать ее как количество пар кроликов в определенный период времени в идеальной популяции. Именно так Леонардо Пизанский сформулировал задачу о кроликах. В начальный период времени имеется новорождённая пара кроликов, начиная со второго месяца после рождения кролики производят новую пару кроликов каждый месяц, при этом кролики бессмертны. В такой интерпретации N-е число Фибоначчи показывает количество пар кроликов в N-м месяце.

## P.S.
Полезную информацию о порядке выполнения задания, установке и настройке необходимого ПО можно посмотреть в [Wiki](https://github.com/hse-algo-24-owl/docs-owl/wiki)