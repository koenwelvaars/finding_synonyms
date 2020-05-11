![alt text](https://i.imgflip.com/1ye64z.jpg)

# Synoniemen zoeken met text mining
De synoniemenzoeker is een onderdeel van een text mining project om complicaties uit medische teksten te ontsluiten. Bij het zoeken naar complicaties
wil je dat alle mogelijke benamingen voor de complicatie meegenomen worden. Binnen medische documentatie kom je nog wel eens praktijkvariatie in benaming tegen; artsen die met verschillende benamingen/woorden dezelfde dingen bedoelen. Denk bijvoorbeeld aan de complicatie "delier": de eerste arts noteert dit als "delier", de tweede arts
noteert dit als "vergeetachtig", de derde arts noteert dit als "inzinking" enzovoort.
Met behulp van een woordenmatrix bereken je de mate van waarschijnlijkheid dat bepaalde woorden in verschillende teksten in combinatie met elkaar voorkomen. Des te meer woorden
bij elkaar voorkomen, des te waarschijnlijker het is dat deze woorden dezelfde betekenis hebben of eenzelfde context hebben.
Hoewel dit een onderdeel van test mining project voor complicatie detectie, is het een leuke manier om goed inzicht te krijgen in de context van het woord
wat je zoekt en hoe text mining omgaat met het berekenen van context (Word2Vec technieken) uit verschillende teksten.

Je kan de code hier terugvinden:
- [Synoniemenzoeker](https://github.com/koenwelvaars/machine-learning-voorbeelden/blob/master/Inladen%20van%20alle%20benodigde%20packages%20en%20data)

Mocht je vragen of suggesties hebben over de code of  ideeën voor een volgende post, neem gerust contact met mij op via k.welvaars@olvg.nl
In de toekomst zal ik meer R-code delen, zodat dit door een ieder te gebruiken is voor zijn/haar machine learning projecten.



