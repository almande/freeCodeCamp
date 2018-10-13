---
title: PHP Data Types
localeTitle: Типы данных PHP
---
# Типы данных

Переменные могут хранить данные разных типов, например:

*   Строка («Привет»)
*   Целое число (5)
*   Float (также называемый double) (1.0)
*   Boolean (1 или 0)
*   Массив (массив («I», «am», «an», «array»))
*   объект
*   НОЛЬ
*   Ресурс

## строка

Строка представляет собой последовательность символов. Это может быть любой текст внутри кавычек (один или два):

#### пример

```php
$x = "Hello!"; 
 $y = 'Hello!'; 
```

## целое число

Целочисленный тип данных представляет собой не десятичное число между -2,147,483,648 и 2,147,483,647.

Правила для целых чисел:

*   Целое число должно иметь по крайней мере одну цифру
*   Целое число не должно иметь десятичной точки
*   Целое число может быть как положительным, так и отрицательным
*   Целые числа могут быть указаны в трех форматах: десятичный (на основе 10), шестнадцатеричный (на основе 16 - с префиксом 0x) или восьмеричный (на основе 8 - префикс 0)

#### пример

```php
$x = 5; 
```

## терка

Поплавок (число с плавающей запятой) - это число с десятичной точкой или числом в экспоненциальной форме.

#### пример

```php
$x = 5.01; 
```

## логический

Boolean представляет два возможных состояния: TRUE или FALSE. Булевы часто используются при условном тестировании.

```php
$x = true; 
 $y = false; 
```

## массив

Массив хранит несколько значений в одной переменной.

```php
$colours = array("Blue","Purple","Pink"); 
```

## Значение NULL

Null - это специальный тип данных, который может иметь только одно значение: NULL.  
Переменная типа данных NULL - это переменная, которая не имеет назначенного ей значения.  
Переменные также можно очистить, установив значение в NULL.

**Примечание.** Если переменная создается без значения, ей автоматически присваивается значение NULL.

```php
<?php 
 $x = "Hello world!"; 
 $x = null; 
 ?> 
```

Вывод:  
НОЛЬ

## объект

Объект - это тип данных, в котором хранятся данные и информация о том, как обрабатывать эти данные.  
В PHP объект должен быть явно объявлен.  
Сначала мы должны объявить класс объекта. Класс - это структура, которая может содержать свойства и методы.

**Пример:**

```php
<?php 
 class Car { 
    function Car() { 
        $this->model = "VW"; 
    } 
 } 
 
 // create an object 
 $herbie = new Car(); 
 
 // show object properties 
 echo $herbie->model; 
 ?> 

```