# Mock CAS Server

This is a minimal stand-alone implementation of a [CAS Authentication Server](https://apereo.github.io/cas/index.html), intended for use in unit tests and/or for local/offline development.

A Ruby interpreter is required.

## Usage

Example:
```bash
MOCK_CAS_AUTO_LOGIN=y ./mock_cas
```

See the comments at the top of [mock_cas](mock_cas) for additional configuration options.

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).
