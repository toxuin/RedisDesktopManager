This fork does not have a Google Analytics and Update Nag enabled.

This fork does not provide binaries of the software, but contains a script for easy compilation (script was deleted from original repo just to make your life harder).

This repo is for my personal use and was not intended for your own, commercial, production, or any other use.

I will not silence you for discussion about how to build a .dmg from latest code as if it would be a piracy (it is, in fact, not a piracy. Code is under LGPL). Freely discuss this matter in Issues.

I will gladly accept all pull requests to improve automated binary production. If you want to make changes to software itself, please contribute to the original repo, author would appreciate that (also, you'd get that bloody subscription for free for a year or so).

You can also contribute build instructions to the wiki of this repo.

How to build a .dmg or a .deb:

        export APP_VERSION=0.8.11aug (or whatever you want)
		export export QTDIR=/Path/to/your/Qt
		cd build
		chmod +x build_package.sh
		./build_package.sh

Below goes the original readme.

#[Redis Desktop Manager](http://redisdesktop.com "Redis Desktop Manager Offical Site")

[Install & Run](http://docs.redisdesktop.com/en/latest/install/) | 
[Quick Start](http://docs.redisdesktop.com/en/latest/quick-start/) |
[Development Guide](http://docs.redisdesktop.com/en/latest/development/) |
[Known issues](http://docs.redisdesktop.com/en/latest/known-issues/) |
:green_apple: [Bountysource](https://www.bountysource.com/teams/redisdesktopmanager)

[![Travis Build Status](https://travis-ci.org/uglide/RedisDesktopManager.svg?branch=0.8.0)](https://travis-ci.org/uglide/RedisDesktopManager) 
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/91mj2ge0lxjf693c/branch/0.8.0?svg=true)](https://ci.appveyor.com/project/uglide/redisdesktopmanager/branch/0.8.0)
[![Coverage Status](https://coveralls.io/repos/uglide/RedisDesktopManager/badge.svg?branch=0.8.0)](https://coveralls.io/r/uglide/RedisDesktopManager?branch=0.8.0)
[![Coverity Scan Build](https://scan.coverity.com/projects/3548/badge.svg)](https://scan.coverity.com/projects/3548)
[![Documentation Status](https://readthedocs.org/projects/redisdesktopmanager/badge/?version=latest)](http://docs.redisdesktop.com/en/latest/?badge=latest)
[![Stories in Progress](https://badge.waffle.io/uglide/redisdesktopmanager.svg?label=in progress&title=In Progress)](http://waffle.io/uglide/redisdesktopmanager)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/uglide/RedisDesktopManager)

Open source cross-platform Redis Desktop Manager based on Qt 5

![Redis Desktop Manager screenshoot](http://redisdesktop.com/static/img/features/all.png?v2)

**Officially Supported platforms** : Windows 7+, Mac OS X 10.11+, Ubuntu 14+, Fedora 22+ (build with automated script)

**Community Supported platforms**: [ArchLinux](https://aur.archlinux.org/packages/redis-desktop-manager/)

**Supported Redis versions** : 2.4, 2.6, 2.8, 3.0+

## Release Schedule
| Release | Original plan | Realized |
| ------- | ------------- | -------- |
| [0.8.7] (https://github.com/uglide/RedisDesktopManager/milestone/23?closed=1) | July 20, 2016 | [July 18, 2016](https://github.com/uglide/RedisDesktopManager/releases/tag/0.8.7) |
| [0.8.7-1] (https://github.com/uglide/RedisDesktopManager/milestone/23?closed=1) | - | [August 02, 2016](https://github.com/uglide/RedisDesktopManager/releases/tag/0.8.7-1) |
| [0.8.8-beta] (https://github.com/uglide/RedisDesktopManager/milestone/24) | August 17, 2016 | |
| [0.8.8] (https://github.com/uglide/RedisDesktopManager/milestone/24) | August 24, 2016 | |
| [0.9.0-beta] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 14, 2016 | |
| [0.9.0] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 21, 2016 | |
| [0.9.1-beta] (https://github.com/uglide/RedisDesktopManager/milestone/22) | Oct 19, 2016 | |
| [0.9.1] (https://github.com/uglide/RedisDesktopManager/milestone/22) | Oct 26, 2016 | |
