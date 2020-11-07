# hw-functionsJS
>
1. Напишіть функцію, що повертає куб числа.
>
2. Напишіть функцію, що додає перше число до другого і ділить результат на третє число.
>
3. Напишіть функцію, що приймає число від 1 до 7 і повертає відповідну назву дня.
>
4. Реалізуйте функцію знаходження факторіала
>
5. Напишіть функцію яка отримує години хвилини та секунди і повертає це число в секундах.
>
6.    Написати функцію , яка приймає секунди, і перетворює їх у години хвилини та секунди у форматі «гг:хх:сс». якщо кількість годин більша за 23.59.59 - вивести повідомлення "Більше одного дня". 
>
7. 4 відмінності ерров фанкшина від звичайної функції.
>


# Відмінності ерров фанкшина від звичайної функції.
- коротший спосіб написання синтаксису, коли лінь писати багато коду)).
- у стрілкових функцій немає this, якщо потрібно - його значення береться зовні.
- стрелочные функции не могут быть использованы как конструкторы. Они не могут быть вызваны с new.
- у стрелочных функций также нет переменной arguments.
- у них также нет super.
- ерров функції повертають значення функції і без return, а у звичайних - якщо немає return або після return немає виразу, функція поверне undefined.
- ерров функція не має масива arguments, вона буде брати його із зовнішньої функції.



## Повторим для закрепления. 
Область видимости **var переменных** ограничена функцией, если вы обратитесь к переменной до её объявления, то получите undefined. 
>
**const и let** ограничены блоком, а попытка обратится к переменной до её объявления, вернётся ошибкой ReferenceError.
>
И наконец, разница между **let и const** в том, что в первом случае вы можете изменить значение переменной, а во втором нет.
>

**var VS let VS const**
>var: 
>>  function scoped
>>  undefined when accessing a variable before it's declared
>let: 
>>  block scoped
>>  ReferenceError when accessing a variable before it's declared
>const:
>>  block scoped
>>  ReferenceError when accessing a variable before it's declared can't be reassigned

