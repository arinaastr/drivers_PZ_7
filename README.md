# MAI Practice 7: Интеграция драйвера в ядро Linux

## Выполненные действия:

### 1. Клонирование ядра Linux
```bash
git clone --depth 1 --branch v6.8 https://github.com/torvalds/linux.git
```

###2. Создание структуры драйвера
- Создана папка: linux/drivers/net/ethernet/mai_driver/

- Скопирован драйвер: mai_practice6_driver.c

- Создан Kconfig для конфигурации

- Создан Makefile для сборки

### 3. Модификация ядра
1. Добавлена строка в drivers/net/ethernet/Kconfig

2. Добавлена строка в drivers/net/ethernet/Makefile

### 4. Создан патч
Патч-файл: mai_practice7.patch
