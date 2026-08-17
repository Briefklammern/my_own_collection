# Ansible Collection - my_own_namespace.yandex_cloud_elk

Documentation for the collection.

В коллекции используется роль `roles/tasks/main.yml`, которая вызывает модуль `plugins/modules/my_own_module.py`, который создает файл по заданному пути и с заданным содержимым.
Путь `path_env` и содержимое `content_env` для роли задано в `roles/defaults/main.yml`.
