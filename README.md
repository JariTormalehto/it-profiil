# IT-profiili mall

Üldine muudetav profiilimall. Avalikku lähtekoodi ei lisata kasutajate andmeid.

## Kasutamine

- Iga uus külastus ja lehe värskendamine avab malli.
- **Muuda sisu** muudab kõiki profiili tekste, sealhulgas pealkirju ja footerit.
- **Salvesta mustand** säilitab teksti ja foto ainult selle brauseri localStorage-is. Mustandit ei taastata automaatselt.
- **Taasta mustand** avab selles brauseris salvestatud mustandi.
- **Kustuta mustand** eemaldab salvestuse ja taastab lehel malli. Kasuta seda jagatud arvutis.
- **Taasta mall** taastab algse malli, jättes salvestatud mustandi alles.
- **Salvesta HTML** laadib alla isikliku koopia, mis sisaldab sisestatud andmeid. Ära asenda sellega avaliku malli lähtefaili.
- **Prindi / PDF** salvestab praeguse vaate PDF-ina. Lülita brauseri päised ja jalused välja.

## Privaatsus

Leht ei saada sisestatud andmeid ega fotosid serverisse ning ei kasuta analüütikat. Salvestus on brauseriprofiili, veebidomeeni ja selle lehe asukoha põhine; see ei ole kontopõhine ega krüpteeritud. Sama brauseriprofiili kasutaja saab salvestatud mustandi taastada. Brauseri saidiandmete kustutamine kustutab ka mustandi. Privaatrežiimis võib salvestus olla ajutine või keelatud.

## Avaldamine

GitHub Pages avaldab ainult üldise malli `main` haru juurkaustast. Kasutajate HTML-eksporte ega mustandeid ei lisata hoidlasse.
