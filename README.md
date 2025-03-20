Как использовать
Запуск программы:

Скомпилируйте и запустите программу в среде разработки, например, Visual Studio, или с помощью команды dotnet run в терминале (если проект настроен как .NET проект).

Ввод данных:

После запуска программа запросит у вас:

Первое число (целое число).

Второе число (целое число).

Знак операции (один из поддерживаемых символов).

Поддерживаемые операции:

+ — сложение.

- — вычитание.

* — умножение.

/ — деление (целочисленное).

% — остаток от деления (в текущей версии ошибочно реализовано как деление, требуется исправление).

& — побитовое И.

| — побитовое ИЛИ.

^ — побитовое исключающее ИЛИ (XOR).

Пример работы:

Введите первое число: 10
Введите второе число: 3
Введите знак: *
Результат = 30

Обработка ошибок:

Если введены некорректные данные (например, нечисловое значение или неподдерживаемый знак операции), программа сообщит об ошибке:

Некоректное значение!
При делении на ноль программа завершится с ошибкой (в текущей версии отсутствует обработка деления на ноль).

Ограничения
Программа работает только с целыми числами.

Деление на ноль не обрабатывается корректно (может вызвать исключение).

Операция % ошибочно реализована как деление (требуется исправление).
