![Cover](https://github.com/saurane/Turkish-Blocklist/blob/master/srnsss.png)

<div align="center">
    <!-- License -->
    <img src="https://img.shields.io/badge/License-MPL 2.0-orange.svg?longCache=true&style=for-the-badge"
      alt="Lisans-MPL-2.0" />
  <!-- Last Updated -->
    <img src="https://img.shields.io/badge/Updated-Jan 13, 2022-green.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- Status -->
    <img src="https://img.shields.io/badge/Status-Unstable-red.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
</div>

------------
<div align="center">
  <h1>DNS ve Adblocker için Türkçe Tabanlı Reklam ve İzleyici Engelleme</h1>
</div>


------------

| İstemci | DNS filtresi | Adblock filtresi | Can Sıkıcı Öğeler filtresi |
| ------------ | ------------ | ------------ | ------------ |
| Pi-hole | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt "Link") | - | - |
| uBlock Origin ~ AdGuard | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt "Link") | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock-filter.txt "Link") | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/annoyances-filter.txt "Link") | 
| DNSCloak | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/wildcards.txt "Link") | - | - |
| Unbound | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf "Link") | - | - |
| dnsmasq | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf "Link") | - | - |
| AdAway | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt "Link") | - | - |
| Windows Hosts | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win "Link") | - | - |
| Plain List | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/plain.txt "Link") | - | - |

> ***Adblock Filtresi:*** Alan adının adres bölümlerine göre engeller. Örnek: example.com/javascript/ads.js - example.com/haber/analytics.js<br/>
> ***DNS Filtresi:*** Alan adı tabanlı engeller. Örnek: example.com - ads.example.com - analytics.example.com<br/>
> ***Can Sıkıcı Öğeler Filtresi:*** Sitelerdeki gereksiz araçları engeller. Örneğin; açılır bildirimler, widget'lar, sosyal medya araçları, abone ol butonları, vb. gibi.<br/>
> ***Not:*** AdGuard ve uBlock Origin gibi adblock söz dizimini kullanan reklam engelleyiciler için tüm filtreleri kullanmanız tavsiye edilir.


## Tespit ve araştırma yöntemleri
[AdGuard](https://adguard.com/), [NextDNS](https://nextdns.io/), [Fiddler](https://www.telerik.com/fiddler), [HTTP Debugger](https://www.httpdebugger.com/), [Portmaster](https://safing.io/portmaster/), Subdomain Finder, URL Scan

## Listenin Temel Amacı
Bu listede sadece yerel reklam ve izleyici adresleri bulunmaktadır, eğer tam bir koruma sağlamak istiyorsanız [1Hosts](https://github.com/badmojr/1Hosts), [Energized](https://github.com/EnergizedProtection/block) veya [oisd](https://github.com/ookangzheng/dbl-oisd-nl) listeleri arasından en az birisiyle beraber kullanmanız tavsiye edilir.

## Sorunlar ve İstekler
İstemci desteği, liste sorunu veya diğer sorunları [E-posta](mailto:saurane@protonmail.com) veya [GitHub](https://github.com/saurane/Turkish-Blocklist/issues) üzerinden bildirebilirsiniz.
