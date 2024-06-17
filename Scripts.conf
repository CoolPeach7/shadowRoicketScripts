# Best Shadowrocket Rules (https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever)
# by Moshel and Johnshall
# build time: UTC 2024-06-16 23:01:56

[General]
# 默认关闭 ipv6 支持，如果需要请手动开启
ipv6 = true
bypass-system = true
skip-proxy = 192.168.0.0/16, 10.0.0.0/8, 172.16.0.0/12, localhost, *.local, e.crashlytics.com, captive.apple.com, sequoia.apple.com, seed-sequoia.siri.apple.com
bypass-tun = 10.0.0.0/8,100.64.0.0/10,127.0.0.0/8,169.254.0.0/16,172.16.0.0/12,192.0.0.0/24,192.0.2.0/24,192.88.99.0/24,192.168.0.0/16,198.18.0.0/15,198.51.100.0/24,203.0.113.0/24,224.0.0.0/4,255.255.255.255/32
dns-server = https://1.12.12.12/dns-query, https://223.5.5.5/dns-query
[Rule]
#
# 国内外划分，对中国网站直连，外国网站代理。
#
# 不包含广告过滤
#

DOMAIN-SUFFIX,ampproject.org,PROXY # Google AMP issue#237

# 手工定义的 Proxy 列表
#TED
DOMAIN-SUFFIX,tedcdn.com,Proxy
#Telegram
DOMAIN-SUFFIX,t.me,Proxy
DOMAIN-SUFFIX,tdesktop.com,Proxy
DOMAIN-SUFFIX,telegra.ph,Proxy
DOMAIN-SUFFIX,telegram.me,Proxy
DOMAIN-SUFFIX,telegram.org,Proxy
DOMAIN-SUFFIX,telesco.pe,Proxy
IP-CIDR,91.108.56.0/22,Proxy
IP-CIDR,91.108.4.0/22,Proxy
IP-CIDR,91.108.8.0/22,Proxy
IP-CIDR,91.108.16.0/22,Proxy
IP-CIDR,91.108.12.0/22,Proxy
IP-CIDR,149.154.160.0/20,Proxy
IP-CIDR,91.105.192.0/23,Proxy
IP-CIDR,91.108.20.0/22,Proxy
IP-CIDR,185.76.151.0/24,Proxy
IP-CIDR,2001:b28:f23d::/48,Proxy
IP-CIDR,2001:b28:f23f::/48,Proxy
IP-CIDR,2001:67c:4e8::/48,Proxy
IP-CIDR,2001:b28:f23c::/48,Proxy
IP-CIDR,2a0a:f280::/32,Proxy
#50 whatsapp
IP-CIDR,18.194.0.0/15,Proxy
IP-CIDR,34.224.0.0/12,Proxy
#183
DOMAIN-SUFFIX,mendeley.com,Proxy
#github
DOMAIN-SUFFIX,raw.githubusercontent.com,Proxy
# DNS Leak
DOMAIN-SUFFIX,dnsleaktest.com,Proxy
DOMAIN-SUFFIX,ipleak.net,Proxy
DOMAIN-SUFFIX,browserleaks.com,Proxy
DOMAIN-SUFFIX,browserleaks.org,Proxy
DOMAIN-SUFFIX,vpnunlimited.com,Proxy
DOMAIN-SUFFIX,whrq.net,Proxy
# Forefront
DOMAIN-SUFFIX,forefront.ai,Proxy
# Mozilla
DOMAIN-SUFFIX,mozilla.org,Proxy
# Txt.fyi
DOMAIN-SUFFIX,txt.fyi,Proxy
# AOL
DOMAIN-SUFFIX,aol.com,Proxy
# Yahoo
DOMAIN-SUFFIX,yahoo.com,Proxy
# Linkedin
DOMAIN-SUFFIX,linkedin.cn,Proxy
DOMAIN-SUFFIX,linkedin.com,Proxy
# Copilot
DOMAIN-SUFFIX,copilot.microsoft.com,Proxy
# hoyolab
DOMAIN-SUFFIX,hoyolab.com,Proxy
# 防止 bing 地区检测
DOMAIN-SUFFIX,location.microsoft.com,Proxy
# GitHub在线编辑器
DOMAIN-SUFFIX,github.dev,Proxy


GEOIP,CN,DIRECT

FINAL,proxy

[URL Rewrite]
^https?://(www.)?(g|google)\.cn https://www.google.com 302


[MITM]
hostname = *.google.cn,*.googlevideo.com

# Made with Love from https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever
