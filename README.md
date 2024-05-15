# thought-of-linux
Think about Linux

# Certbot generate wilcard certificate

certbot certonly --force-renewal --manual --preferred-challenges=dns --email jakir.hossin@brainstation-23.com --server https://acme-v02.api.letsencrypt.org/directory -d *.sellzzy.dev

