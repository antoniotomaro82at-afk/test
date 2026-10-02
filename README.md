# Mockup portale Demi Mobility

Copia statica della vista catalogo di `demimobilitynlt.be-work.it` (repository GitLab del sito, letto tramite BeDev), con due sole modifiche:

1. **Logo**: il logo NLT è sostituito dal simbolo Demi (vettoriale, `assets/demi-simbolo.svg`) con la scritta "Demi Mobility".
2. **Rosa antico** `#DFB3A7` (colore del simbolo) come colore di accento al posto dell'arancio/rosso.

File:
- `sito-demimobility/styles.css`: copia dello stile del sito (parte catalogo), invariato.
- `sito-demimobility/demi-brand.css`: **tutte le modifiche di marchio**, da caricare dopo `styles.css`.
- `sito-demimobility/index.html`: pagina del mockup (generata da `index.tpl.html`); veicoli e canoni sono esempi, sul sito reale arrivano dal catalogo REST.

Per applicarlo al sito reale bastano `demi-brand.css` (incluso dopo `styles.css`) e il markup del logo `.brand-demi` nell'header e nel footer di `index.html`.
