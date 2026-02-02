# МІНІСТЕРСТВО ОСВІТИ І НАУКИ УКРАЇНИ  
## КИЇВСЬКИЙ ФАХОВИЙ КОЛЕДЖ ЗВ'ЯЗКУ  

---

# ЗВІТ  
## Про виконання лабораторної роботи №2  
### з дисципліни «Операційні системи»  

**Тема:**  
_«Знайомство з інтерфейсом та можливостями ОС Linux»_

---

### Виконала  
студентка групи **БІКС-33**  
**Руда Дарина Сергіївна**

### Перевірив  
**Сушанова Вікторія Сергіївна**

---

**Київ — 2026**

---

## Мета роботи
Знайомство з інтерфейсами ОС Linux.  
Отримання практичних навичок роботи в середовищах ОС Linux та мобільної ОС – їх графічною оболонкою, входом і виходом з системи, ознайомлення зі структурою робочого столу, вивчення основних дій та налаштувань при роботі в системі.

---

## Завдання для попередньої підготовки
- Прочитати теоретичні відомості до лабораторної роботи  
- Скласти словник базових англійських термінів  
- Опрацювати онлайн-курс **Cisco Networking Academy NDG Linux Essentials**:
  - Chapter 3 — Working in Linux  
  - Chapter 4 — Open Source Software and Licensing  
- Пройти тестування:
  - Chapter 03 Exam  
  - Chapter 04 Exam  
- Дати визначення поняттям:
  - CLI-режим  
  - Термінал на основі графічного інтерфейсу користувача  
  - Віртуальний термінал  

---

## 1. Dictionary of Basic English Terms

- **CLI (Command Line Interface)** – A text-based interface used to interact with the operating system, where the user types commands via a keyboard.
- **Terminal** – An application that provides access to the command line within a graphical Linux environment.
- **Virtual Terminal** – A text-only Linux mode that operates without a graphical interface.
- **Kernel** – The core of the operating system that manages hardware resources.
- **Process** – An instance of a running program.
- **Shell** – A command-line interpreter that processes user input (Bash, Zsh).

---

## 2. Опрацьовані навчальні матеріали
Було опрацьовано навчальні матеріали онлайн-курсу Cisco Networking Academy **NDG Linux Essentials**, а саме:
- Chapter 3 — Working in Linux  
- Chapter 4 — Open Source Software and Licensing  

---

## 3. Пройдені тести
- Chapter 03 Exam  
- Chapter 04 Exam  

---

## 4. Визначення основних понять

- **CLI-режим** — режим роботи операційної системи, у якому керування здійснюється шляхом введення текстових команд без використання графічного інтерфейсу.
- **Термінал на основі GUI** — програма в графічному середовищі, що емулює командний рядок.
- **Віртуальний термінал** — окрема текстова сесія Linux, доступна незалежно від графічної оболонки.

---

## Хід роботи

### Підготовка середовища
Для роботи з ОС Linux було встановлено **Oracle VM VirtualBox** на ОС Windows.  
З офіційного сайту завантажено **Fedora Workstation 43 (x86_64)**.

Параметри ВМ:
- Оперативна пам’ять: **4096 МБ**
- Процесор: **2 ядра**
- Режим запуску: **Live ISO**

---

## 1. Робота в графічному режимі ОС Linux (GNOME)

### Основні компоненти GNOME
- **Activities (Огляд)** — перегляд усіх відкритих вікон
- **Dash** — панель швидкого доступу
- **Пошук** — миттєвий пошук програм
- **Workspaces** — динамічні робочі столи
- **Quick Settings** — керування мережею, звуком та живленням

---

### 1.2 Запуск програм

1. **Через панель швидкого запуску (Dash)**  
   Натискання на іконку програми.

2. **Через пошук у меню (Activities)**  
   Натискання клавіші `Super` та введення назви програми.

3. **Через Show Applications**  
   Натискання кнопки з дев’ятьма крапками.

4. **Через Alt + F2**  
   Введення назви програми (наприклад, `firefox`, `gnome-terminal`).

---

### 1.3 Вихід з системи та завершення роботи

- **Зміна користувача:** Log Out  
- **Перезавантаження:** Restart  
- **Вимкнення:** Power Off  

---

## 2. Робота в середовищі мобільної ОС (iOS)

### 2.1 Головне меню
- Робочі столи з іконками та віджетами  
- App Library  
- Control Center  

### 2.2 Налаштування
- Wi-Fi / Bluetooth  
- Екран та яскравість  
- Face ID і код-пароль  
- Приватність і безпека  

### 2.3 Комбінації кнопок
- Скріншот  
- Екстрений виклик  
- Примусове перезавантаження  

### 2.4 Живлення
- Режим низького заряду  
- Оптимізоване заряджання  
- Перегляд стану акумулятора  

---

## Відповіді на контрольні запитання

### 1. Приклади серверних додатків Linux
- MySQL, PostgreSQL, MariaDB, MongoDB  
- Postfix, Exim, Dovecot  
- vsftpd, Samba, Nextcloud  

### 2. Порівняння оболонок
- sh, csh, bash, tcsh, ksh, zsh  

### 3. Менеджери пакетів
- RPM-based: dnf, yum  
- Debian-based: apt, dpkg  
- Інші: pacman, snap, flatpak  

### 4. Засоби безпеки
- DAC (rwx)  
- SELinux  
- firewalld, nftables  
- SSH-ключі  

### 5. Актуальність віртуалізації
- Ізоляція  
- Тестування  
- Snapshots  

### 6. Контейнеризація
Контейнери (Docker) використовують ядро хоста та є значно легшими за ВМ.

### 7. Відкрите ПЗ
**Переваги:** безкоштовність, прозорість  
**Недоліки:** складність налаштування, менше підтримки  

### 8. Віртуальні консолі (TTY)
- Ctrl + Alt + F1–F6  
- Можливість керування системою без GUI  

### 9. Графічна консоль
У Fedora графічна оболонка зазвичай працює на TTY1 або TTY2.

### 10. Реєстрація під одним ім’ям
Linux дозволяє багаторазовий вхід під одним акаунтом одночасно.

---

## Conclusion

In the course of this laboratory work, I successfully deployed and configured Fedora Workstation 43 using Oracle VM VirtualBox.  
I explored the GNOME graphical interface, application launching methods, power management, and mobile OS features.  
This work confirmed the flexibility and efficiency of Linux systems and highlighted the importance of virtualization in modern IT.

