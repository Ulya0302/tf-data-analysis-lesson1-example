# Условие

Школа `N` имеет сильный состав
для соревнования в прыжках в длину.
В ней есть несколько сильных спортсменов,
но на соревнования нужно отправить одного.
Тренер Максим вычитал из книги, 
что длина прыжка имеет нормальное распределение,
поэтому тренер решил выбрать лучшего школьника
на основании оценки матожидания длины прыжка.
Помогите Максиму составить оценку этой величины
для каждого студента.

# Входные данные

Одномерный массив `numpy.ndarray`
длин прыжков (в сантиметрах) одного спортсмена.

# Возвращаемое значение

Оценка матожидания длины прыжка.

# Оценка

Максимальный балл: $4$.
* $+1$ балл, если на выборках размера $1000$ MSE оценки < $0.01$.
* $+1$ балл, если на выборках размера $1000$ MSE оценки < $0.005$.
* $+1$ балл, если на выборках размера $100$ MSE оценки < $0.015$.
* $+1$ балл, если на выборках размера $10$ MSE оценки < $0.09$.
