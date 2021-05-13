+++
title = "Обновление Ubuntu 20.04/20.10 до 21.04"
description = "Обновление Ubuntu 20.04/20.10 до 21.04"
date = 2021-05-11T12:45:07+03:00
draft = false
tags = [
"ubuntu"
]
categories = [
"Администрирование",
]
slug = "ubuntu_update"
+++

22 апреля вышел новый релиз ubuntu 21.04.
Из заметных нововведений стоит отметить, что Ubuntu 21.04 по умолчанию использует Wayland. А это значит, 
что приложения созданные с помощью Electron и Flutter автоматически используют преимущества Wayland для более плавной графики и лучшего масштабирования.

Как пример, ваш любимый VS code, должен начать работать еще лучше.
Почитать о всех изменениях можно на официальной странице релиза [Ubuntu.com](https://ubuntu.com/blog/ubuntu-21-04-is-here
)
<!--more-->
1. Для начала зайдем в *Software Updater*
    <img src="/img/update_ubuntu/all_update.png" width="500">
    и обновим все устаревшие пакеты.

2. Делаем перезагрузку.
3. После перезагрузки заходим в *Software & Update*
    <img src="/img/update_ubuntu/update_manager.png" width="400">
    вкладка *Updates* ставим *For any new version*
    <img src="/img/update_ubuntu/full_update.png" width="500">
   
4. После этого снова заходим в *Software Updater* и жмем *Upgrade...*
   <img src="/img/update_ubuntu/upgrade.png" width="450">
    далее высветится окно с общей информацией о том что будет обновлено, жмем так же *Upgrade*
   
5. Profit
   <img src="/img/update_ubuntu/profit.png" width="500">