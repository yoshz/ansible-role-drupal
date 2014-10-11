drupal
======

An Ansible role for configuring rsyslog/logrotate for Drupal.

The rsyslog configuration will forward all log messages of Drupal to the separate file /var/log/drupal.log.
The lograte configuration will lograte the file each day for 14 days.

The syslog module in your Drupal installation should be enabled.


Requirements
------------

Rsyslog and logrotate should be installed.


Role Variables
--------------

See `defaults/main.yml` for possible configuration.


Dependencies
------------

None


License
-------

MIT
