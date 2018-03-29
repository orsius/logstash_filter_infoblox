# Infoblox Logstash filters
> forked from [willemdh/logstash_filter_infoblox](https://github.com/willemdh/logstash_filter_infoblox)

Send your Infoblox logs to an Elastic stack and apply filters to enable advanced analysis.

## Usage
- `infoblox.conf`	logstash conf file
- `./dictionnaries/syslogpri.yml`dictionnary used by translate filter
- `./patterns/sec_infloblox` the custom pattern used in `infoblox.conf`
- `infoblox.template`	elasticsearch data mapping
- `readme.md`

:information_source: In case you find a bug or have a feature request, please make an issue on GitHub.

## Copyright
*This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public
License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later
version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the
implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more
details at <http://www.gnu.org/licenses/>.*
