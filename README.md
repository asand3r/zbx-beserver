# zbx-beserver
Zabbix template for Veritas/Symantec Backup Exec server
Rate it on Zabbix Share if template was helpful: https://share.zabbix.com/cat-app/backup/veritas-simantec-backup-exec-server

The template give you ability to discover backup jobs and retrieve their statuses and total received bytes like on image below:
![Latest Data](https://sun9-4.userapi.com/c857424/v857424416/109d50/yEaIQqXdcoc.jpg)


## Dependencies
- FreeTDS for MS SQL Server support

## Features
- Backup jobs LLD rule
- BE Server Windows Service monitoring

## Installation
1. Install and configure FreeTDS on your Zabbix Server to support establishing ODBC connections with MS SQL Server
2. Inport template file
3. Set macroses {$BE.USER} and {$BE.PASSWORD} on template or host level
