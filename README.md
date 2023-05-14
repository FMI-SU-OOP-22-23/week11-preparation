## Разглеждаме полином от вида
### F(x) = a\*x^n+b\*x^(n-1)+...+z

### Задача 1
Разглеждаме
* a,b....z... са в интервалът на double, като може да приемат и отрицателни стойности.
* Нямаме ограничения за степените, стига те да се побират в int, т.е. може и да са отрицателни.
* Да се дефинират клас Polinom, който да може да дефинира съответно такава функция.
* Да се дефинират дясноасоциативни оператори 
#### \+
#### \+=
#### \-
#### -=
които по зададена стойност на степента да променя стойност пред нея.
Въпрос? Можем ли данните за съответна степен да ги заделим в отделен клас или структура.

* Да се дефинират и оператори
#### ==
#### !=
#### \(\) който изчислява изразът в съответна точка double
#### operator[], като са съответната степен няма стойност да връща 0 в контекста на const оператора. Иначе да връща обекта, съдържащ информация са степента.

* Да се дефинира метод derivative, който намира производната на зададената функция, връщайки нов обект от клас Fuction
* Ако има невалиден израз/стойност, да се хвърли съответно грешка за това.

### Задача 2
Нека a,b,..z... вече не са в контекста само на double, а могат да приемат функции от вида на
* sin(x)
* cos(x)
* ln(x)
* 1/x (x!=0)

Като тази стойност за x ще дойтe от изпълнението на оператор (), т.е.

Имайки полином от вида
* F(x) = sin(x) * x^3 + cos(x) * x^1 - ln(e)

ще можем да изчислим изразът в точка 1
Да се изпълнят всичките условия от подточка а. Какво ни трябва допълнително за да изчислим производната?
