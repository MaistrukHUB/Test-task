FrontEnd Task

Working with Objects

Technical Specifications

Use react + redux

Input Parameters

Numbers M, N, X

Preparation

Create a matrix M*N (rows, columns)

The value of the intersection is an object with a unique identifier ID and the amount of Amount: int (3-digit random)

Find the sum of each row M and the average for each column N

Table Output

Display the resulting data in a table with good UX. The main cells of the table display Amount, previously automatically generated, the sum of rows M on the right, and the average of columns N below.

Cell Dynamics

When clicking on a cell, increase the Amount value by 1 and accordingly change the average of this column and the sum of this row.

When hovering over a cell, highlight X cells, the Amount of which is closest to the Amount of the current cell.

When hovering over a row sum cell, replace the values of the cells with the percentage of their contribution to the total sum and add a background: a bar that visually shows the percentage. Essentially color part of the cell.

Row Dynamics

Allow deleting a row from the table, with changes in the average values for each column.

Allow adding a row, essentially M+1. In this case, the row is filled according to all the rules of the table.













Завдання FrontEnd

На роботу з об'єктами

Технічні умови

Використовувати react + redux

Вхідні параметри

Числа M, N, X

Підготовка

Створити матрицю M*N (рядки, стовпці)

Значення місця перетину — об'єкт з унікальним ідентифікатором ID та кількістю Amount: int (3-значний рандом)

Знайти суму кожного рядка M та середнє по кожному стовпцю N

Вивід таблиці

Вивести результати в таблицю з хорошим UX. У основних комірках таблиці виводиться Amount, раніше автоматично згенерований, справа сума по рядках M, знизу — середнє по стовпцям N.

Динаміка комірок

При натисканні на комірку збільшувати значення Amount на 1 і відповідно змінювати середнє цього стовпця та суму цього рядка

При наведенні на комірку підсвічувати X комірок, Amount яких найближчий до Amount поточної комірки.

При наведенні на комірку суми по рядку необхідно замінювати значення комірок на відсоток їх внеску в загальну суму та додати фон: стовпчик, який наочно покаже величину відсотка. Фактично закрасити частину комірки.

Динаміка рядків

Дати можливість видалити рядок з таблиці, при цьому повинні змінитися середні значення по кожному стовпцю.

Дати можливість додати рядок, фактично M+1. При цьому рядок заповнюється за всіма правилами таблиці.
