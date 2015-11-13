README

1.  clock12to24 changes the default 24 hour clock to 12 hour for certain defined locales (US,Egypt,Greece,Albania)
2.  put clock12to24 in /usr/local/bin
3.  call clock12to24 from LIVE rc.local
4.  if persistence is used, clock12to24 will only run once.
5.  clock12to24 should be removed from rc.local on an installed system.

comment:  this script will do nothng on a default a4 live system as the clocks are not defined the way the script assumes.

rev 2 - added additional locale info.

rev 9 - update comments

rev 10 - changed %I (uppercase "eye") to %l (lowercase L)
