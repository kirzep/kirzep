<div align="center">

<img src="assets/banner.svg" width="100%" alt="kirzep — путь в DevOps: сборка, проверки, релиз">

### Начинающий разработчик · развиваюсь в сторону DevOps

Мне интересно всё, что происходит между кодом и работающим приложением:<br>
**сборки, автоматизация, инфраструктура и понятные релизы.**

[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-20242D?style=flat-square&logo=githubactions&logoColor=94BFFF)](https://github.com/kirzep/RebellioCap/actions)
[![PowerShell](https://img.shields.io/badge/PowerShell-20242D?style=flat-square&logo=powershell&logoColor=94BFFF)](https://github.com/kirzep/RebellioCap/tree/main/scripts)
[![Git](https://img.shields.io/badge/Git-20242D?style=flat-square&logo=git&logoColor=F4A58A)](https://github.com/kirzep?tab=repositories)

</div>

## Практика на реальном проекте

### [RebellioCap](https://github.com/kirzep/RebellioCap)

Приложение для Windows: запись игрового процесса, мгновенные повторы и встроенный видеоредактор. Его стек — **C++20, Rust / Tauri и React / TypeScript**.

Для меня это ещё и практическая площадка для работы со сборками и доставкой ПО:

| Область | Что есть в проекте |
| :--- | :--- |
| **CI** | GitHub Actions: проверки интерфейса, браузерные тесты, тесты C++ и Rust. |
| **Сборки** | Скрипты PowerShell, CMake, закреплённые версии инструментов и зависимостей. |
| **Кэширование** | Кэши npm, Rust и нативных зависимостей vcpkg в CI. |
| **Релизы** | Сборка Windows-установщика, подписанные пакеты обновлений и проверка версии. |
| **Документация** | Архитектура, настройка окружения, инструкции по сборке и ограничения приложения. |

[CI: проверки](https://github.com/kirzep/RebellioCap/blob/main/.github/workflows/desktop-ci.yml) · [Сборка релиза](https://github.com/kirzep/RebellioCap/blob/main/.github/workflows/desktop-release.yml) · [Релизы](https://github.com/kirzep/RebellioCap/releases) · [Документация](https://github.com/kirzep/RebellioCap/tree/main/docs)

<details>
<summary>Посмотреть интерфейс RebellioCap</summary>

<br>
<img src="https://raw.githubusercontent.com/kirzep/RebellioCap/main/docs/screenshots/overview.png" width="100%" alt="Интерфейс RebellioCap: запись и мгновенный повтор; демонстрационные данные">

*Скриншот из документации проекта; показаны демонстрационные данные.*

</details>

## Куда хочу двигаться

Следующий этап — отдельные DevOps-проекты с открытым кодом и документацией. Планирую пройти полный путь: **поднять сервис → автоматизировать доставку → наблюдать за его работой → разобрать сбои**.

- **Linux и сети:** окружение сервиса, права доступа, процессы и диагностика.
- **Docker и CI/CD:** контейнеризация приложения и автоматический деплой.
- **Инфраструктура как код:** воспроизводимое окружение вместо ручной настройки.
- **Наблюдаемость:** метрики, логи и оповещения, которые помогают найти причину проблемы.

Будущие проекты будут появляться здесь по мере реализации.

## Ещё один проект

[**Water Tracker**](https://github.com/kirzep/your-water-tracker) — ранний командный проект для учёта потребления воды: персональная цель, визуализация прогресса и история. JavaScript, HTML и CSS.

---

<div align="center">
<sub>От работающего приложения — к воспроизводимым сборкам и надёжной доставке.</sub>
</div>
