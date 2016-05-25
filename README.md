# Apache-2.4-suPHP-0.72-Installer
Upgrade Apache and suPHP in CentOS Web Panel

cd /usr/local/src

wget -c https://raw.githubusercontent.com/StoneSpiral/Apache-2.4-suPHP-0.72-Installer/StoneSpiral-patch-1/apache-upgrade.sh

chmod +x apache-upgrade.sh

sh apache-upgrade.sh | tee /var/log/apache_upgrade.log
