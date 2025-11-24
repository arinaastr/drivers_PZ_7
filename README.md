# MAI Practice 7

## Выполненные действия:

### 1. Клонирование ядра Linux
```bash
git clone --depth 1 --branch v6.8 https://github.com/torvalds/linux.git
```

### 2. Создание структуры драйвера
- Создана папка: linux/drivers/net/ethernet/mai_driver/
- Скопирован драйвер: mai_practice6_driver.c
- Создан Kconfig для конфигурации
- Создан Makefile для сборки

### 3. Модификация ядра
1. Добавлена строка в drivers/net/ethernet/Kconfig
2. Добавлена строка в drivers/net/ethernet/Makefile

### 4. Создан патч
Патч-файл: mai_practice7.patch. При запуске `make menuconfig` открывается окно, где в драйверах лежит добавленный драйвер МАИ
<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/8326ea75-aab8-4d44-855f-6cb09255b4b3" />
