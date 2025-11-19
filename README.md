[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)
[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General)
[comment]: <> (Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)


# The Martian Company's Split (`tmcsplit`)

Javascript GNU Split rewrite.

Splittable with number of parts or maximum bytes per part.

It works both in Node.js and in web browsers
using the
[Crash Javacript](
  https://github.com/themartiancompany/crash-js)
and
[Split File](
  https://github.com/themartiancompany/node-split-file)
modules.

### Installation

You can install and save an entry to your `package.json`
with the following command:

```bash
npm \
  install \
    --save \
    @themartiancompany/tmcsplit
```

You can then run the program with

```bash
npx \
  "tmcsplit"
```

or just with `tmcsplit` if you install
the program system-wide using npm from this source
repository or from the
[NPM Registry](
  https://www.npmjs.com/package/tmcsplit)

```
npm \
  -g \
  install \
    "split-file"
```

or if using GNU make in this repository

```bash
make \
  install
```

**Note:** You may need admin rights (`sudo`,
`su -c` or on Windows `Run as administrator`).

or if you install it as a
[DogeOS](
  https://github.com/themartiancompany/dogeos)
package from the
[Ur](
  https://github.com/themartiancompany)

```bash
ur \
  tmcsplit
```

### Documentation

Upon installation the manual can be accessed with
`man tmcsplit` but really it's the same as
GNU Split, so you can also refer to `man split`
for what is it implemented.

# License

This software by Pellegrino Prevete is released
under the terms of the GNU Affero General Public License
version 3.
