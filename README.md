# Arduino Core for SAMD51P20A

This repository contains the source code and configuration files of the Arduino Core
for Atmel's SAMD51P20A processor.

In particular, this adds support for the Adafruit SAMD Boards such as the Feather M0

## Bugs or Issues

* AREF must be tied to 3.3V for dac to work. This is a bug in the SAMD51 silicon.
* USB host mode doesn't work yet


## License and credits

This core has been developed by Arduino LLC in collaboration with Atmel.

```
  Copyright (c) 2015 Arduino LLC.  All right reserved.

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU Lesser General Public
  License as published by the Free Software Foundation; either
  version 2.1 of the License, or (at your option) any later version.

  This library is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
  See the GNU Lesser General Public License for more details.

  You should have received a copy of the GNU Lesser General Public
  License along with this library; if not, write to the Free Software
  Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```
