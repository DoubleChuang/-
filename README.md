
[目錄位置]
 
網頁 目錄為 /usr/local/apache/htdocs/
BT	 目錄為 /BT
samba目錄為 /BT
FTP	 目錄為 /

[連線]
transmission: http://ip:9091
FTP			: ftp://ip
 


開機自啟 /etc/rc.local

ftp:
/etc/init.d/vsftpd start

samba:
/etc/init.d/smb start

apache:
/usr/local/apache/bin/apachectl start

transmission(BT):
transmission-daemon

mysql:
/usr/local/mysql/bin/mysqld_safe --user=mysql &

紅外線:
/etc/init.d/lircd start
irexec &

cvbs輸出:
cd /root/stmfb
./insmod.sh &
