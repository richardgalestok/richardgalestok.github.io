# Dokumentácia
## Podstránky
- Úvod
- Blog
- O mne
- Webové Publikovanie
- Kontakt

Premenné:
- site.meno
- site.priezvisko
- site.popis
- site.email
- page.title
- page.date

## Šablóny/Layouts
- Default
- Article - šablóna pre jednotlivé podstránky príspevkov
- Post - šablóna pre samotné príspevky v blogu

## Dátový súbor:
- _data/predmety.csv, použité v omne/index.html cez for cyklus

## Tagy a Filtre:
- include menu.html v default a article šablóne
- include footer.html v default a article šablóne
- page.url contains - v _includes/menu.html
- if, else, endif - v _includes/menu.html
- site.time | date_to_long_string
- page.date | date_to_string (pri daných postoch)
- post.content | strip_html | truncatewords: 20

## Plugin:
- Sitemap - mapa stránok, generuje zoznam URL na webe, ktoré sú dôležité pre užívateľov, vyhľadávacie roboty a ďalší software. Použil som XML sitemap, plugin generuje súbor sitemap.xml v zložke _site
- Sitemap - gem jekyll-sitemap
- _config.yml definovaný
