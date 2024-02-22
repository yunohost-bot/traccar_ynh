<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Traccar for YunoHost

[![Integration level](https://dash.yunohost.org/integration/traccar.svg)](https://dash.yunohost.org/appci/app/traccar) ![Working status](https://ci-apps.yunohost.org/ci/badges/traccar.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/traccar.maintain.svg)

[![Install Traccar with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traccar)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Traccar quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Traccar is an open source GPS tracking system. It supports more than 200 GPS protocols and more than 2000 models of GPS tracking devices.

### Features

- Real-time GPS tracking
- Driver behaviour monitoring
- Detailed and summary reports
- Geofencing functionality
- Alarms and notifications
- Account and device management
- Email and SMS support


**Shipped version:** 5.12~ynh2

**Demo:** https://www.traccar.org/demo-server/

## Screenshots

![Screenshot of Traccar](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://www.traccar.org/>
* Official admin documentation: <https://www.traccar.org/documentation/>
* Upstream app code repository: <https://github.com/traccar/traccar>
* YunoHost Store: <https://apps.yunohost.org/app/traccar>
* Report a bug: <https://github.com/YunoHost-Apps/traccar_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/traccar_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
or
sudo yunohost app upgrade traccar -u https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>