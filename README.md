# ARound — contenuti delle città

Questo repository contiene **solo i dati** che l'app ARound scarica: i
JSON delle città, le foto, le mappe offline e le strade a piedi. Viene
riempito automaticamente dal repository dell'app, che è privato, con un
commit solo che prende il posto del precedente.

Non modificare niente a mano: la prossima pubblicazione sovrascrive tutto.

## Cosa c'è dentro

    data/index.json              elenco delle città, un file solo per tutte le lingue
    data/cities/<id>.<lang>.json contenuto completo di una città in una lingua
    data/images/                 le foto dei luoghi
    data/maps/<id>.pmtiles       la mappa offline di una città
    data/grafi/<id>.grafo        le strade a piedi di una città, con le quote

## Licenze

I testi, la selezione e l'ordine dei luoghi sono di chi li ha scritti, e
non sono rilasciati sotto alcuna licenza d'uso: sono qui perché un'app li
scarica da un browser, non perché siano riutilizzabili.

Le foto sono di terzi, ognuna con la sua licenza, ridimensionate e
ricompresse. Autore, licenza e pagina da cui viene ogni foto stanno nel
file della sua città, in `city.crediti`, alla voce `images/<file>`.

Mappe e strade sono derivate da OpenStreetMap e restano sotto la sua
licenza, la Open Database License 1.0: © OpenStreetMap contributors
(https://www.openstreetmap.org/copyright). Le mappe sono ritagliate dalla
build di Protomaps (https://protomaps.com). Le quote delle strade vengono
dal Copernicus DEM GLO-30: © DLR e.V. 2010-2014 and © Airbus Defence and
Space GmbH 2014-2018 provided under COPERNICUS by the European Union and
ESA; all rights reserved.
