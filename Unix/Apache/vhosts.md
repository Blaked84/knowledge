# Default vhost

```xml
<VirtualHost *:80>
    DocumentRoot /www/
    ServerName domain.tld
    ServerAlias domain.tld
    <Directory /www/>
                Options Indexes FollowSymLinks MultiViews
                AllowOverride None
                Order allow,deny
                allow from all
                Require all granted
    </Directory>
</VirtualHost>
```

