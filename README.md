## Задание
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## **Описание алгоритма работы кода на C#**

### **Инициализация массива**

1. Создается массив **`array1`** типа **`string`** с 5 элементами: **`"123"`**, **`"23"`**, **`"hello"`**, **`"world"`** и **`"res"`**.
2. Создается массив **`array2`** типа **`string`** с тем же размером, что и массив **`array1`**.

### **Метод `SecondArrayWithIF`**

1. Создается переменная **`count`** и инициализируется значением **`0`**.
2. Выполняется цикл **`for`** с итератором **`i`**, который проходит по всем элементам массива **`array1`**.
3. Если длина текущего элемента **`array1[i]`** не превышает 3 символов, то выполняются следующие действия:
    - Элемент **`array1[i]`** копируется в массив **`array2`** на следующую позицию с помощью переменной **`count`**.
    - Переменная **`count`** инкрементируется.
4. По окончании цикла массив **`array2`** будет содержать только те элементы из **`array1`**, которые имеют длину не более трех символов.

### **Метод `PrintArray`**

1. Принимает в качестве параметра массив **`array`**.
2. Выполняется цикл **`for`** с итератором **`i`**, который проходит по всем элементам массива **`array`**.
3. Каждый элемент массива **`array[i]`** выводится в консоль с помощью метода **`Console.Write`**.
4. После выполнения цикла выводится символ перевода строки с помощью метода **`Console.WriteLine`**.

### **Выполнение кода**

1. Вызывается метод **`SecondArrayWithIF`** с параметрами **`array1`** и **`array2`**.
2. Вызывается метод **`PrintArray`** с параметром **`array2`**.
3. В результате выполнения программы в консоль будет выведен массив **`array2`**, содержащий только те элементы из **`array1`**, которые имеют длину не более трех символов.
