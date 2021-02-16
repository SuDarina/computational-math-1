Лабораторная работа 1
Вариант:
•	Метод простых итераций

Размерность n <= 20 (задается из файла или с клавиатуры - по выбору конечного пользователя)
Должно быть предусмотрено чтение исходных данных как из файла, так и ввод с клавиатуры.
Должна быть реализована возможность ввода коэффициентов матрицы как с клавиатуры, так и из файла. Также предусмотреть случайные коэффициенты.
Обязательно: Тестовые данные на матрице большого размера (5*5 / 6*6...) + в отчёт с решением.
Для итерационных методов должно быть реализовано:
•	Точность задается с клавиатуры/файла
•	Проверка диагонального преобладания
//В случае, если диагональное преобладание в изначальной матрице отсутствует - предлагается сделать перестановку строк/столбцов до тех пор, пока преобладание не будет достигнуто. В случае невозможности достижения диагонального преобладания - выводить сообщение.
•	Столбец неизвестных
•	Количество итераций, за которое было найдено решение
•	Столбец погрешностей
