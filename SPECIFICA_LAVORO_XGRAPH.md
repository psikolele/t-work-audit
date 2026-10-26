# Specifica di lavoro e vincoli: nuovo portale T-Works

**Committente:** XGRAPH Sagl, Viale Breggia 11 A, 6834 Morbio Inferiore (Ticino, Svizzera)  
**Preparato da:** Kraken Web Development  
**Data:** Ottobre 2026

---

## 1. Contesto

Il sito attuale (`t-workgadget.ch`) è una vetrina statica costruita su un template tedesco. I cataloghi dei marchi sono link a PDF su Google Drive, non sono indicizzati e non permettono di richiedere un preventivo in modo strutturato. Il nuovo portale deve diventare uno strumento di raccolta preventivi B2B per aziende ed enti in Ticino e in Svizzera.

## 2. Obiettivo e perimetro

Il nuovo sito include:

- un catalogo interattivo B2B con **8–10 marchi**, con circa **15–20 modelli per marchio** (120–200 articoli in totale);
- una richiesta di preventivo con lista multi-articolo e upload del logo aziendale;
- un design responsive, pensato per uso da smartphone;
- una base SEO territoriale per Ticino e Svizzera, conforme alla nLPD.

La scelta dei marchi spetta al committente. Makito e midocean sono i primi candidati, perché forniscono un feed dati.

## 3. Moduli di lavoro

**Modulo A: Design e sito**

- Grafica su misura, pulita e professionale, per responsabili acquisti e PMI.
- Caricamento rapido e uso mobile.
- Sezione "Lavorazioni e personalizzazione" (ricamo, serigrafia, stampa DTF, incisione laser).

**Modulo B: Catalogo B2B**

- Categorie per ambito d'uso: lavoro e DPI, promozionale e corporate, Horeca e medicale, gadget e merchandising.
- Scheda prodotto con foto, taglie e colori.
- Ricerca per parola chiave e filtro per marchio.

**Modulo C: Richiesta preventivo**

- Lista di più articoli con quantità indicative.
- Upload del logo (`.ai`, `.eps`, `.svg`, `.pdf`, `.png`).
- Scelta della tecnica di personalizzazione, o richiesta di consiglio.
- Recapiti e note.

**Modulo D: SEO territoriale e conformità**

- Schema.org `LocalBusiness` per Chiasso, Lugano e Ticino.
- Ottimizzazione per ricerche locali di abbigliamento da lavoro e gadget personalizzati.
- Informativa privacy e cookie conformi alla nLPD.
- Redirect dalle vecchie URL.

## 4. Tempistica

La tempistica parte dal completamento della Fase 0.

| Fase | Contenuto | Durata |
|---|---|---|
| **0. Prerequisiti** | Contratto Hostpoint intestato al committente, accesso DNS del dominio, recupero dei cataloghi dei marchi scelti | 1 settimana |
| **1. Architettura e grafica** | Struttura del sito, wireframe e grafica, con due giri di revisione | 1–2 settimane |
| **2. Piattaforma e frontend** | WordPress + WooCommerce in modalità catalogo B2B su Hostpoint, interfaccia e preventivo | 2 settimane |
| **3. Migrazione cataloghi** | Articoli, foto, varianti e taglie dei marchi scelti, in parallelo alla fase 2 | 3–4 settimane |
| **4. SEO e conformità** | Schema.org, SEO territoriale, informativa nLPD, notifiche preventivi | 1 settimana |
| **5. Collaudo e messa online** | Collaudo col committente, passaggio DNS, redirect, verifica di indicizzazione | 1 settimana |

**Durata complessiva: 6–8 settimane** dal completamento della Fase 0. Go-live con i marchi che hanno i file disponibili: circa settimana 7.

## 5. Vincoli e dipendenze

Questi punti condizionano la tempistica e il perimetro. Se uno di essi non si verifica, la data slitta di un numero equivalente di giorni.

- **Hosting:** il contratto Hostpoint deve essere intestato al committente prima di qualsiasi messa in produzione. Fino ad allora il lavoro si svolge in ambiente di staging. I costi Hostpoint sono a carico del committente.
- **Dominio:** accesso alla gestione DNS di `t-workgadget.ch`, o del nuovo dominio se viene scelto.
- **Cataloghi e file dei fornitori:** i cataloghi attuali sono nell'account Google del committente. Il recupero dei file è a carico del committente.
- **Feed dati:** Makito e midocean hanno un feed. Midocean richiede un'autorizzazione di accesso da chiedere al fornitore.
- **Solo PDF:** se un fornitore rilascia solo PDF e non un feed, i costi possono variare. L'inserimento manuale viene quantificato a ore e concordato prima di procedere.
- **Marchi senza file:** i marchi per cui non arrivano file o feed slittano a un lotto successivo, da concordare a parte.
- **Loghi e immagini:** forniti dal committente o dal fornitore, con diritti d'uso garantiti dal committente.
- **Testi aziendali:** forniti dal committente. Servizi di copywriting e fotografia non sono inclusi.
- **Tempi di risposta:** feedback sulle bozze entro 5 giorni lavorativi. Ritardi nelle approvazioni spostano la consegna.
- **Lingua:** italiano al lancio.

## 6. Esclusioni

- Foto di prodotto non fornite dal committente o dal fornitore.
- Cataloghi PDF scansionati o non leggibili, salvo inserimento manuale concordato a ore.
- Servizi fotografici, copywriting e traduzioni.
- Modifiche di perimetro: vengono descritte per iscritto e concordate prima di essere eseguite.
- Gestione quotidiana di nuovi articoli o contenuti dopo il go-live, salvo accordo separato.

## 7. Revisioni

Sono previsti due giri di revisione sulla grafica e uno sul sito completo prima del go-live.
