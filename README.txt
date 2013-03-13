GENTOO vm BUILT FOR I686 FOR DEV + TESTING. 

Since this is a 8GB VM with a very generic kernel compliation there is a lot of room for optimization and specialization of subsequent branches. 

The VM ws all setup and installed with 512MB ram in a windows host with 1 CP
host os has ONLY FREE SOFTWARE!!!
the most restrictive licencing involved in this build is for vbox
Inculdes:
PYTHONs.pERL. 
Portage updated.
syslog-ng set up for default logging
vixie-cron for cron daemon services

REMOTE ACCES is not enabled ::: sshd :::
Adding sshd to the default runlevel
# rc-update add sshd default
you will need to set up /etc/inittab for serial console access!!
gentoolkit is in this

KDE installed, but untested. 
dhcp networking was set up and was working with 4.2.6 virtual box

Some additional tools that I did not know enough about but may prove useful are
http://www.gentoo.org/doc/en/handbook/handbook-x86.xml?part=3&chap=4
In general there is alot of information in the handbook for most setups.

the man pages for portage and emerge are among the first pages to read and understand.

released under same GPL or applicible license of gentoo .

