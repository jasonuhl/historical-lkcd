# historical-lkcd

This is an archive of my past work on the Linux Kernel Crash Dump
project.  The most notable piece of this is support for polling I/O,
which made LKCD dramatically more robust (it's designed to run while
the kernel is panicking, which means the usual interrupt-driven I/O
path isn't reliable).  There are also some patches to improve
scalability to hundreds of processors.

LKCD was eventually supplanted by kexec/kdump, so it's unlikely that
anyone would want to run this code nowadays.


## License

This code is free software; you can redistribute it and/or modify
it under the terms of version 2 of the GNU General Public License as
published by the Free Software Foundation.

This code is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this code; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
