[![License](https://img.shields.io/github/license/Graylog2/graylog2-server.svg)](https://www.gnu.org/licenses/gpl-3.0.txt)

# PulsesSecure Content Pack

This PulseSecure content pack can be used to collect and enrich your log data for
a efficent analyzing and visibility 


## Includes
* TCP and UDP Inputs on port 1514 with extractors using grok
* PulseSecure grok patttern
* "PulseSecure Global" Stream with all extracted messages
* Stream "PulseSecure Failed Logins" contains all messages with failed status
* Dashboards named "PulseSecure"

## Requirements

* A PulseSecure gateway which is forwarding messages to the graylog-server on port 514
* Portforwarding for incoming messages on port 514 to port 1514
* Leading Wildcard Searches enabled in graylog.conf:  allow_leading_wildcard_searches = true


## Screenshots
Will follow soon.

## License
  Copyright (C) 2017  NETWAYS GmbH/Daniel Neuberger info@netways.de

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <http://www.gnu.org/licenses/>.
