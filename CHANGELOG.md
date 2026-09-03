# awstats Changelog

## 8.0-2

- Add `%if 0%{?suse_version}` macros: `httpd_confdir`, `httpd_logdir`,
  `httpd_service` routing to apache2 paths on SUSE vs httpd on RHEL/Fedora
- Replace all hardcoded `/etc/httpd/conf.d`, `/var/log/httpd`, and
  `httpd.service` references with macros throughout the spec

## 8.0-1

- Initial packaging
