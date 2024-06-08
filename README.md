# DOS18-onl-DiplomProject
# Дипломный проект
 ФИО: Давыдчик Геннадий Вячеславович\
 Направление: DevOps инжнер\
 Группа: Dos18-Onl\

## Требования к дипломному проекту
* В дипломном проекте должно быть реализовано:\
* выбран общедоступный репозиторий или несколько репозиториев с исходным кодом приложения, состоящего из одного или нескольких микросервисов;
### В нашем случае был выбрано приложение которое будет развернуто на ApacheServer
выполнен fork или сделана копия репозитория;\
автоматизировано создание инфраструктуры для развертывания проекта;\
автоматизированы процессы CI/CD;\
настроен мониторинг инфраструктуры и приложения.\
\
Критерии выполнения:\
Репозитории должен содержать минимальную документацию, описывающую содержимое и процессы сборки и развертывания;\
Инфраструктура должна разворачиваться с нуля запуском одной команды. Все должно быть реализовано по принципам IaC;
CI/CD:\
при коммите в любую ветку репозитория должны запускаться этапы проверки кода линтером, сборки исходного кода, автотесты собранного приложения и загрузка артефактов в хранилище;\
при коммите в основную ветку (master/main) дополнительно должен запускаться автоматический deployment на целевую инфраструктуру;\
Должно отправляться уведомление о результате сборки и развертывания в любой канал (почта, чат).
### В нашем случае. Уведомление отправляются на Телеграм бот настроенного с помощью FatherBot.
