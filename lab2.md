# МІНІСТЕРСТВО ОСВІТИ І НАУКИ УКРАЇНИ  
## КИЇВСЬКИЙ ФАХОВИЙ КОЛЕДЖ ЗВ'ЯЗКУ  

---

# ЗВІТ  
## Про виконання лабораторної роботи №2  
### з дисципліни «Операційні системи»  

**Тема:**  
Знайомство з інтерфейсом та можливостями ОС Linux

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
Отримання практичних навичок роботи в середовищах ОС Linux та мобільної ОС,
їх графічною оболонкою, входом і виходом з системи, ознайомлення зі
структурою робочого столу, вивчення основних дій та налаштувань.

---

## Завдання для попередньої підготовки
- Ознайомлення з теоретичними відомостями
- Складання словника базових англійських термінів
- Проходження курсу **Cisco NDG Linux Essentials**
- Проходження тестів Chapter 03 та Chapter 04
- Надання визначень CLI, GUI Terminal, Virtual Terminal

---

## 1. Dictionary of Basic English Terms

- **CLI (Command Line Interface)** — text-based interface for OS interaction  
- **Terminal** — GUI application for CLI access  
- **Virtual Terminal** — text-only Linux session  
- **Kernel** — OS core managing hardware  
- **Process** — running program instance  
- **Shell** — command interpreter (Bash, Zsh)

---

## 2. Опрацьовані матеріали
- Chapter 3 — Working in Linux  
- Chapter 4 — Open Source Software and Licensing  

---

## 3. Пройдені тести
- Chapter 03 Exam  
- Chapter 04 Exam  

---

## 4. Визначення основних понять

**CLI-режим** — керування ОС через текстові команди  
**Термінал GUI** — емулятор командного рядка  
**Віртуальний термінал** — незалежна текстова сесія Linux

---

## Хід роботи

### Підготовка середовища
Встановлено **Oracle VM VirtualBox** на ОС Windows.  
Завантажено **Fedora Workstation 43 (x86_64)**.  

Параметри:
- RAM: 4096 МБ  
- CPU: 2 ядра  
- Запуск: Live ISO  

---

## 1. Робота в GNOME

### Основні компоненти
- Activities  
- Dash  
- Пошук  
- Workspaces  
- Quick Settings  

![GNOME Overview](screenshots/gnome-overview.png)

---

### 1.2 Запуск програм

**Через Dash**
![Dash Launch](screenshots/dash-launch.png)

**Через пошук**
![Search](screenshots/search-launch.png)

**Show Applications**
![Show Apps](screenshots/show-apps.png)

**Alt + F2** — запуск через команду

---

### 1.3 Завершення роботи

**Log Out**
![Logout](screenshots/logout.png)

**Restart**
![Restart](screenshots/restart.png)

**Power Off**
![Power Off](screenshots/poweroff.png)

---

## 2. Мобільна ОС (iOS)

### Інтерфейс
- Робочі столи
- App Library
- Control Center

### Налаштування
- Wi-Fi / Bluetooth
- Екран і яскравість
- Face ID
- Приватність

### Кнопки
- Скріншот
- Екстрений виклик
- Примусове перезавантаження

### Живлення
- Low Power Mode
- Оптимізоване заряджання
- Стан акумулятора

---

## Відповіді на контрольні запитання

### 1. Серверні додатки
MySQL, PostgreSQL, MariaDB, MongoDB, Postfix, Dovecot, Samba, Nextcloud

### 2. Оболонки
sh, csh, bash, tcsh, ksh, zsh

### 3. Менеджери пакетів
dnf, yum, apt, dpkg, pacman, snap, flatpak

### 4. Безпека
DAC, SELinux, firewalld, SSH-ключі

### 5. Віртуалізація
Ізоляція, тестування, snapshots

### 6. Контейнеризація
Docker — легша за ВМ, використовує ядро хоста

### 7. Відкрите ПЗ
Плюси: безкоштовність, прозорість  
Мінуси: складність налаштування

### 8. TTY
Ctrl+Alt+F1–F6 — текстові консолі

### 9. Графічна консоль
Fedora — TTY1 / TTY2

### 10. Багатосеансність
Можливий багаторазовий вхід під одним акаунтом

---

## Conclusion
The laboratory work demonstrated the flexibility of Linux systems,
the usability of GNOME, and the importance of virtualization
for modern IT education and practice.
