# fallout-terminal-solver
Fallout terminal solver for those who have trouble with the terminal hacking.

**Setup:**

Put `80-fallout.conf` in `/etc/lighttpd/conf-enabled/`

Put all other files in `/var/www/html/fallout-terminal-solver`

**Set permissions:**

```
sudo chown -R www-data:www-data /var/www/html/fallout-terminal-solver
sudo chmod 755 /var/www/html/fallout-terminal-solver
sudo chmod 644 /var/www/html/fallout-terminal-solver/*
```

**Restart lighttpd:**

`sudo systemctl restart lighttpd`

accessible at `http://YOUR-IP/fallout`

If you do not want to host locally (which can be done on a Pi 4 2GB) you can use the [online version](https://amec0e.github.io/fallout-terminal-solver/)

This is free to use and modify as you see fit
