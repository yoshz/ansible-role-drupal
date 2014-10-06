drupal
======

An Ansible role for configuring Drupal rsyslog/logrotate and installing Drush.

The rsyslog configuration will forward all log messages of Drupal to the separate file /var/log/drupal.log.
The lograte configuration will lograte the file each day for 14 days.

The syslog module in your Drupal installation should be enabled.


Requirements
------------

None


Role Variables
--------------

See `defaults/main.yml` for possible configuration.

You can disable logging configuration with the following line:

    drupal_logfile: ~


Dependencies
------------

None

License
-------

MIT