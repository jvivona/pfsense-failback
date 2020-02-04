# pfsense-failback
 handle failback of pfsense  when WAN1 comes back online

for up to pfsense 2.4.4

bring down both files to local pfsense root directory -  use   fetch <url>

chmod +x  both files

install cron on pfsense from package manager

add cron job as user root

*/5 * * * *  /root/check_backup_wan


