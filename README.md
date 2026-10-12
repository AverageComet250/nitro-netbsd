# Service Files for the Nitro Init System on NetBSD

These are based loosely on `/etc/rc.d` and the manpages around the various
services.

**_They are still a work in progress!_**

Symlink `getty@` as wanted (I recommend `constty` and `ttyE{1..3}`). Currently
`network` assumes you're using wifi and dhcp on `iwm0` - edit it as needed.

`nitro` is an amazing piece of software written by Leah Neukirchen
<leah@vuxu.org>, check it out on her [git](https://git.vuxu.org/nitro/) or her
[gh](https://github.com/leahneukirchen/nitro).
