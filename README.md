1. Что произойдет при использовании `typeof` с `null`? <br>
    - a) Вернется "null" <br>
      Не верно потому что `typeof null` возвращает "object" <br>
    - b) Вернется "undefined" <br>
      Не верно потому что `typeof null` возвращает "object", а не "undefined" <br>
    - c) Вернется "object" <br>
      Верно потому что это известный "баг" JavaScript, и `typeof null` действительно возвращает "object" <br>
    - d) Вернется "error" <br>
      Не верно потому что JavaScript не выдаст ошибку, а вернет строку "object" <br>
2. Какое ключевое слово используется для создания нового контекста выполнения функции? <br>
    - a) `function` <br>
      Не верно потому что `function` определяет функцию, а не контекст выполнения <br>
    - b) `new` <br>
      Верно потому что при использовании `new` перед функцией создается новый объект, и `this` внутри функции будет ссылаться на него <br>
    - c) `this` <br>
      Не верно потому что `this` ссылается на текущий контекст выполнения, а не создает его <br>
    - d) `create` <br>
      Не верно потому что в JavaScript нет ключевого слова `create` для создания контекстов <br>
3. Какой метод массива используется для добавления элементов в начало массива? <br>
    - a) `push()` <br>
      Не верно потому что метод `push()` добавляет элементы в конец массива <br>
    - b) `pop()` <br>
      Не верно потому что метод `pop()` удаляет последний элемент из массива <br>
    - c) `shift()` <br>
      Не верно потому что метод `shift()` удаляет первый элемент из массива <br>
    - d) `unshift()` <br>
      Верно потому что метод `unshift()` добавляет один или несколько элементов в начало массива <br>

4. Что возвращает метод `Array.prototype.map()`? <br>
    - a) Новый массив, являющийся результатом вызова указанной функции для каждого элемента исходного массива. <br>
      Верно потому что это основное назначение метода `map()` <br>
    - b) `undefined` <br>
      Не верно потому что `map()` всегда возвращает новый массив <br>
    - c) Исходный массив без изменений <br>
      Не верно потому что `map()` создает и возвращает новый массив <br>
    - d) Массив, который может быть изменен внутри коллбэка <br>
      Не верно потому что результат работы `map()` не зависит от того, изменяется ли исходный массив в коллбэке <br>

5. Что такое Closure в JavaScript? <br>
    - a) Функция, объявленная внутри другой функции <br>
      Не совсем верно, поскольку само понятие закрытия включает в себя не только объявление функции внутри другой функции <br>
    - b) Объект базового класса `Object` <br>
      Не верно потому что Closure и `Object` относятся к разным аспектам JavaScript <br>
    - c) Возможность функции запоминать и доступаться к своему лексическому окружению, даже когда она выполняется вне его <br>
      Верно потому что это определение замыкания в JavaScript <br>
    - d) Специальная конструкция для работы с асинхронным кодом <br>
      Не верно, поскольку замыкания используются не только для асинхронного кода <br>

6. Какие методы существуют для контроля асинхронных операций в JavaScript? <br>
    - a) `async` и `await` <br>
      Да, `async` и `await` используются для упрощения работы с промисами, но используются не только они <br>
    - b) `setTimeout` и `setInterval` <br>
      Да, эти функции используются для управления асинхронными операциями через задержки и интервалы, но используются не только они <br>
    - c) `Promise.all()` и `Promise.race()` <br>
      Да, эти методы `Promise` используются для агрегации результатов нескольких промисов, но используются не только они  <br>
    - d) Все вышеперечисленные <br>
      Верно потому что все указанные варианты используются для управления асинхронными операциями <br>

7. В чем разница между операторами `==` и `===` в JavaScript? <br>
    - a) `==` сравнивает по значению, а `===` по типу и значению <br>
      Не верно потому что `==` также учитывает типы после приведения типов <br>
    - b) `==` выполняет автоматическое приведение типов, тогда как `===` сравнивает значения и типы без приведения <br>
      Верно, это основное различие между этими операторами <br>
    - c) `==` используется только для строк, а `===` только для чисел <br>
      Не верно потому что оба оператора могут использоваться для любых типов <br>
    - d) Нет разницы; это просто два разных способа написания одного и того же оператора <br>
      Не верно, так как между `==` и `===` есть существенное различие в поведении <br>

8. Что такое IIFE в JavaScript? <br>
    - a) Немедленно вызываемое функциональное выражение <br>
      Верно потому что IIFE (Immediately Invoked Function Expression) - это функция, которая выполняется сразу после ее создания <br>
    - b) Интерфейс внутренней функциональности элемента <br>
      Не верно, так как это определение не относится к IIFE <br>
    - c) Индикатор интерактивной ошибки выполнения <br>
      Не верно, IIFE не имеет отношения к ошибкам выполнения <br>
    - d) Независимо исполняемая файловая среда <br>
      Не верно, так как IIFE связано с функциями, а не файловыми средами <br>
9. Какой будет результат сравнения `0 == ""` в JavaScript? <br>
    - a) `true` <br>
      Верно потому что JavaScript выполнит приведение типов, и 0 и пустая строка будут преобразованы к false. <br>
    - b) `false` <br>
      Не верно, несмотря на то, что значения различных типов, после приведения типов они оба считаются ложными значениями. <br>
    - c) TypeError <br>
      Не верно, JavaScript не выдаст ошибку типа при сравнении этих значений. <br>
    - d) ReferenceError <br>
      Не верно, так как это валидное сравнение значений в JavaScript. <br>

10. Что делает оператор `??` в JavaScript? <br>
    - a) Сравнивает два значения на равенство без приведения типов <br>
      Не верно, оператор `??` не выполняет сравнение. <br>
    - b) Возвращает правый операнд, если левый не `null` и не `undefined` <br>
      Не верно, возвращает левый операнд, если он не `null` и не `undefined`. <br>
    - c) Возвращает левый операнд, если он не `null` и не `undefined`, иначе возвращает правый <br>
      Верно, это определение оператора нулевого слияния. <br>
    - d) Удаляет свойство из объекта <br>
      Не верно, оператор `??` не используется для удаления свойств из объектов. <br>

11. Каков будет результат выполнения `Boolean([])` в JavaScript? <br>
    - a) `true` <br>
      Верно, потому что пустой массив преобразуется в `true`. <br>
    - b) `false` <br>
      Не верно, пустой массив не является ложным значением. <br>
    - c) `null` <br>
      Не верно, `Boolean` функция не возвращает `null`. <br>
    - d) `undefined` <br>
      Не верно, функция `Boolean` не возвращает `undefined`. <br>

12. Что такое Promise в JavaScript? <br>
    - a) Callback функция <br>
      Не верно, Promise не является callback функцией. <br>
    - b) Объект, представляющий возможное будущее значение или ошибку <br>
      Верно, так как Promise используется для асинхронных операций. <br>
    - c) Глобальный объект JavaScript <br>
      Не верно, Promise является частью JavaScript, но не глобальным объектом. <br>
    - d) Синтаксическая конструкция для обработки исключений <br>
      Не верно, это определение больше подходит для try/catch. <br>

13. Какой метод используется для превращения JSON строки в объект JavaScript? <br>
    - a) `JSON.parse()` <br>
      Верно, `JSON.parse()` преобразует строку JSON в объект JavaScript. <br>
    - b) `JSON.stringify()` <br>
      Не верно, `JSON.stringify()` преобразует объект JavaScript в строку JSON. <br>
    - c) `Object.fromString()` <br>
      Не верно, в JavaScript нет метода `Object.fromString()`. <br>
    - d) `parseJSON()` <br>
      Не верно, правильный метод для этой операции — `JSON.parse()`. <br>

14. Какой метод добавляет один или несколько элементов в конец массива? <br>
    - a) `unshift()` <br>
      Не верно, `unshift()` добавляет элементы в начало массива. <br>
    - b) `push()` <br>
      Верно, так как `push()` добавляет один или несколько элементов в конец массива. <br>
    - c) `pop()` <br>
      Не верно, `pop()` удаляет последний элемент из массива. <br>
    - d) `shift()` <br>
      Не верно, `shift()` удаляет первый элемент из массива. <br>

15. Что такое Полифилл в контексте веб-разработки? <br>
    - a) Элемент дизайна в CSS <br>
      Не верно, полифилл не относится к дизайну. <br>
    - b) Ошибка в JavaScript <br>
      Не верно, полифилл не является ошибкой. <br>
    - c) Фрагмент кода, реализующий функционал, который не поддерживается текущим браузером <br>
      Верно, полифиллы используются для эмуляции недостающих функций. <br>
    - d) API браузера для работы с мультимедиа <br>
      Не верно, это определение не характеризует полифилл. <br>

16. Что такое hoisting в JavaScript? <br>
    - a) Динамическое назначение контекста выполнения функции <br>
      Не верно, hoisting не связан с динамическим назначением контекста. <br>
    - b) Поднятие объявления переменных и функций в верх текущей области видимости <br>
      Верно, hoisting означает поднятие объявлений в начало. <br>
    - c) Автоматическое преобразование типов при сравнении <br>
      Не верно, это процесс, не связанный с hoisting. <br>
    - d) Способ объявления переменных в ES6 <br>
      Не верно, hoisting присутствует в JavaScript и до ES6. <br>

17. Что делает оператор `delete` в JavaScript? <br>
    - a) Удаляет свойство из объекта <br>
      Верно, `delete` удаляет указанное свойство из объекта. <br>
    - b) Вызывает сборщик мусора для удаления неиспользуемых переменных <br>
      Не верно, оператор `delete` прямо не влияет на сборку мусора. <br>
    - c) Удаляет элемент из массива <br>
      Не верно, хоть и удаляет элемент, оставляет пустой слот. <br>
    - d) Полностью удаляет переменную из памяти <br>
      Не верно, оператор `delete` не может удалить переменные, объявленные через `var`, `let` или `const`. <br>

18. Какой из ниже перечисленных типов данных является примитивным в JavaScript? <br>
    - a) Строка (String) <br>
      Верно, строка является примитивным типом данных. <br>
    - b) Массив (Array) <br>
      Не верно, массивы являются объектами. <br>
    - c) Объект (Object) <br>
      Не верно, объект не является примитивным типом данных. <br>
    - d) Функция (Function) <br>
      Не верно, функции являются объектами высшего порядка. <br>

19. Для чего используется ключевое слово `const` в JavaScript? <br>
    - a) Для объявления переменной, значение которой не может быть изменено <br>
      Верно, `const` создает константу, которая не может быть переназначена. <br>
    - b) Для создания условных конструкций <br>
      Не верно, `const` не используется для создания условных конструкций. <br>
    - c) Для объявления анонимных функций <br>
      Не верно, `const` используется для объявления переменных, а не функций. <br>
    - d) Для определения констант времени выполнения <br>
      Не верно, хотя `const` определяет константу, она должна быть присвоена при объявлении. <br>

20. Как в JavaScript создать копию объекта?
    - a) `Object.assign({}, obj)`<br>
      Верно, это один из способов создать поверхностную копию объекта.
    - b) `Object.copy(obj)`<br>
      Не верно, в JavaScript нет встроенного метода `Object.copy`.  
    - c) `obj.clone()`<br>
      Не верно, объекты JavaScript по умолчанию не имеют метода `clone`.  
    - d) `{ ...obj }`<br>
      Верно, это современный способ создать поверхностную копию объекта через spread оператор.  
