# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

# Описание решения
## Проект содержит различные геометрические формулы ,такие как:
- Формулы площади: круга, прямоугольника, квадрата, треугольника
- Формулы периметра: круга, прямоугольника, квадрата, треугольника

# circle.py
## 1: area(r)
### Параметры функции
- r - радиус круга
### Возвращает:
- площадь круга радиуса r 
### Пример:
- input -> 0
- area(0)
- return math.pi * r * r
- output -> 0
## 2: perimeter(r)
### Параметры функции
- r - радиус окружности
### Возвращает:
- длину окржности радиуса r 
### Пример:
- input -> 0
- perimeter(0)
- return math.pi * 2 * r
- output -> 0

# rectangly.py
## 1: area(a,b)
### Параметры функции
- a - первая сторона прямоуг.
- b - первая сторона прямоуг.
### Возвращает:
- площадь прямоугольника со сторонами a и b
### Пример:
- input-> 10 20
- area(10, 20)
- return a * b
- output -> 200
## 2: perimeter(a,b)
### Параметры функции
- a - первая сторона прямоуг.
- b - первая сторона прямоуг.
### Возвращает:
- периметр прямоугольника со сторонами a и b
### Пример:
- input-> 10 20
- area(10, 20)
- return 2 * (a + b)
- output -> 60

# rectangly.py
## 1: area(a)
### Параметры функции
- a - сторона квадрата
### Возвращает:
- площадь квадрата со стороной а
### Пример:
- input-> 10
- area(10)
- return a * a
- output -> 100
## 2: perimeter(a)
### Параметры функции
- a - сторона квадрата
### Возвращает:
- периметр квадрата со стороной а
### Пример:
- input-> 10
- area(10)
- return 4 * a
- output -> 40

# triangly.py
## 1: area(a , h)
### Параметры функции
- a - сторона треугольника
- h - высота проведенная к этой стороне
### Возвращает:
- площадь треугольника со стороной а и высотой,проведенной к этой стороне h
### Пример:
- input-> 20 10
- area(20, 10)
- return a * h / 2
- output -> 100
## 2: perimeter(a,b,c)
### Параметры функции
- a - первая сторона треугольника
- b - вторая сторона треугольника
- c - третья сторона треугольника 
### Возвращает:
- периметр треугольника со сторонами а,b,c
### Пример:
- input-> 10 20 30
- area(10, 20, 30)
- return a + b + c
- output -> 60

# История коммитов

- b98cd85fbea69798ecf92bd9bf83a6f91d0182c8 : добавлена документация к файлу triangle.py
- 031928f915df3515a64e7f0f91f7e57b70dc348a : добавлена документация к файлу square.py
- e8afef4127166dab3122751343b675834e2fa579 : добавлена документация к файлу recyangle.py
- dbacabcd2baee5109f921271477935ce31293604 : добавлена документация к файлу circle.py

