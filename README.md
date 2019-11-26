# zbx-beserver
Zabbix template for Veritas/Symantec Backup Exec server

## Dependencies
- FreeTDS for MS SQL Server support

## Features
- Backup jobs LLD rule
- BE Server Windows Service monitoring

## Installation
1. Install and configure FreeTDS on your Zabbix Server to support establishing ODBC connections with MS SQL Server
2. Inport template file
3. Set macroses {$BE.USER} and {$BE.PASSWORD} on template or host level
