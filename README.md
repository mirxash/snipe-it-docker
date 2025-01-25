mkdir -p /root/snipe-it/apache-config
cd /root/snipe-it
mkdir -p /var/www/snipeit
sudo chmod -R 755 /var/www/snipeit 
sudo chown -R 1000:1000 /var/www/snipeit
docker compose up -d
