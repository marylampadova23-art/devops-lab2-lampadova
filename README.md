# DevOps Lab 2

Лабораторная работа №2 по настройке CI/CD для Docker-приложения.

В проекте настроен GitHub Actions pipeline, который автоматически:

- запускается при push в ветку main;
- собирает Docker-образ;
- авторизуется в Docker Hub через GitHub Secrets;
- публикует образ `marylampadova/my-flask-app:latest`;
- выполняет условный шаг деплоя.

Отчет по лабораторной работе находится в файле `lab2/lab2_report.md`.
