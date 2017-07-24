# Cloud Provider IP Ranges

## Amazon AWS
 * https://ip-ranges.amazonaws.com/ip-ranges.json

## CloudFlare
 * IPv4: https://www.cloudflare.com/ips-v4
 * IPv6: https://www.cloudflare.com/ips-v6

## Microsoft Azure
 * https://www.microsoft.com/en-gb/download/details.aspx?id=41653

## Google Cloud
 * Managed via SPF records:
 
```
$ dig txt _cloud-netblocks.googleusercontent.com +short
 -> "v=spf1 include:_cloud-netblocks1.googleusercontent.com include:_cloud-netblocks2.googleusercontent.com include:_cloud-netblocks3.googleusercontent.com ?all"
 
$ dig txt _cloud-netblocks1.googleusercontent.com +short
$ dig txt _cloud-netblocks2.googleusercontent.com +short
$ dig txt _cloud-netblocks3.googleusercontent.com +short
```

