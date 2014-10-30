#### OPcache configuration for Drupal 8

In /opt/etc/fpm/fpm-pool-common.conf

from:

    php_admin_flag[opcache.load_comments] = off
    php_admin_flag[opcache.save_comments] = off

to:

    php_admin_flag[opcache.load_comments] = on
    php_admin_flag[opcache.save_comments] = on

#### Enable simpletest.module (Drupal before 8)

We can not enable using web, just use drush

    drush en simpletest
