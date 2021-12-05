![alt text](https://github.com/saurane/Turkish-Blocklist/blob/master/banner.png)

***Blocking; [TR] advertisements, statistics and tracker.***


| Client | RAW |
| ------------ | ------------ |
| Pi-hole | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt "Link") |
| uBlock Origin ~ AdGuard | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt "Link") |
| DNSCloak | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/wildcards.txt "Link") |
| Unbound | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf "Link") |
| dnsmasq | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf "Link") |
| AdAway | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt "Link") |
| Windows Hosts | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win "Link") |
| Plain List | [Link](https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/plain.txt "Link") |

## Proje Açıklaması / Project Description
TR: Türkçe tabanlı reklam ve izleyici listesi.<br/>
EN: Turkish based ad and tracker blocklist.

## Listenin Temel Amacı
Bu listede sadece yerel reklam ve izleyici adresleri bulunmaktadır, eğer tam bir koruma sağlamak istiyorsanız [1Hosts Pro](https://github.com/badmojr/1Hosts), [Energized](https://github.com/EnergizedProtection/block) veya [oisd](https://github.com/ookangzheng/dbl-oisd-nl) listeleri arasından en az birisiyle beraber kullanmanız tavsiye edilir.

## Listenin Gelişimi
Listenin daha fazla büyümesi için yardımınız gerekiyor, örnek olarak `Pi-hole, AdGuard Home` veya diğer reklam engelleme istemcilerindeki günlüklerinizi kontrol ederek listede olmayan reklamları, izleyicileri bildirirseniz listenin büyümesinde önemli bir artış kazanırız.

## Reklam, İzleyici ve Analitik Tespiti
İstemci günlüğünüzü inceleyerek alan adının bünyesinde bulunan reklam, izleyici veya analitik amaçlı kullanılan alt alan adlarını öğrenebilirsiniz. Genelde `(tracker, track, ads, ad, analitik, counter, collect, collector, analiz, reklam, sayac, hit)` şeklinde başlar ve alan adıyla devam eder, örnek olarak `(analiz.example.com , ads.example.com , counter.example.com)`.

## Sorunlar ve İstekler
İstemci desteği, liste sorunu veya diğer sorunları [E-posta](mailto:saurane@protonmail.com) veya [GitHub](https://github.com/saurane/Turkish-Blocklist/issues) üzerinden bildirebilirsiniz.
