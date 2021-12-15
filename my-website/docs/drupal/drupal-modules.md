---
sidebar_position: 2
---

# Contrib modules

The common set of Drupal modules used in Oyster Drupal projects and there recommended setup and configuration.

## Stage File Proxy
Stage File Proxy is a general solution for getting production files on a development server on demand. It saves you time and disk space by sending requests to your development environment's files directory to the production environment and making a copy of the production file in your development site. You should not need to enable this module in production.

[https://www.drupal.org/project/stage_file_proxy](https://www.drupal.org/project/stage_file_proxy)

## Environment Indicator
This module will help you to keep sane while working on your different environments by adding a configurable color bar to each one of your environments.

[https://www.drupal.org/project/environment_indicator](https://www.drupal.org/project/environment_indicator)

### Development
```php
$config['environment_indicator.indicator']['fg_color'] = '#ffffff';
$config['environment_indicator.indicator']['bg_color'] = '#00aa00';
$config['environment_indicator.indicator']['name'] = 'Development';
```

### UAT
```php 
$config['environment_indicator.indicator']['fg_color'] = '#ffffff';
$config['environment_indicator.indicator']['bg_color'] = '#0000aa';
$config['environment_indicator.indicator']['name'] = 'UAT';
```

### Live
```php
$config['environment_indicator.indicator']['fg_color'] = '#ffffff';
$config['environment_indicator.indicator']['bg_color'] = '#aa0000';
$config['environment_indicator.indicator']['name'] = 'Live';
```