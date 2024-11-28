# Лабораторная работа №1 Карасева Дарья 367269
## Project Euler - Problem 8 (Largest Product in a Series)
>
>The four adjacent digits in the 1000-digit number that have the greatest product are 9 x 9 x 8 x 9 = 5832
>
>7316717653133062491922511967442657474235534919493496983520312774506326239578318016984801869478851843858615607891129494954595017379583319528532088055111254069874715852386305071569329096329522744304355766896648950445244523161731856403098711121722383113622298934233803081353362766142828064444866452387493035890729629049156044077239071381051585930796086670172427121883998797908792274921901699720888093776657273330010533678812202354218097512545405947522435258490771167055601360483958644670632441572215539753697817977846174064955149290862569321978468622482839722413756570560574902614079729686524145351004748216637048440319989000889524345065854122758866688116427171479924442928230863465674813919123162824586178664583591245665294765456828489128831426076900422421902267105562632111110937054421750694165896040807198403850962455444362981230987879927244284909188845801561660979191338754992005240636899125607176060588611646710940507754100225698315520005593572972571636269561882670428252483600823257530420752963450
>
>Find the thirteen adjacent digits in the 1000-digit number that have the greatest product. What is the value of this product?

### Problem 8 Solution
1) Монолитная реализация

- С использованием рекурсии
```agda
```
- С использованием хвостовой рекурсии
```agda
```

2) Модульная реализация, где явно разделена генерация последовательности, фильтрация и свёртка
3) Генерация последовательности при помощи отображения
4) Работа со спец. синтаксисом для циклов
5) Работа с бесконечными списками для языков, поддерживающих ленивые коллекции или итераторы как часть языка
6) Реализация на любом удобном для вас традиционном языке программирования для сравнения
```cpp
```

## Project Euler - Problem 23 (Non-Abundant Sums)
>
>A perfect number is a number for which the sum of its proper divisors is exactly equal to the number. For example, the sum of the proper divisors of 28 would be 1 + 2 + 4 + 7 + 14 = 28, which means that 28 is a perfect number.
>
>A number n is called deficient if the sum of its proper divisors is less than n and it is called abundant if this sum exceeds n.
>
>As 12 is the smallest abundant number, 1 + 2 + 3 + 4 + 6 = 16, the smallest number that can be written as the sum of two abundant numbers is 24. By mathematical analysis, it can be shown that all integers greater than 28123 can be written as the sum of two abundant numbers. However, this upper limit cannot be reduced any further by analysis even though it is known that the greatest number that cannot be expressed as the sum of two abundant numbers is less than this limit.
>
>Find the sum of all the positive integers which cannot be written as the sum of two abundant numbers.
