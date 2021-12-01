# Analiza podatkov s programom R - 2021/22


Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza izpusta toplogrednih plinov v EU


Analiziral bom izpust toplogrednih plinov v EU. Izpust plinov bom tudi primerjal z razvitostjo posameznih držav in velikostjo le teh. Primerjal bom tudi izpust CO2 posameznika in BDP na prebivalca v. Podatke bom večinoma dobil na Eurostatu.

### 1. tabela
V prvi tabeli bi predstavil izpust plinov držav po letih. Vrednosti za posamezno državo bojo v stolpcih s tem da bi predzadnji stolpec bil izpust toplogrednih plinov celega sveta, zadnji pa spremebma temperature sveta.

V drugi tabeli

V zadnji tabeli bi podrobno predstavil izpust plinov (gospodinjstva, industrija, javni transport, agrikultura) 
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
