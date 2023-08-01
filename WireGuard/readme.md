Создайте директорию для вашей роли и ее структуру:

```bash
mkdir -p roles/wireguard/{defaults,files,handlers,meta,tasks,templates}
```
В директории tasks создайте файл main.yml и напишите таски для настройки WireGuard
В директории templates создайте файлы шаблонов для конфигурационных файлов WireGuard
Создайте файл site.yml с плейбуком, который использует вашу роль
Запустите плейбук, указав хосты вашего VPN-сервера в файле /etc/ansible/hosts
