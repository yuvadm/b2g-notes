# B2G Notes
## Will you accept my pull request?
A collection of notes, scripts and helper files for building [B2G](https://github.com/mozilla-b2g/B2G).

## Build

Check out the settings used in [.userconfig](.userconfig).

Load the udev rules prior to connecting the device:

```bash
$ cp 90-flame.rules /etc/udev/rules.d/
$ sudo udevadm control --reload-rules
```

## Applications

### Twitter

[Macaw](https://marketplace.firefox.com/app/macaw) performs much better than the default Twitter mobile client.

### WhatsApp

[ConnectA2](https://marketplace.firefox.com/app/connecta2) is the only client that does proper push with WhatsApp
