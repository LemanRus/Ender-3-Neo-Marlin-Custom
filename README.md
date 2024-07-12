# Marlin Configuration for Creality Ender 3 Neo

This repository contains customized Marlin firmware configuration files for the Creality Ender 3 Neo 3D printer. The configurations are designed to optimize performance and print quality.

## Repository URL

[Ender-3-Neo-Marlin-Custom](https://github.com/LemanRus/Ender-3-Neo-Marlin-Custom)

## Features

- Nozzle temperature increased to 300°C
- Bed temperature increased to 110°C
- Linear advance enabled
- Bed leveling using UBL (Unified Bed Leveling) with 25 points
- Russian language set by default (can be changed in the configuration)
- Enabled Z-axis nozzle offset wizard and UBL setup wizard

## Requirements

- Marlin firmware version 2.1.2.4
- Visual Studio Code with the Auto Build Marlin extension (recommended) or another build method

## Installation Instructions

1. **Download Marlin Firmware**

    Download Marlin version 2.1.2.4 from the [official Marlin repository](https://github.com/MarlinFirmware/Marlin/releases/tag/2.1.2.4).

2. **Unpack Marlin**

    Unpack the downloaded Marlin firmware to a directory on your computer.

3. **Download Configuration Files**

    Clone or download the configuration files from this repository:
    ```bash
    git clone https://github.com/LemanRus/Ender-3-Neo-Marlin-Custom
    cd Ender-3-Neo-Marlin-Custom
    ```

4. **Replace Marlin Configuration**

    Copy the configuration files from this repository and replace the corresponding files in the unpacked Marlin directory.

    ```bash
    cp -r Ender-3-Neo-Marlin-Custom/* /path/to/unpacked/Marlin/Marlin/
    ```

5. **Build Firmware**

    Open the Marlin firmware directory in Visual Studio Code. Use the Auto Build Marlin extension to build the firmware, or use your preferred build method.

    - Open VSCode and install the [Auto Build Marlin](https://marketplace.visualstudio.com/items?itemName=marlinfirmware.auto-build) extension if you haven't already.
    - Open the Marlin firmware directory.
    - Click on the Auto Build Marlin icon on the left sidebar.
    - Click the "Build" button to compile the firmware.

6. **Upload Firmware to Printer**

    Follow the standard process to upload the compiled firmware to your Creality Ender 3 Neo.

## Support

If you encounter any issues or have questions, please open an issue in this repository.

## License

This project is licensed under the GPLv3 License.

---

# Настройка Marlin для Creality Ender 3 Neo

Этот репозиторий содержит файлы настроек прошивки Marlin для 3D-принтера Creality Ender 3 Neo. Конфигурации разработаны для оптимизации производительности и качества печати.

## URL репозитория

[Ender-3-Neo-Marlin-Custom](https://github.com/LemanRus/Ender-3-Neo-Marlin-Custom)

## Возможности

- Температура сопла поднята до 300°C
- Температура стола поднята до 110°C
- Активирован Linear advance
- Выравнивание стола методом UBL (Unified Bed Leveling) по 25 точкам
- Русский язык по умолчанию (можно заменить в конфигурации)
- Активированы мастер настройки смещения сопла по оси Z и мастер настройки UBL

## Требования

- Прошивка Marlin версии 2.1.2.4
- Visual Studio Code с расширением Auto Build Marlin (рекомендуется) или другой метод сборки

## Инструкции по установке

1. **Скачайте прошивку Marlin**

    Скачайте Marlin версии 2.1.2.4 из [официального репозитория Marlin](https://github.com/MarlinFirmware/Marlin/releases/tag/2.1.2.4).

2. **Распакуйте Marlin**

    Распакуйте скачанную прошивку Marlin в директорию на вашем компьютере.

3. **Скачайте файлы конфигурации**

    Клонируйте или скачайте файлы конфигурации из этого репозитория:
    ```bash
    git clone https://github.com/LemanRus/Ender-3-Neo-Marlin-Custom
    cd Ender-3-Neo-Marlin-Custom
    ```

4. **Замените конфигурацию Marlin**

    Скопируйте файлы конфигурации из этого репозитория и замените соответствующие файлы в распакованной директории Marlin.

    ```bash
    cp -r Ender-3-Neo-Marlin-Custom/* /path/to/unpacked/Marlin/Marlin/
    ```

5. **Соберите прошивку**

    Откройте директорию прошивки Marlin в Visual Studio Code. Используйте расширение Auto Build Marlin для сборки прошивки или используйте предпочитаемый метод сборки.

    - Откройте VSCode и установите расширение [Auto Build Marlin](https://marketplace.visualstudio.com/items?itemName=marlinfirmware.auto-build), если еще не установили.
    - Откройте директорию прошивки Marlin.
    - Нажмите на иконку Auto Build Marlin на левой боковой панели.
    - Нажмите кнопку "Build" для компиляции прошивки.

6. **Загрузите прошивку в принтер**

    Следуйте стандартному процессу загрузки скомпилированной прошивки в ваш Creality Ender 3 Neo.

## Поддержка

Если у вас возникли проблемы или вопросы, пожалуйста, откройте тикет в этом репозитории.

## Лицензия

Этот проект лицензирован под лицензией GPLv3.
