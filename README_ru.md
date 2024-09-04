<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Zoraxy для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/zoraxy.svg)](https://ci-apps.yunohost.org/ci/apps/zoraxy/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/zoraxy.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/zoraxy.maintain.svg)

[![Установите Zoraxy с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zoraxy)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Zoraxy быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Zoraxy is a new kid in reverse-proxy world written in Go, designed to simplify and streamline web routing and proxying. Zoraxy simplifies the process of setting up a reverse proxy, It serves as an intermediary between client requests and backend servers, effectively managing traffic flow. Whether you're running a small personal website or managing a complex web infrastructure, Zoraxy is designed to make these tasks accessible to all, regardless of your networking expertise.


**Поставляемая версия:** 3.1.1~ynh1

## Снимки экрана

![Снимок экрана Zoraxy](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://zoraxy.arozos.com/index.html>
- Официальная документация администратора: <https://github.com/tobychui/zoraxy/wiki/Getting-Started>
- Репозиторий кода главной ветки приложения: <https://github.com/tobychui/zoraxy>
- Магазин YunoHost: <https://apps.yunohost.org/app/zoraxy>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/zoraxy_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
или
sudo yunohost app upgrade zoraxy -u https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
