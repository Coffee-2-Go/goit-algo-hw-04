Час сортування злиттям, сек:   0.233525 | 0.015897 | 0.001074
Час сортування вставками, сек: 2.066566 | 0.021213 | 0.000217
Час сортування Timsort, сек:   0.000677 | 0.000065 | 0.000010

# Висновки:
З результатів емпіричних вимірів видно, що алгоритм Timsort (вбудований у функції sorted та sort в Python) працює набагато швидше за інші алгоритми сортування на великих масивах даних через те, що він реалізований на мові програмування С, на відміну від двох інших алгоритмів, які реалізовані безпосередньо на Python.

В той же час сортування злиттям, яке має лінійно-логарифмічну складність, на середніх та великих об'ємах даних є значно ефективнішим за сортування вставками, яке має квадратичну складність. Хоча на малих об'ємах даних сортування вставками є більш ефективним, бо не потребує створення рекурсивих функцій в процесі сортування.
