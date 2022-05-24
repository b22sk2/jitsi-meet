1. apt-get install -y apt-transport-https
2. apt-get update
3. apt-get install -y jitsi-meet
4. mkdir -p /etc/letsencrypt/renewal-hooks/deploy/ 
5. touch /etc/letsencrypt/renewal-hooks/deploy/0000-coturn-certbot-deploy.sh
6. chmod +x /etc/letsencrypt/renewal-hooks/deploy/0000-coturn-certbot-deploy.sh
7. /usr/share/jitsi-meet/scripts/install-letsencrypt-cert.sh 
