# Analiza podatkov s programom R - 2021/22


Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza izpusta agregatnih plinov po svetu


Analiziral bom izpust agregatnih plinov po svetu ter vpliv le teh na dvig temperature zemlje skozi čas. Izpust plinov bom tudi primerjal z razvitostvjo posameznih držav in velikostjo le teh. Podatke sem dobil na [Greenhouse gas emissions](https://ourworldindata.org/greenhouse-gas-emissions), na [Wikipediji](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_area) 


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
