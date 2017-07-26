Simple docker syslog plugin for dokku
=========================

Project: https://github.com/dokku/dokku & https://docs.docker.com/engine/admin/logging/syslog

Requirements
------------
* Dokku version `0.10.4` or higher

WARNING: This will (unfortunately) disable `docker logs` for all dokku containers. See [docker docs](https://docs.docker.com/engine/admin/logging/overview/#limitations-of-logging-drivers) for more info

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
    syslog:format <format>                        set remote syslog format (i.e. rfc3164, rfc5424, or rfc5424micro)
```

## Contributing

Feel free to fork and create a Pull Request. (Please add your name to AUTHORS)

## License

MIT
