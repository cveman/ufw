# ufw

sudo ufw default deny incoming;
sudo ufw default allow outgoing;
sudo ufw allow out 80/tcp;
sudo ufw allow out 443/tcp;
sudo ufw allow out 443/udp;
sudo systemctl enable ufw;
sudo ufw status;
