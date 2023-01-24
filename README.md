# Exam-DevOps

1 ЗАДАНИЕ: Собрать образ и проверить его.

Скопировать репозиторий на сервер control, где установлены пакеты Jenkins, ansible и docker. Написать Dockerfile для сборки образа. После того как собрали образ, запустить контейнер локально и проверить его работу.

2 ЗАДАНИЕ: Настройка Jenkins и создание Jenkinsfile

В вашем пайплайне должно быть 2 стейджа это build и deploy, и сделать trigger, чтобы при изменении кода ваше приложение автоматически пересобиралось. В стейдже build вы должны собрать приложение с помощью Dockerfile и запушить его в свой Docker registry на DockerHUB. В стейдже deploy должен запускаться playbook.yaml для запуска вашего приложения на сервера worker01 и worker02 И сделать отправку уведомлений в телеграм.

Ссылки для быстрого поиска: https://www.jenkins.io/doc/book/pipeline/jenkinsfile/ https://docs.docker.com/engine/reference/builder/
