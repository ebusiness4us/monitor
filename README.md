# Monitor

A project to generete and collect VPS data

## Requirements:
- php >= 7.3
- php-sqlite3

## How to install

```
composer require leandrogrando/monitor
```
You will be asked for a token and password.

## Cron config

```
* * * * * cd /path_to_monitor_root && php monitor
```

## Publishing the data
Set up a virtual host point to monitor root
