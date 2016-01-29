# Скрипты для автоматизации управления серверами

## Предварительные требования

Используется [Ansible 2.0](https://ansible.com/). Для установки на MacOS:

```bash
brew install ansible
```

### Запуск с паролем

Для запуска установки на чистом сервере нужно выполнять команды с `--ask-pass`. Если падает с ошибкой *ERROR! to use the 'ssh' 
connection type with passwords, you must install the sshpass program* - пользуемся этим руководством http://thornelabs.net/2014/02/09/ansible-os-x-mavericks-you-must-install-the-sshpass-program.html
