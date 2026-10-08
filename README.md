<div align="center">

<img src="assets/banner.svg" width="100%" alt="kirzep — DevOps / Automation">

<br>
<sub>Целевой DevOps-стек</sub>

<p>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Linux-Dark.svg" width="36" height="36" alt="Linux" title="Linux"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Bash-Dark.svg" width="36" height="36" alt="Bash" title="Bash"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Git.svg" width="36" height="36" alt="Git" title="Git"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Python-Dark.svg" width="36" height="36" alt="Python" title="Python"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Nginx.svg" width="36" height="36" alt="Nginx" title="Nginx"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/PostgreSQL-Dark.svg" width="36" height="36" alt="PostgreSQL" title="PostgreSQL">
</p>
<p>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GithubActions-Dark.svg" width="36" height="36" alt="GitHub Actions" title="GitHub Actions"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GitLab-Dark.svg" width="36" height="36" alt="GitLab CI" title="GitLab CI"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Jenkins-Dark.svg" width="36" height="36" alt="Jenkins" title="Jenkins"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Docker.svg" width="36" height="36" alt="Docker" title="Docker"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Kubernetes.svg" width="36" height="36" alt="Kubernetes" title="Kubernetes"> &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/helm/helm-original.svg" width="36" height="36" alt="Helm" title="Helm">
</p>
<p>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Terraform-Dark.svg" width="36" height="36" alt="Terraform" title="Terraform"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Ansible.svg" width="36" height="36" alt="Ansible" title="Ansible"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/AWS-Dark.svg" width="36" height="36" alt="AWS" title="AWS"> &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/argocd/argocd-original.svg" width="36" height="36" alt="Argo CD" title="Argo CD"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Prometheus.svg" width="36" height="36" alt="Prometheus" title="Prometheus"> &nbsp; <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Grafana-Dark.svg" width="36" height="36" alt="Grafana" title="Grafana">
</p>

Мне интересно всё, что происходит между кодом и работающим приложением:<br>
**сборки, автоматизация, инфраструктура и понятные релизы.**

Развиваюсь в DevOps через практику: от CI и выпуска приложения<br>
к контейнерам, инфраструктуре как коду и наблюдаемости.

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

## Целевой DevOps-стек

Строю траекторию развития вокруг полного цикла: **код → сборка → инфраструктура → деплой → наблюдение → восстановление**. Ниже — карта технологий, которые хочу закрепить в портфолио; текущая практика со сборками и CI показана выше.

| Направление | Технологии и навыки |
| :--- | :--- |
| **Linux и администрирование** | Ubuntu / Debian, Bash, systemd, пользователи и права, процессы, диски, журналирование. |
| **Сети и веб** | TCP/IP, DNS, HTTP/HTTPS, TLS, SSH, маршрутизация, firewall, Nginx, reverse proxy. |
| **Автоматизация** | Bash, Python, PowerShell, Git, YAML / JSON, API, идемпотентные скрипты. |
| **CI/CD** | GitHub Actions, GitLab CI, тесты, артефакты, кэши, секреты, окружения, версии и откат. |
| **Контейнеры** | Docker, Compose, multi-stage builds, registry, volumes, сети, health checks. |
| **Оркестрация и GitOps** | Kubernetes, Helm, Argo CD, Deployments, Services, probes, ресурсы, RBAC. |
| **Инфраструктура как код** | Terraform / OpenTofu, Ansible, state, модули, provisioning и управление конфигурацией. |
| **Облако** | AWS как основной учебный трек: IAM, VPC, EC2, S3, балансировщики, бюджеты и стоимость. |
| **Наблюдаемость и SRE** | Prometheus, Grafana, Loki, OpenTelemetry, метрики / логи / трейсы, SLI / SLO, алерты, разбор инцидентов. |
| **Безопасность и восстановление** | Минимальные привилегии, OIDC, управление секретами, Trivy, Gitleaks, зависимости, бэкапы и проверка восстановления. |

## Следующие проекты портфолио

Планирую собрать последовательную серию лабораторных проектов. Каждый будет содержать код, схему инфраструктуры, инструкцию запуска и описание принятых решений.

1. **Linux Service Lab** — сервис на Linux, Nginx, TLS, systemd, диагностика и восстановление из бэкапа.
2. **Container Delivery Lab** — приложение с PostgreSQL в Docker Compose, CI/CD, безопасная работа с секретами и откат релиза.
3. **Cloud Infrastructure Lab** — инфраструктура через Terraform / OpenTofu, конфигурация через Ansible, IAM и контроль затрат.
4. **GitOps & Observability Lab** — Kubernetes, Helm, Argo CD, Prometheus / Grafana, централизованные логи и сценарий сбоя.

Проекты буду добавлять по мере реализации. Мой ориентир — показать не только успешный деплой, но и **умение объяснить архитектуру, найти причину сбоя и восстановить сервис**.

## Ещё один проект

[**Water Tracker**](https://github.com/kirzep/your-water-tracker) — ранний командный проект для учёта потребления воды: персональная цель, визуализация прогресса и история. JavaScript, HTML и CSS.

---

<div align="center">
<sub>От работающего приложения — к воспроизводимым сборкам и надёжной доставке.</sub>
</div>
