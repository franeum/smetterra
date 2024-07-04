# terra

## installazione

Per la versione semplice (pagina web statica) puoi semplicemente mettere il file html nella stessa cartella in cui si trova la libreria `terra.min.js`, che a sua volta è nella cartella `dist`

all'interno del file html (nella sezione `head`) si trova la seguente riga, che serve a importare la libreria:

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
 