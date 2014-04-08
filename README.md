make-jailed-nginx
=================

This is a small script, `make-jailed-nginx`, which automates setting up a
chrooted ("jailed") nginx server on Arch Linux. The procedure itself is taken
from the [Arch Wiki](https://wiki.archlinux.org/index.php/Nginx#Installation_in_a_chroot).

Jailing a web server limits the capabilities of an attacker who has gained
unauthorized access to the system.

Running the script with no arguments runs the setup process with default
values. It can take a few optional parameters; run

    make-jailed-nginx --help

for details.

