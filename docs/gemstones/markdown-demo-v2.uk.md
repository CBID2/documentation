---
title: Markdown Demo
author: Einstein
contributors: Dr. Ben Dover, Sweet Gypsy Rose, Anna
tested_with: 8.5
tags:
  - зразок
  - crowdin
  - markdown
---

# Огляд

!!! WARNING "ПОПЕРЕДЖЕННЯ"

    Не сприймайте серйозно те, що ви можете прочитати в цьому документі.

Як ви можете зрозуміти, це досить дурний приклад, призначений для перевірки деяких проблем з перекладом, які ми маємо. Але оскільки проблеми ще не вирішено, ми збираємося дещо змінити файл, щоб побачити його ефект. Хоча писати весело!

Цей посібник демонструє популярні теги Markdown, які використовуються на [https://docs.rockylinux.org](https://docs.rockylinux.org), а також містить тег admonitions, який не є частиною стандартних тегів Markdown.

## Демо

> Це приклад цитати. Гарно відформатований.

Іноді ви побачите _це_.

Як щодо маленького **bold face**

У більшості випадків це прямий текст.

Іноді потрібно показати `команду`

Або кілька команд:

```
dnf install my_stapler
dnf update my_pencil
dnf remove my_notepad
systemctl enable my_stapler
```

В інших випадках вам потрібні марковані або пронумеровані списки:

- Думаю, у вас є мій степлер
- Якщо подумати, я навіть не можу знайти свій компас
- Якщо ні, будь ласка, принаймні поверніть мені олівець
- Мені це точно потрібно

1. Я не знав, що тобі це потрібно
2. Ось твій зламаний олівець
3. Заточувати його марно

І вам може знадобитися попередження:

!!! TIP "ПІДКАЗКА"

    Олівці та степлери справді старовинні.

Часто, коли команда має кілька параметрів або вам потрібно вказати особливості, ви можете використовувати таблицю для визначення речей:

| Інструмент | Використання                            | Додаткова інформація                                                                  |
| ---------- | --------------------------------------- | ------------------------------------------------------------------------------------- |
| олівець    | написання або друк                      | часто замінюють пером                                                                 |
| перо       | написання або друк                      | часто замінюють стилусом                                                              |
| стилус     | запис або друк на електронному пристрої | іноді замінюється клавіатурою                                                         |
| клавіатура | запис або друк на електронному пристрої | жодного разу не замінювали - використовували до повного наповнення харчовими крихтами |
| блокнот    | робити нотатки                          | замінити інколи несправну пам’ять                                                     |