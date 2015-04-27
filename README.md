# fake-nino-node

This is a clone of [**fng-nino-tools**](https://github.com/corbanworks/fng-nino-tools) just in node.js

A small library providing the ability to validate a UK national insurance number, and generate a fake national insurance number for testing your application.

## Installation

```bash
  npm install fake-nino -g
```

## Usage

```javascript
  // Generate random NINO
  var nino = require('fake-nino');
  console.log(nino.generate());

  // Validate NINO
  if ( nino.validate('EC 55 50 80 A') ) {
        console.log('valid');
  } else {
        console.log('invalid');
  }
```

## Contributing

If you find a bug or are willing to add some enhancement, pull requests are very welcome.

## Release History

* 0.0.1 Initial release

## Legal

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
