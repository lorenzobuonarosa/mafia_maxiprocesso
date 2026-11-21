# Maxiprocesso di Palermo – dataviz Radar · QN

Stile e asset: skill `radar-dataviz` (`assets/radar.css`, `assets/radar.js`, `assets/embed.js`).

| Cartella | Contenuto | Dati |
|---|---|---|
| `maxiprocesso/` | Dashboard: numeri del primo grado (big number + waffle) e timeline 1981-1993 | `data/maxi-numeri.csv`, `data/maxi-eventi.csv` |
| `maxi-struttura/` | La piramide di Cosa nostra secondo Buscetta (schema a sei passi) e la Commissione nel 1978 | `data/struttura-livelli.csv`, `data/commissione-1978.csv` |

Fonte: Wikipedia, voce *Maxiprocesso di Palermo* e voci collegate (date dei singoli eventi).
Struttura: ordinanza-sentenza del Maxiprocesso, vol. 5, pp. 810-818; Wikipedia, *Sicilian Mafia Commission* e *Cosa nostra*.

Nei CSV degli eventi le date con giorno `01` sono approssimate al mese e nella scheda compaiono solo come mese e anno.
Il `data_fine` disegna un segmento (le bombe del 1993).

## Foto della Commissione (`maxi-struttura/img/`)

Le foto vengono da Wikimedia (file indicati come dominio pubblico dalla comunità, per lo più PD-Italy per fotografie semplici di oltre 20 anni).
La provenienza originale è spesso un giornale o un sito: prima di usarle in pagina conviene che l'ufficio foto ne verifichi i diritti.
Le didascalie di credito stanno nella colonna `credito` di `data/commissione-1978.csv`; i file nella colonna `foto` (più file separati da `|`).

| Mandamento | File | File su Wikimedia | Licenza indicata |
|---|---|---|---|
| Ciaculli | `greco.jpg` | Michele Greco.jpg (en) | PD-Italy |
| Corleone | `riina.jpg` (ritaglio) | Foto segnaletica di Salvatore Riina.jpg (it) | dominio pubblico |
| Corleone | `provenzano.jpg` | Bernardo Provenzano.jpg (Commons) | dominio pubblico |
| Santa Maria di Gesù | `bontate.jpg` | Stefano Bontade.jpg (en) | PD-Italy |
| Passo di Rigano | `inzerillo.jpg` | Salvatore Inzerillo.jpg (Commons) | dominio pubblico |
| Porta Nuova | `calo.jpg` | Giuseppe Calo.jpg (en) | PD-Italy |
| Noce | `scaglione.jpg` | Salvatore Scaglione.jpg (Commons) | dominio pubblico, foto diffusa dalla polizia |
| Resuttana | `madonia.jpg` | Francesco Madonia.jpg (Commons) | dominio pubblico |
| Partinico | `geraci.jpg` | Antonio Geraci.jpg (en) | PD-Italy |
| San Giuseppe Jato | `salamone.jpg` | fornita dalla redazione | credito da indicare |
| Castronovo di Sicilia | `pizzuto.jpg` | fornita dalla redazione | credito da indicare |
| Pagliarelli | `motisi.jpg` | fornita dalla redazione | credito da indicare |
| Partanna | `riccobono.jpg` (bianco e nero, sfondo sfocato) | fornita dalla redazione | credito da indicare |

Tutti i dodici mandamenti hanno una foto; per quelle fornite dalla redazione manca ancora il credito.
