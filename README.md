# DXVK

A Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.
Оригинальный репозиторий [DXVK](https://github.com/doitsujin/dxvk)

## Описание форка

Данный форк - кастоманая версия DXVK, специально для модификации [S.T.A.L.K.E.R. Belarus](https://vk.cc/cuGXl4). 
Стабильность других игр с данной версией библиотеки не гарантируется...

## Сборка проекта

Сборка проекта настраивалась под Visual Studio 2019 (v142 компиляторы) и Windows 10 SDK.

Для сборки проекта необходимо запустить решение `dxvk.sln` и выбрать один из доступных вариантов сборки (`x86` или `x64`).
Сборка данного репозитория настраивалась только под `Windows`