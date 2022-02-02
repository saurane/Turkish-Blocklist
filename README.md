![Cover](https://github.com/saurane/Turkish-Blocklist/blob/master/srnsss.png)

<div align="center">
    <!-- Last Updated -->
    <img src="https://img.shields.io/badge/Updated-Jan 25, 2022-green.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- Status -->
    <img src="https://img.shields.io/badge/Status-Stable-blue.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- License -->
    <img src="https://img.shields.io/badge/License-MPL 2.0-orange.svg?longCache=true&style=for-the-badge"
      alt="Lisans-MPL-2.0" />
</div>

------------
<div align="center">
  <h1>DNS ve Adblocker için Türkçe Tabanlı Reklam ve İzleyici Engelleme Projesi</h1>
</div>


------------

| İstemci | DNS filtresi | Xtreme DNS filtresi | Adblock filtresi | Can Sıkıcı Öğeler filtresi |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Pi-hole | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt "RAW") | - | - | - |
| uBlock Origin ~ AdGuard | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/xtreme-dns-filter.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock-filter.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/annoyances-filter.txt "RAW") | 
| DNSCloak | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/wildcards.txt "RAW") | - | - |
| Unbound | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf "RAW") | - | - |
| dnsmasq | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf "RAW") | - | - |
| AdAway | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt "RAW") | - | - |
| Windows Hosts | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win "RAW") | - | - |
| Plain List | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/plain.txt "RAW") | - | - |

> ***Adblock Filtresi:*** Alan adının adres bölümlerine göre engeller. Örnek: example.com/js/ads.js - example.com/js/analytics.js<br/>
> ***DNS Filtresi:*** Alan adı tabanlı engeller. Örnek: example.com - ads.example.com - analytics.example.com<br/>
> ***Can Sıkıcı Öğeler Filtresi:*** Sitelerdeki gereksiz araçları engeller. Örneğin; açılır bildirimler, widget'lar, çerez bildirimleri, sosyal medya araçları, abone ol butonları, vb. gibi.<br/>
> ***Not:*** AdGuard ve uBlock Origin gibi adblock söz dizimini kullanan reklam engelleyiciler için tüm filtreleri kullanmanız tavsiye edilir.


## Tespit ve araştırma yöntemleri
[AdGuard](https://adguard.com/), [NextDNS](https://nextdns.io/), [Fiddler](https://www.telerik.com/fiddler), [HTTP Debugger](https://www.httpdebugger.com/), [Portmaster](https://safing.io/portmaster/), Subdomain Finder, URL Scan

## Listenin Temel Amacı
Bu listede sadece yerel reklam ve izleyici adresleri bulunmaktadır, eğer tam bir koruma sağlamak istiyorsanız [1Hosts](https://github.com/badmojr/1Hosts), [Energized](https://github.com/EnergizedProtection/block) veya [oisd](https://github.com/ookangzheng/dbl-oisd-nl) listeleri arasından en az birisiyle beraber kullanmanız tavsiye edilir.

## Sorunlar ve İstekler
İstemci desteği, liste sorunu veya diğer sorunları E-posta: saurane@protonmail.com veya [GitHub](https://github.com/saurane/Turkish-Blocklist/issues) üzerinden bildirebilirsiniz.
