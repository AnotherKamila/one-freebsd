# one-freebsd
Opennebula contextualization for FreeBSD.

Tested with 11.1-RELEASE and CURRENT (as of Apr 2018).

Install from ports/pkg: available as `sysutils/opennebula-contextualization`.
Then `echo 'vmcontext_enable="YES"' >> /etc/rc.conf`.

Note: It does not make much sense to install this into an existing VM. It should be installed into the image before first boot, so that it can configure networking on first boot.
