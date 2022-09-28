Повторяю основы JavaScript по данному [курсу](https://ru.hexlet.io/courses/js-basics) и если что-то подзабыла конспектирую сюда
# :computer: Конспект по темам, которые не помню :computer:
### Переменные
Переменные необходимы только в одном случае, если мы работаем с циклами. В остальном нужно использовать константы.
**4 основных подхода в именовании переменных:**
1. kebab-case
2. snake_case
3. CamelCase
4. loverCamelCase

**Magic Numbers** - это числа, происхождение которых нельзя понять без глубоко анализа кода.

### Интерполяция
Работает только со строками в бектиках

### Типы данных
Зачем нужны типы данных? Для защиты данных от трудноотловимых ошибок. JavaScript понимает какой тип данных перед ним по способу инциализации.

`let name = undefined` - это нарушение семантики значения undefined. Потому что смысл (семантика) значение undefined в том, что значение не присвоено, а мы выполняем присваивание

**typeof** - это оператор

### Детерминированнная функция
Функция называется детерминированной тогда, когда для одних и тех же входных параметров она возвращает один и тот же результат.

### Побочный эффект
Это действия, которые изменяют внешнее окружение (среду выполнения)

name.length - это свойство
name.toUpperCase() - это метод (методы возвращают новое значение, а не меняют значение переменных)

### Возврат значений
return - это особая инструкция, которая берет выражение справа и отдает наружу, тому коду, который вызвал функцию. Как только JavaScript видит return функция прекращает свою работу (после return ничего не выполняется)

### Значения по умолчанию
Прописываются в конце иначе они будут перезаписаны

В es6 появилась возможность укореченной записи функции: `const name = (x) => x / 3`

### Предикаты
Это функции, которые всегда отвечают на один вопрос и возращают только true/flase. В JavaScript для простоты анализа, принято называть функции-предикаты с is,has или can

### Логические операции
&& - и (и то, и другое). В математической логике это называю коньюкцией. Работает так, что его выполнение прерывается, как только он найдет false

|| - или (или то, или другое, или оба). В математической логике - дизъюнкция. Работает так, что его выполнение прерывается, как только он найдет true

! - отрицание
