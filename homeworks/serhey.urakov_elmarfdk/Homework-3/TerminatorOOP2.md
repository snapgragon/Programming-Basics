ООП

1. Класс терминатор - серия различных роботов и автоматических боевых механизмов, созданных искусственным
интеллектом «Скайнет» для истребления человечества.
2. Объект - терминатор Т-800
3. Наследование на примере человекоподобных роботов:
T-70 Первый вариант человекообразного боевого робота-терминатора.
T-600 представляют собой примитивный вариант человекообразной машины: помимо грубой резиновой лицевой маски они
имеют неудачную громоздкую конструкцию высотой 2,2 метра.
В основе T-800 — металлический эндоскелет, в общих чертах имитирующий скелет человека.
4. Инкапсуляция:
Несмотря на то что терминаторы проектировались и создавались искусственным интеллектом, были технически очень сложными,
люди смогли перепрограммировать их.
5. Полиморфизм:
Мототерминаторы, гидротерминаторы, летающие охотники-убийцы, человекоподобные роботы. Несмотря на то что терминаторы
очень различны, основной их задачей является уничтожение людей.

SOLID

S. Принцип единственной ответственности (The Single Responsibility Principle)
Для выполнения различных задач используться разные виды роботов: мототерминаторы, гидротерминаторы, летающие
охотники-убийцы, человекоподобные роботы.
O. Принцип открытости/закрытости (The Open Closed Principle)
Созданием и разработкой терминаторов занимался Скайнет. Более поздние модели терминаторов почти полностью исключают
вмешательство человека в свои системы управления.
L. Принцип подстановки Барбары Лисков (The Liskov Substitution Principle)
Основной задачей терминаторов всех модельных линеек является физическая ликвидация людей, в этом вопросе терминаторы
всех серий взаимозаменяемы.
I. Принцип разделения интерфейса (The Interface Segregation Principle)
Хотя Скайнет для управления своими машинами использует свой интерфейс, Джон Конорм смог перепрограммировать терминатора
T-800 используя интерфейс доступный человеку разработаный людьми из «Cyberdyne Systems».
D. Принцип инверсии зависимостей (The Dependency Inversion Principle)
Процессоры Т-900 могли работать в режиме «читать». Это позволяло Скайнет лучше контролировать свои создания, но сильно
ограничивало их способность к обучению. К концу войны большое количество терминаторов было захвачено и
перепрограммировано людьми, а работающие в режиме самообучения роботы сами переходили на сторону людей.