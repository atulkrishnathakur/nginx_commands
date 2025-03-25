# nginx server commands

## how to know nginx is active or not
```
atul@atul-Lenovo-G570:~$ sudo systemctl status nginx

```
## How to stop nginx
- If you reboot your system then nginx will be active again
```
atul@atul-Lenovo-G570:~$ sudo systemctl stop nginx
```

## How to disable nginx
- If you disable nginx then nginx can not be active if you reboot system
```
atul@atul-Lenovo-G570:~$ sudo systemctl disable nginx

```
