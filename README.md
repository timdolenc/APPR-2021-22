# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Tematika

Analiziral bom vpliv dohodkovne neenakosti na kriminal, samomore in onesnaževanje v evropskih državah in ga primerjal z vplivom absolutnega nivoja dohodka.
Za merjenje dohodkovne neenakosti bom uporabil Ginijev index, za merjenje onesnaževanja pa se bom osredotočil le na stopnjo onesnaženosti zraka.

## Podatki
1. Tabela 1 vsebuje Ginijeve koeficiente po državah.
2. Tabela 2 vsebuje število samomorov na 100000 prebivalcev po svetovnih državah (wikipedia: https://en.wikipedia.org/wiki/List_of_countries_by_suicide_rate).
3. Tabela 3 vsebuje podatke o onesnaženosti zraka po državi (grami toplogrednih plinov per capita)
4. Tabela 4 vsebuje podatke o kriminalnih dejanjih glede na vrsto, na 100000 prebivalcev po državah.
5. Tabela 5 vsebuje BDP per capita po državi.
## Program

Glavni program in poročilo se nahajata v datoteki `projekt.Rmd`.
Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

* obdelava, uvoz in čiščenje podatkov: `uvoz/uvoz.r`
* analiza in vizualizacija podatkov: `vizualizacija/vizualizacija.r`
* napredna analiza podatkov: `analiza/analiza.r`

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi `lib/`.
Potrebne knjižnice so v datoteki `lib/libraries.r`
Podatkovni viri so v mapi `podatki/`.
Zemljevidi v obliki SHP, ki jih program pobere,
se shranijo v mapo `../zemljevidi/` (torej izven mape projekta).
