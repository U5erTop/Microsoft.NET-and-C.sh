## Темы заданий:
1. Обзор методов.
2. Различия между процедурами и функциями.
3. Работа методов - примеры.
4. Управляющая структура return.
5. Использование сторожевых операторов (Guard Clauses).
6. Сторожевые операторы для защиты номинального варианта.
7. Использование ref и out аргументов в методах.
---
## Решения к первым 10 заданиям:

### Задача 1

```csharp
// 1. Метод для суммирования двух чисел
static int Sum(int a, int b)
{
    return a + b;
}
```

### Задача 2

```csharp
// 2. Метод для суммирования двух чисел
static int Sum(int a, int b)
{
    return a + b;
}
```

### Задача 3

```csharp
// 3. Максимум из трех чисел
static int MaxOfThree(int a, int b, int c)
{
    int max = a;
    if (b > max) max = b;
    if (c > max) max = c;
    return max;
}
```

### Задача 4

```csharp
// 4. Проверка четности
static bool IsEven(int n)
{
    return n % 2 == 0;
}
```

### Задача 5

```csharp
// 5. Проверка четности
static bool IsEven(int n)
{
    return n % 2 == 0;
}
```

### Задача 6

```csharp
// 6. Проверка четности
static bool IsEven(int n)
{
    return n % 2 == 0;
}
```

### Задача 7

```csharp
// 7. Суммирование двух чисел
static int Sum(int a, int b)
{
    return a + b;
}
```

### Задача 8

```csharp
// 8. Метод, выводящий все числа в диапазоне от a до b
static void PrintRange(int a, int b)
{
    for (int i = a; i <= b; i++)
        Console.WriteLine(i);
}
```

### Задача 9

```csharp
// 9. Суммирование двух чисел
static int Sum(int a, int b)
{
    return a + b;
}
```

### Задача 10

```csharp
// 10. Метод, выводящий все числа в диапазоне от a до b
static void PrintRange(int a, int b)
{
    for (int i = a; i <= b; i++)
        Console.WriteLine(i);
}
```
