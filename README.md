# devuan-lxc-template
the templates to create a [devuan](https://devuan.org/) [lxc](https://linuxcontainers.org) container.

Devuan GNU+Linux is a fork of Debian without systemd.

By default it will download devuan ascii. You can however choose to use jessie, ceres or sid instead.

To manually install it:

* **lxc-devuan** goes into `/usr/share/lxc/templates/` (remember to `chmod +x` it!)
* **devuan.userns.conf** and **devuan.common.conf** go into `/usr/share/lxc/config/`

To make things quicker for myself I wrote a small script to automate it

`chmod +x install.sh && ./install.sh`
