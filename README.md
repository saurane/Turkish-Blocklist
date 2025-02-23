![Cover](https://github.com/saurane/Turkish-Blocklist/blob/master/Assets/srn-banner.png)

<div align="center">
    <!-- Last Updated -->
    <img src="https://img.shields.io/badge/Updated-Feb 23, 2025-green.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- Status -->
    <img src="https://img.shields.io/badge/Status-Stable-blue.svg?longCache=true&style=for-the-badge"
      alt="_time_stamp_" />
    <!-- License -->
    <img src="https://img.shields.io/badge/License-MPL 2.0-orange.svg?longCache=true&style=for-the-badge"
      alt="Lisans-MPL-2.0" />
</div>
<br/>

| İstemci | DNS filtresi | Gizlilik filtresi | URL izleme filtresi | İzin verilenler filtresi |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| uBlock - AdGuard | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adb-privacy.txt "RAW") | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adb-urltracking.txt "RAW") <br/>"güvenilir filtre olarak işaretleyin" | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Whitelist/adb-whitelist.txt "RAW") |
| Pi-hole | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt "RAW") | - | - | - | - |
| AdAway | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt "RAW") | - | - | - |
| Unbound | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf "RAW") | - | - | - |
| dnsmasq | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf "RAW") | - | - | - |
| RPZ | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/rpz.txt "RAW") | - | - | - |
| Windows Hosts | [RAW](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win "RAW") | - | - | - |

## Filtre açıklaması
> ***DNS Filtresi:*** Alan adı tabanlı engeller. Örnek: example.com - ads.example.com - analytics.example.com<br/>
> <br/>
> ***Gizlilik Filtresi:*** Alan adının adres bölümlerine göre engeller. Örnek: example.com/file/js/tracker.js - example.com/js/analytics.js<br/>
> <br/>
> ***URL İzleme Filtresi:*** Sitelerdeki URL adreslerinde bulunan izleme parametrelerini kaldırır.<br/> Not: Bu filtrenin çalışması için "güvenilir filtre" olarak işaretlenmesi gerekiyor.<br/>
> <br/>
> ***İzin verilenler filtresi:*** Reklam engelleyicilerden veya filtrelerden kaynaklanan sorunları çözmek için hazırlanmıştır.<br/>
> <br/>
> ***Not:*** DNS filtrem bazı popüler engelleme listeleri tarafından güncel bir şekilde kullanılıyor, bunlar; [1Hosts](https://github.com/badmojr/1Hosts), [Energized Protection](https://github.com/EnergizedProtection/block) ve [oisd](https://oisd.nl/downloads) listeleridir. DNS filtrem her ne kadar bu listelerde bulunsa da bazı çakışmalardan dolayı tamamı kullanılamıyor, sadece %95'lik kısmı mevcut. Mümkün olduğunca, yayınladığım filtreleri de kullanmanızı tavsiye ediyorum.


## Amaç
> ***DNS filtresi:*** Bu filtrede sadece yerel reklam ve analitik amaçlı kullanılan adresler bulunmaktadır, eğer tam bir koruma sağlamak istiyorsanız [1Hosts](https://github.com/badmojr/1Hosts), [Energized](https://github.com/EnergizedProtection/block) veya [oisd](https://oisd.nl/downloads) listeleri arasından en az birisiyle beraber kullanmanız tavsiye edilir.<br/>
> ***Not:*** DNS filtresinin %99'luk kısmı, sahibi Türk olan şirketlerin/kişilerin veya "com.tr" uzantılı Türkçe içerikli sitelerin sunucularıdır.<br/>
> <br/>
> ***Gizlilik filtresi:*** DNS filtresi ile engellenemeyen, alan adının bünyesinde bulunan izleyicileri ve analitik amaçlı öğeleri engeller.

## Tespit ve araştırma yöntemleri
[AdGuard](https://adguard.com/), [NextDNS](https://nextdns.io/), URL Scan

## Sorunlar ve İstekler
İstemci desteği, liste sorunu veya diğer sorunları [GitHub](https://github.com/saurane/Turkish-Blocklist/issues) üzerinden bildirebilirsiniz.
