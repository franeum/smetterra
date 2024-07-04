# terra

## versione semplice
### installazione

scarica questo repository e metti tutto il suo contenuto in una normale cartella. La cosa importante è che ci sia la cartella `dist` contenente la libreria terra (`terra.min.js`)

All'interno del file html (nella sezione `head`) si trova la seguente riga, che serve a importare la libreria:

```html
<head>
    ...
    <script src="./dist/terra.min.js"></script>
    ...
</head>
```

nella sezione `body` si trova effettivamente lo script che definisce il comportamento dell'automa

## TODO
## Versione complessa

Per una versione che permetta di inviare i dati bisogna fare le seguenti cose:
1.  instanziare un server web
2.  creare un client web che mostrerà l'automa in una pagina web
3.  inviare i dati con websocket tramite il protocollo osc
 