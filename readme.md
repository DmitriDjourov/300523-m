1. Теги это сущность с помощю которой мы можем добалять разные элементы на нашу страницу
2. Тегы бываеют открывающееся и сразу закрывающейся (<!DOCTYPE html>, <meta charset="UTF-8" />)
   и есть открывающееся(<p>) и закрывающейся(</p>)
3. Атрибут это дополнительное свойсто для наших тегов, которые модифицируют его
4. Теги разделяются на блочные(h1-h6, p, div) и строчные(img, span, a)
5. Блочные элементы занимают всю ширину своего родителя
6. Строчные элементы занимают столько место сколько им надо
7. Для добавления гиперссылок используют <a>. Он имеет атрибут href, в него добавляем ссылку для переадресации
8. 3 основные способа работы с css.
   --1. Работать через атрибут style ( <div style="margin-left: 100px; margin-top: 100px">).
   --2. Через тег style. В теге head прописать тег style и внем уже писать стили
   --3. Работать с css-ом в отдельном документе (в head добавляем teg link и отдаем ссылку на css документ)
9. Когда работаем с двумя документами(html css). HTML является оснваным(у страницы может не быть стилей но у страницы не может быть html-я). Поэтому до того как писать css надо:
   1-- Создать документ css-a
   2-- Прикрепить css к html

10. Цвета можно писать:
    1-- через rgb - красного, зеленного, синего. Каждый из цветов идет в диапазоне 0-255
    3-- через hex - 3ое или 6ое величниа. Обьязательно пишем через #
    4-- через имя цвета (red, green, blue)
    5\*\*-- На реальных проектах в оснавном запрещают писать черес имена цвета

11. Отсупты бывают внутренние(padding) и внешние(margin). Они работают с сторчнимы элементами

12. Для того чтобы писать каждому элементу писать отдлеьный стиль можно использвать классы. В css пишем имя класса через точку(.) и в фигурных скобках даем стили.

1-- Если мы хотим прописать общий стиль то можно создать еще один общий класс и там задатаь общие стили. В результате полчится в html теги с несколькими классами (свой класс, общи). А в css-е будет прописан общий стиль и для каждого отдельный
# 300523-m
