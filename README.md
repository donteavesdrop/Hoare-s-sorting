
# Проект: Сортировка Хоара на основе очереди

## Описание проекта

Данный проект реализует алгоритм быстрой сортировки (сортировка Хоара) с использованием пользовательской структуры данных очереди. Программа генерирует случайные числа, помещает их в очередь, а затем сортирует с помощью метода `QuicksortNoPivot`. Результаты работы алгоритма, включая время сортировки, выводятся в консоль.

## Структура проекта

1. **Program.cs**: Основной файл приложения, где происходит генерация случайных чисел и вызов метода сортировки. Здесь также измеряется время выполнения сортировки.

2. **HoareSort.cs**: Файл, содержащий реализацию алгоритма быстрой сортировки без использования медианного элемента. Включает основной метод `QuicksortNoPivot`.

3. **Queue.cs**: Реализация пользовательской очереди, поддерживающей основные операции, такие как добавление и извлечение элементов, доступ к элементам по индексу и замену элементов.

## Алгоритм

### Сортировка Хоара

Сортировка Хоара (или быстрая сортировка) — это эффективный алгоритм сортировки, который разделяет массив на подмассивы, основанные на значении опорного элемента, и рекурсивно сортирует каждый подмассив. В данном проекте опорный элемент не используется, вместо этого происходит обмен значениями между элементами.

### Пользовательская очередь

Очередь реализована как список, поддерживающий следующие операции:
- **Enqueue**: добавление элемента в конец очереди.
- **Dequeu**: извлечение первого элемента из очереди.
- **ElementAt**: доступ к элементу по индексу.
- **Replace**: замена элемента по индексу.
- **SwapElements**: обмен местами двух элементов очереди.



## Пример вывода

Пример вывода в консоль после запуска программы:

![image](https://github.com/user-attachments/assets/4866dafa-cf35-449e-a7b1-8f3aeb650ed6)


