# thought-of-linux
Think about Linux
# Certbot generate wilcard certificate
certbot certonly --force-renewal --manual --preferred-challenges=dns --email jakir.hossin@brainstation-23.com --server https://acme-v02.api.letsencrypt.org/directory -d *.sellzzy.dev
# Getting Apache Access Log for specific time range 
    awk '$4 >= "[30/Jun/2024:14:35:59" && $4 <= "[30/Jun/2024:14:45:59" {print}' /var/log/apache2/access_daktarbhai.log >/root/BS-23/access_daktarbhai_log_30June_14:35-14:45
# Getting Apache Error Log from a specific time range
    awk '/Sun Jun 30/ && $4 >= "14:35:59" && $4 <= "14:45:59" {print}' /var/log/apache2/error_daktarbhai.log >/root/BS-23/error_daktarbhai_30june_14:35-14:45
