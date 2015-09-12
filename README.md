# Stylus Death Star Mixin
A stylus mixin that makes a single element death star. You can still add your own styles afterwards but changing some things might make it display incorrectly.

It comes in three types, normal, strict and minimal :
- Normal lets you apply any styles to it, even if makes it display incorrectly
- Strict overrides your styles in favor of the ones in the mixin, I recommend not using this unless you have to
- Minimal is recommended for those who know what they're doing, it doesn't override the styles or omit the unnecesarry ones, your output will be much messier

### How to use:

- in your html add a death star element (the class name doesn't matter)
```HTML
<div class="death-star"></div>
```

- in your stylus file include the mixin
  - either by using @include
  - or by copying and pasting the mixin

- to call the mixin
```stylus
.death-star
  death-star(100px)
```

Have Fun!



## Licence
Stylus Death Star Mixin
(C)CKH4 2015

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
