# Shakti: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-shakti.svg?branch=develop)](https://travis-ci.org/platformio/platform-shakti)
[![Build status](https://ci.appveyor.com/api/projects/status/pm59mq539ttp51hd/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-shakti/branch/develop)

Shakti is an open-source initiative by the RISE group at IIT-Madras, which is not only building open source, production grade processors, but also associated components like interconnect fabrics, verification tools, storage controllers, peripheral IPs and SOC tools.  

* [Home](http://platformio.org/platforms/shakti) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/shakti.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = shakti
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-shakti.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/shakti.html).
