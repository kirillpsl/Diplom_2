# Diplom_2
## О проекте
Тестирование API учебного сервиса [Stellar Burgers](https://stellarburgers.nomoreparties.site/).

Его документация: [Документация](https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/api-documentation.pdf)

## Технологии в проекте
|              | версия |
|--------------|--------|
| Java         | 11     |
| JUnit        | 4.13.2 |
| Maven        | 4.0.0  |
| Rest Assured | 5.3.1  |
| Allure       | 2.15.0 |
| Aspectj      | 1.9.7  |
| Gson         | 2.10.1 |

## Как запустить
<ol>
<li>Клонируй репозиторий</li>

```
git clone https://github.com/kirillpsl/Diplom_2
```
<li>Для запуска тестов</li>

```
mvn clean test
```
<li>Для просмотра отчета в Allure</li>

```
mvn allure:serve
```
</ol>