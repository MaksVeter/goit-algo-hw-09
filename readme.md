
### Порівняння ефективності

**Жадібний алгоритм**:

-   **Часова складність**: O(n), ( n — кількість монет у наборі ). Всі монети перевіряються один раз.
-   **Переваги**: Простий у реалізації, швидкий для невеликих сум.
-   **Недоліки**: Може не давати оптимального рішення для деяких наборів монет (наприклад, при нестандартних номіналах, які не є кратними один одному).

**Динамічне програмування**:

-   **Часова складність**: O(n * m), ( n — сума, m — кількість монет у наборі ). Це залежить від розміру суми та кількості монет.
-   **Переваги**: Завжди знаходить оптимальне рішення для будь-якого набору монет, включаючи нестандартні набори.
-   **Недоліки**: Може бути повільнішим і використовувати більше пам'яті при великих сумах.

### Висновки

-   **Жадібний алгоритм** швидший і легший у реалізації для стандартних наборів монет, але може не завжди знайти оптимальне рішення.
-   **Динамічне програмування** гарантує оптимальне рішення для будь-якого набору монет, але може бути менш ефективним для великих сум або використовувати більше пам'яті.