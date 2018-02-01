### WARNING: Do not use this Rust code.

This is not a complete implementation of WireGuard. Thus, it is full of known
security vulnerabilities and bugs. There is no group of users that should be 
using the code in this repository here under any circumstances at the moment.

If you're interested in using WireGuard, use the implementation for Linux
[found here](https://git.zx2c4.com/WireGuard/) and described on the 
[main wireguard website](https://www.wireguard.com/).


If you're interested in assisting with the Rust development of WireGuard and 
contributing to this repository by all means dig in and help out. But users: 
stay far away, at least for now.

-------

# wireguard-rs

This is a work in progress for implementing a userspace WireGuard in Rust.

The current plan is to target macOS (utun-compatible operating systems) for
simplicity, but full cross-platform support is the eventual goal. Linux
is next up, and shouldn't require a lot of extra effort to get running.

## License

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License version 2 as
    published by the Free Software Foundation.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.



