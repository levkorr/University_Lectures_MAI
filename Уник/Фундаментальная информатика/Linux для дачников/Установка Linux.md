Linux на своем ноуте (под Windows)
1. Рекомендованный способ - Windows Subsystem for Linux 2(WSL2)
2. Из PowerShell или cmd.exe с правами администратора: `wsl -install`
3. По умолчанию ставится последняя версия Ubuntu без GUI
4. Какие еще дистрибутивы есть в wsl: `wsl --list -online`
5. Поставить конкретный: `wsl --install -d Ubuntu-24.04`
6. Документация: https://learn.microsoft.com/ru-ru/windows/wsl/install
7. Под WSL по умолчанию ставится версия без GUI
8. Если нужен GUI, нужно обновить пакеты:
   `sudo apt update`
   `sudo apt upgrade`
9. Установить GUI - Ставятся уевые программы
   `sudo apt install ubuntu-desktop`
10. WSLg: https://learn.microsoft.com/en-us/windows/wsl/tutorials/gui-apps

Жертвы MacOS: установить VMware Fusion, скачать образ ISO с сайта ubuntu.com, запустить Fusion, закинуть ISO в него и следовать инструкциям

Dual-boot или установка непосредственно на железо основной ОС - для любителей развлечений