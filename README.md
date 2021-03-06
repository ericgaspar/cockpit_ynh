# Cockpit Next for YunoHost

[![Integration level](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/cockpit) ![](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)  
[![Install TaskBoard with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cockpit)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install TaskBoard quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
A Kanban-inspired app for keeping track of things that need to get done.
The goal of TaskBoard is to provide a simple and clean interface to a functional and minimal application for keeping track of tasks. It's not trying to be the next Trello or LeanKit.
What TaskBoard does is make it easy to start keeping track of anything you need to get done. The visual aspect of a board allows for easy status checks, and can be motivating for users who want to move their tasks to the next column. 

**Shipped version:** 1.0.2

## Screenshots

![]()

## Demo

* [Official demo]()

## Documentation

 * Official documentation: 
 * YunoHost documentation: https://yunohost.org/#/app_cockpit

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported ? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/cockpit%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/cockpit/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/cockpit%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/cockpit/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/cockpit_ynh/issues
 * App website: http://getcockpit.com/
 * Upstream app repository: https://github.com/agentejo/cockpit
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing --debug
or
sudo yunohost app upgrade cockpit -u https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing --debug
```
