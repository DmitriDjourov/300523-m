1. Массив это тип данных кототрый относится к ссылочным типам данных
2. В массиве можно хранить сразу несколъко значений с разными типами данных
3. Массив был создан на основе объектаов
4. Для того чтобы взять конкретый элемент массива надо к ниму обратится через его индекс. Для обращения пишем название массива, ставим [], и в них пишем индекс
5. Индексация в массиве начинается с 0я
6. Методы массива это встоенные функции для работы с массивами. Они были разработаны до нас самими разробтчиками языка. Она упращют код делая его меньше и намного читабльнее
7. Push - добаляет в конец массива новый элемент, и возвращет новую длинну массива(можем хранить в переменной).
8. Unshift - делает все как метод "Push", только добавляет в начало массива
9. Pop - удаляет последний элемент массива, и возращает его (можно хранить в переменной)
10. Shift - длеает все как метод "Pop", только удалает с начала
11. ForEach - метод массива который нам посозвляет, итерривоатся по ниму. Метод как параметр принемает колбэк функцию, которся в свою очередь принимает: первым параметром
    итерируемый элемент, индекс итеруемого элемента, сам массив. Здесь надо быть внимательным так как данный метод нам нечего не возращает.
12. Map - Данный метод тоже итерируется по массиву как метод ForEach, только есть одно
    исключение. Он нам в качестве результата возращает новый массив

13. Reduce - метод с помощь которо можно транфомировать текущию массив. В качестве параметра метод пинимает, 1ым колбек функцию и 2ым дефолтное значение. Колбэек в совю очередь принемает 4 параметра, предудещее состояние(во время итерции рова дефолтному значению), теукщее значение, индехкс итерауемого элемента, сам массив

DOM manuplation (InnereHTML, InnereText,ClinetWidth,CLinetHeight,InserAdjectHTML, InserAdjectElmenet, addEventlistteners)
Object methods (call,apply,bind)
this (объекта, функции тд)
executon context
this in function (пичему нельзя испоольвать this внутри стелочной функции)
Асинхронный код