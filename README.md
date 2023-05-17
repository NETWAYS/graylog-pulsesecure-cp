# PulseSecure Content Pack

This PulseSecure content pack can be used to collect and enrich your log data for
a efficent analyzing and visibility of the user lgoings. This conetent pack only
handling messages from your PulseSecure who are related to user logins.


## Includes
* UDP Input on port 1514 with a grok extractor
* PulseSecure grok patttern
* "PulseSecure Global" Stream with all extracted messages with one filter
rule
* Stream "PulseSecure Failed Logins" contains all messages with status failed based on a filter rule
* Dashboards named "PulseSecure"

## Requirements

* A PulseSecure gateway which is forwarding messages to the graylog-server on port 514
* Portforwarding for incoming messages on port 514 to port 1514
* Leading Wildcard Searches enabled in graylog.conf:  allow_leading_wildcard_searches = true

## License

Copyright (C) 2017 NETWAYS GmbH <info@netways.de>
                   Daniel Neuberger

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
