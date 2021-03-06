---
title: SlickStack (Public Mirrors)
---

# Public Mirrors (SlickStack)

----

### Core Modules

*Main modules of SlickStack's optimized WordPress LEMP stack, including Ubuntu LTS, Nginx, MySQL, PHP-FPM, Redis, and optional LittleBizzy MU plugins.*

* [adminer](/adminer/)
* [clamav](/clamav/)
* [cloudflare](/cloudflare/)
* [craft-cms](/craft-cms/)
* [git](/git/)
* [letsencrypt](/letsencrypt/)
* magento
* mediawiki
* [moodle](/moodle/)
* [mysql](/mysql/)
* [nginx](/nginx/)
* [nginx-fastcgi-cache](/fastcgi-cache/)
* [opencart](/opencart/)
* [openssl](/openssl/)
* [php-fpm](/php-fpm/)
* [php-fpm opcache](/opcache/)
* [postfix](/postfix/)
* [prestashop](/prestashop/)
* [redis](/redis/)
* [ubuntu](/ubuntu/)
* [ufw-firewall](/ufw-firewall/)
* [wordpress-cli](/wp-cli/)
* [wordpress-core](/wordpress/)
* [wordpress-mu-plugins](/mu-plugins/)
* [wordpress-starter-themes](/starter-themes/)


### Core Cron Jobs

*These cron jobs are the most critical part of SlickStack's setup, as they allow your LEMP stack to receive updates to modules and scripts via GitHub.*

* [00-crontab](00-crontab.txt)
* [01-cron-often](01-cron-often.txt)
* [02-cron-regular](02-cron-regular.txt)
* [03-cron-quarter-hourly](03-cron-quarter-hourly.txt)
* [04-cron-half-hourly](04-cron-half-hourly.txt)
* [05-cron-hourly](05-cron-hourly.txt)
* [06-cron-quarter-daily](06-cron-quarter-daily.txt)
* [07-cron-half-daily](07-cron-half-daily.txt)
* [08-cron-daily](08-cron-daily.txt)
* [09-cron-half-weekly](09-cron-half-weekly.txt)
* [10-cron-weekly](10-cron-weekly.txt)
* [11-cron-half-monthly](11-cron-half-monthly.txt)
* [12-cron-monthly](12-cron-monthly.txt)
* [13-cron-sometimes](13-cron-sometimes.txt)

### Core Bash Scripts

*Bash scripts that perform SlickStack's main functions as an active LEMP environment, which are called via cron jobs, and can also be run manually.*

* [ss-check](ss-check.txt)
* [ss-clean](ss-clean.txt)
* [ss-config-sample](ss-config-sample.txt)
* [ss-dump](ss-dump.txt)
* [ss-encrypt](ss-encrypt.txt)
* [ss-import](ss-import.txt)
* [ss-install](ss-install.txt)
* [ss-install-adminer](ss-install-adminer.txt)
* [ss-install-bash](ss-install-bash.txt)
* [ss-install-clamav](ss-install-clamav.txt)
* [ss-install-cron](ss-install-cron.txt)
* ss-install-magento-core
* ss-install-mediawiki-core
* [ss-install-misc](ss-install-misc.txt)
* ss-install-moodle-core
* [ss-install-mysql](ss-install-mysql.txt)
* [ss-install-nginx](ss-install-nginx.txt)
* ss-install-opencart-core
* [ss-install-php](ss-install-php.txt)
* [ss-install-postfix](ss-install-postfix.txt)
* ss-install-prestashop-core
* [ss-install-redis](ss-install-redis.txt)
* [ss-install-ufw](ss-install-ufw.txt)
* [ss-install-wordpress-cli](ss-install-wp.txt)
* [ss-install-wordpress-config](ss-install-wpconfig.txt)
* [ss-install-wordpress-core](ss-install-wordpress.txt)
* [ss-install-wordpress-muplugins](ss-install-muplugins.txt)
* [ss-optimize](ss-optimize.txt)
* [ss-perms](ss-perms.txt)
* [ss-purge](ss-purge.txt)
* [ss-restart](ss-restart.txt)
* [ss-scan](ss-scan.txt)
* [ss-sync](ss-sync.txt)
* [ss-update](ss-update.txt)
* [ss-worker](ss-worker.txt)

### Core Meta Files

*Various meta files that are not part of SlickStack's functionality but provide key information about licensing, general "readme" summary files, etc.*

* [changelog](changelog.md)
* [license](license.md)
* [readme](readme.md)

### References

* https://blog.coinbase.com/container-technologies-at-coinbase-d4ae118dcb6c

----

*Last updated: Aug 18, 2020*
