Итоговая контрольная работа по основному блоку
Урок 1. Контрольная работа
Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе Разработчик. Мы должны убедится, что базовое знакомство с IT прошло успешно.

Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

1. Создание репозитория в GitHub.

2. Создание проекта

1. В терминале VSC командой <dotnet new console> был создан проект на C#.
2. В терминале VSC командой <git init> был создан локальный репозиторий проекта.

3. Cоздание блок-схемы решения задачи

4. Написание кода на C#

1. После каждого шага выполнялась отправка промежуточных коммитов в удаленный репозиторий командами

2.git add
3.git commit
3.git push

5.Описана функция CreateArray() для создания исходного массива с получением данных от пользователя.
6.Описана функция ShowArray() для вывода массива в консоль.
7.Описана функция ResultArray() по блок-схеме, которая непосредственно выполняет поставленную задачу.
8.Описание вызова функций.
7.Тестирование на примерах и дополнительных данных.
