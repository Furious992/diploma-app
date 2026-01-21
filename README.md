# Diploma App Перцев Максим Андреевич

В этом репозитории находится тестовое приложение для дипломного проекта.

Приложение представляет собой простой веб-сервис на базе nginx, который используется для демонстрации:
- контейнеризации с помощью Docker,
- публикации образа в DockerHub,
- работы CI/CD пайплайна,
- автоматического деплоя в Kubernetes.

Для проекта настроен GitHub Actions, который при изменении кода автоматически собирает Docker-образ, публикует его в registry и разворачивает новую версию приложения в кластере.

![](https://github.com/Furious992/diploma-app/blob/main/screen/dockerhub.png)
![](https://github.com/Furious992/diploma-app/blob/main/screen/reposecret.png)
![](https://github.com/Furious992/diploma-app/blob/main/screen/failokactions.png)
