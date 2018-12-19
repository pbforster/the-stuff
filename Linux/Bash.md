# Bash

## mount

```bash
sudo mount -t cifs -o username=<user>,password=<password>,vers=1.0,uid=$(id -u) //<ip-address>/path/to/mount/remote where/to/mount/locally
```
