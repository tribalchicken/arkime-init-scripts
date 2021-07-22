# arkime-init-scripts

FreeBSD init scripts for Arkime.

Contains an init script for both `arkimecapture` and `arkimeviewer`

Plop them into `/usr/local/etc/rc.d/` and enable by adding the following to `/etc/rc.conf`:

```
arkimecapture_enable="YES"
arkimeviewer_enable="YES"
```

