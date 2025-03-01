# Домашнее задание к занятию " `Защита хоста` " - `Сулименков Алексей`

---

## Задание 1

1. Установите eCryptfs.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.
4. В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

### Ответ

<details> <summary>Исходный каталог пользователя</summary>

![free](https://github.com/biparasite/DB-13-02HW/blob/main/task-1.1.png "free")

</details>

<details> <summary>Зашифрованный каталог пользователя/summary>

![free](https://github.com/biparasite/DB-13-02HW/blob/main/task-1.2.png "free")

</details>

---

## Задание 2

1. Установите поддержку LUKS.
2. Создайте небольшой раздел, например, 100 Мб.
3. Зашифруйте созданный раздел с помощью LUKS.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

### Ответ

<details> <summary>Установка cryptosetup</summary>

![cryptosetup](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.1.png "cryptosetup")

</details>

<details> <summary>Создайте LUKS-раздела с типом luks2</summary>

![cryptosetup](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.2.png "cryptosetup")

</details>

<details> <summary>luksOpen - создние устройства ввода-вывода</summary>

![luksOpen](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.3.png "luksOpen")

</details>

<details> <summary>Проверка существования устройства ввода-вывода</summary>

![luksOpen](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.4.png "luksOpen")

</details>

<details> <summary>Форматирование</summary>

![mkfs.ext4](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.5.png "mkfs.ext4")

</details>

<details> <summary>Монтирование диска</summary>

![mount](https://github.com/biparasite/DB-13-02HW/blob/main/task-2.6.png "mount")

</details>
