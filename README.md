# 2.7_pack


1. **Передача пакетов на сервер вручную**.
В Диске будут все файлы для скрипта.
ссылка: https://drive.google.com/drive/folders/1Mq3PWUrzzn2FB2xanx1U3hJRWP7udEGI?usp=sharing

(Есть разные виды файлов, например как tar.gz, zip, whl)

#### 1. Установка пакетов происходит с командой:

```bash
sudo python2 -m easy_install ./package_name"
```
#### 2. некоторые файлы придется распоковать, перейти к ним и установить.

1. Пакеты передаются на сервер через команду:
   ```bash
   scp -P 2*** /путь/к/файлам/*.whl administrator.ru:/home/administrator/...
   ```

2. Подключение по SSH:
   ```bash
   ssh administrator.ru -p 2***
   ```
   
