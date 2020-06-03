# Резервное копирование

Скрипт резервного копирования [backup-data.sh](https://github.com/awesomenmi/borg/blob/master/backup-data.sh) и вывод команд терминала [typescript](https://github.com/awesomenmi/borg/blob/master/typescript).

Содержимое файла /var/log/borg/backup.log - [backup.log](https://github.com/awesomenmi/borg/blob/master/typescript)

Для запуска бэкапа раз в час необходимо выполнить:

```
crontab -e
0 0 * ? * * /home/vagrant/backup-data.sh
```
