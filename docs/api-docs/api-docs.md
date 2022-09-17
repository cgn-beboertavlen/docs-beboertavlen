---
sidebar_position: 1
---
# Introduktion til BeboerTavlens API
Datamodellen for BeboerTavlen kan illusteres med figuren forneden.

|![\label{fig:datamodel}](/img/datamodel.drawio.png)|
|:--:| 
| *Figur: Datamodel objekter af BeboerTavlen* |

De enkelte objekter (bokse, vist i figuren) er uddybet nærmere i deres respektive sider, som kan tilgås på undermenuen for <!--\ref(-->API-Docs.  

## Krav til brug af API'et
BeboerTavlen kræver, at der udstilles en adgangsnøgle til en bruger, der er registreret i BeboerTavlens system. 

Adgangsnøglen følger med i mailen, der er sendt ud som email ved tegnelsen af en abonnementspakke.

API'et kan tilgås via OpenAPI specifikationen med linket `https://test.api.beboertavlen.dk/swagger/index.html` i test miljøet eller `https://api.beboertavlen.dk/swagger/index.html` i produktions miljøet.

## OpenAPI Specifikation
[BeboerTavlens API](https://tst-beboertavlen.azurewebsites.net/swagger/index.html) er kompatibel med OpenAPI 3.0 specifikationen. Der er knyttet Swagger, der kan fortolke API forespørgslerne direkte fra linksne specificeret under sektionen \label{sek:krav}, hvor man kan teste API'et på en nem og hurtig måde på browseren.

Når man vil teste en metode i API'et, så trykker man på *Try it out* og angiver adgangsnøglen, og så trykker man på *Send*. Det er så muligt at se responsen på metode kaldet. 
