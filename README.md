![Cover](https://github.com/saurane/Turkish-Blocklist/blob/master/srnsss.png)

<div align="center">
    <!-- Last Updated -->
    <img src="https://img.shields.io/badge/Updated-Feb 16, 2022-green.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- Status -->
    <img src="https://img.shields.io/badge/Status-Stable-blue.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- License -->
    <img src="https://img.shields.io/badge/License-MPL 2.0-orange.svg?longCache=true&style=for-the-badge"
      alt="Lisans-MPL-2.0" />
</div>
<br/>

| İstemci | DNS filtresi | Xtreme DNS filtresi | Adblock filtresi | Can Sıkıcı Öğeler filtresi |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Pi-hole | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt "RAW") | - | - | - |
| AdGuard | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/xtreme-dns-filter.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock-filter.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/annoyances-filter.txt "RAW") | 
| DNSCloak | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/wildcards.txt "RAW") | - | - |
| Unbound | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf "RAW") | - | - |
| dnsmasq | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf "RAW") | - | - |
| AdAway | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt "RAW") | - | - |
| Windows Hosts | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win "RAW") | - | - |
| Plain List | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/plain.txt "RAW") | - | - |


> ***DNS Filtresi:*** Alan adı tabanlı engeller. Örnek: example.com - ads.example.com - analytics.example.com<br/>
> <br/>
> ***Xtreme DNS Filtresi:*** Henüz bilinmeyen reklamları, izleyicileri ve diğer analitik amaçlı kullanılan alt alan adlarını engeller. Tam performans için DNS filtresi olarak kullanmanız tavsiye edilir, aksi takdirde yanlış engellemeden kaçınmak için listede bulunan beyaz kurallara eklenen sitelerde filtreleme devre dışı kalır. Tavsiye edilen uygulama: [AdGuard for Windows](https://adguard.com/tr/adguard-windows/overview.html) ~ [AdGuard for Android](https://adguard.com/tr/adguard-android/overview.html). Diğer uygulamalar: Adblock söz dizimini kullanan reklam engelleyiciler ile kullanabilirsiniz (Örn: uBlock, AdGuard, Adblock Plus vb. gibi) fakat beyaz kurallara eklenen sitelerdeki filtrelemenin devre dışı kalacağını unutmayın.<br/>
> <br/>
> ***Adblock Filtresi:*** Alan adının adres bölümlerine göre engeller. Örnek: example.com/js/ads.js - example.com/js/analytics.js<br/>
> <br/>
> ***Can Sıkıcı Öğeler Filtresi:*** Sitelerdeki gereksiz araçları engeller. Örneğin; açılır bildirimler, widget'lar, çerez bildirimleri, sosyal medya araçları, abone ol butonları, vb. gibi.<br/>
> <br/>
> ***Not:*** DNS filtrem bazı popüler engelleme listeleri tarafından güncel bir şekilde kullanılıyor, bunlar; [1Hosts](https://github.com/badmojr/1Hosts), [Energized Protection](https://github.com/EnergizedProtection/block) ve [oisd](https://oisd.nl/downloads) listeleridir. DNS filtrem her ne kadar bu listelerde bulunsa da bazı çakışmalardan dolayı tamamı kullanılamıyor, sadece %95 gibi bir kısmı mevcut. Mümkün olduğunca, yayınladığım filtreleri de kullanmanızı tavsiye ediyorum.

## Tespit ve araştırma yöntemleri
[AdGuard](https://adguard.com/), [NextDNS](https://nextdns.io/), Subdomain Finder, URL Scan

## Listenin Temel Amacı
Bu listede sadece yerel reklam ve izleyici adresleri bulunmaktadır, eğer tam bir koruma sağlamak istiyorsanız [1Hosts](https://github.com/badmojr/1Hosts), [Energized](https://github.com/EnergizedProtection/block) veya [oisd](https://oisd.nl/downloads) listeleri arasından en az birisiyle beraber kullanmanız tavsiye edilir.

## Sorunlar ve İstekler
İstemci desteği, liste sorunu veya diğer sorunları E-posta: saurane@protonmail.com veya [GitHub](https://github.com/saurane/Turkish-Blocklist/issues) üzerinden bildirebilirsiniz.
