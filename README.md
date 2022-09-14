# Mortem backup script

This uses inotify to watch your mortem file and make a copy.

If you choose to use the included systemd script, please run it as a user so that the home directory can resolve correctly.

```
systemctl --user enable mortem-bak
systemctl --user start mortem-bak
```

