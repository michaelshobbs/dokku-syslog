Simple docker syslog plugin for dokku
=========================

Project: https://github.com/dokku/dokku & https://docs.docker.com/engine/admin/logging/syslog

Requirements
------------
* Dokku version `0.8.x` or higher

Installation
-----------
```
$ dokku plugin:install https://github.com/michaelshobbs/dokku-syslog.git
```

Commands
--------
```
$ dokku help
    syslog:info                                   show status of running container
    syslog:server <server-url>                    set remote syslog server
```

## Contributing

Feel free to fork and create a Pull Request. (Please add your name to AUTHORS)

## License

MIT
