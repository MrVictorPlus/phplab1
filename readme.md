# Установка и первая программа на PHP

## 1. Инструкции по запуску проекта

1. Установите PHP или XAMPP.

2. Склонируйте репозиторий проекта.

3. Перейдите в папку с проектом.

4. Запустите сервер командой php -S localhost:8000.

5. Откройте в браузере http://localhost:8000.

## 2. Описание лабораторной работы

Лабораторная работа посвящена созданию простого веб-приложения на PHP. Проект включает в себя базовый PHP-скрипт, который использует встроенный сервер для отображения данных на веб-странице. В рамках работы настроена среда для разработки и обеспечен вывод информации через браузер с использованием таких конструкций PHP, как echo и print.

---

## 3. Краткая документация к проекту

### Основные функции:
- Проект запускается с помощью встроенного сервера PHP.
- Для вывода данных используется стандартный механизм PHP, например, `echo` и `print`.

### Примеры использования:
1. Вывод данных на страницу с использованием `echo` и `print`.
2. Простая работа с переменными и строками, включая конкатенацию и интерполяцию.


---

## 4. Примеры использования проекта

### Вывод данных
```php
<?php
// Вывод с echo
echo "Hello, World with echo!";

// Вывод с print
print "Hello, World with print!";
?>
```

### Работа с переменными
```php
<?php
$days = 288;
$message = "Все возвращаются на работу!";

// Конкатенация строк
echo "Осталось " . $days . " дней. " . $message . "<br>";

// Вывод через интерполяцию
echo "Осталось $days дней. $message<br>";
?>
```

---

## 5. Ответы на контрольные вопросы

1. **Какие способы установки PHP существуют?**  
   - Вручную (скачать с [php.net](https://www.php.net/downloads)).
   - Через XAMPP (установка в комплекте с Apache).

2. **Как проверить, что PHP установлен и работает?**  
   - Выполнить команду `php -v`.
   - Запустить локальный сервер `php -S localhost:8000`.
   - Открыть PHP-файл через Apache (XAMPP).

3. **Чем отличается echo от print?**  
   - `echo` быстрее, поддерживает несколько аргументов.
   - `print` возвращает `1`, можно использовать в выражениях.

---

## 6. Список использованных источников
- [PHP.net](https://www.php.net/)
- [Учебник PHP](https://www.w3schools.com/php/)

---

## 7. Дополнительные важные аспекты
- Использование встроенного сервера PHP удобно для разработки без установки Apache.
- XAMPP подходит для работы с MySQL и phpMyAdmin.
- Для работы с PHP в Windows можно использовать `php.ini` для настройки конфигурации.

