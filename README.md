# FAMP stack (HTTP/HTTPS) meta-template
Bastille meta-template to install the Apache HTTP Server, MariaDB and PHP (FAMP stack).

* https://github.com/jail-templates/apache-https
* https://github.com/jail-templates/php
* https://github.com/jail-templates/mariadb

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/famp-https
```

## Apply template
```
bastille template $JAIL jail-templates/famp-https
```

## Support
Templates will be maintained until their respective software version is end-of-life. Repositories will then be archived and removed from any meta-templates.

If you have a question, suggestion or find a bug, please let us know via an Issues in the relevant repository or send us an email.

## License
All templates are distributed under the 3-Clause BSD License. See `LICENSE` in every template repository for more information.
