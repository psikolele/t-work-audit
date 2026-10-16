# Proposta Commerciale & Strategica: Rifacimento Nuovo Portale T-Works

**Destinatario:** Emanuele Frigerio — Fondatore & Titolare, T-Work & Gadget Sagl  
**Data:** Ottobre 2026  
**Riferimento offerta:** KRK-TW-2026-01 · **Validità:** 30 giorni dalla data di invio  
**Società Proponente:** Kraken Web Development  
**Oggetto:** Riprogettazione integrale della presenza digitale, catalogo interattivo B2B e preventivatore automatizzato per il Canton Ticino e la Svizzera.

---

## 1. Perché il sito attuale sta frenando la crescita di T-Works

L'attuale sito web (`t-workgadget.ch`) non riflette la qualità dei prodotti e la professionalità che T-Work & Gadget offre ai propri clienti sul territorio ticinese. 

Dall'audit tecnico e strategico condotto emergono tre problemi strutturali che oggi causano la **perdita quotidiana di potenziali clienti aziendali**:

1. **La "trappola" dei cataloghi su Google Drive:**  
   Attualmente i cataloghi dei marchi (Portwest, Sol's, Giblor's, Clique, Makito, Siggi, ecc.) sono link a file PDF esterni su Google Drive.  
   - Da smartphone, aprire PDF da 80 MB su Google Drive è lento e frustrante.
   - Google non indicizza nessun singolo capo d'abbigliamento o gadget sul dominio di T-Works: il cliente che cerca online non trova T-Works, ma i competitor.
   - Il cliente non può interagire: legge il PDF, ma per ordinare deve inviare un'email generica senza riferimenti precisi.

2. **Errori formali e tecnici che minano l'autorevolezza del marchio:**  
   - Il codice sorgente dichiara ai motori di ricerca che il sito è in lingua tedesca (`lang="de"`), penalizzando il posizionamento organico in Ticino.
   - Sono presenti refusi evidenti nei titoli in Home Page (*"Abbigliamentpo promozionale"*, *"Abbigliamentpo da lavoro"*).
   - In testata compaiono icone di carrello e profilo utente che non sono cliccabili e non portano ad alcuna pagina, dando l'impressione di un sito non funzionante.

3. **Nessun sistema di conversione lead per aziende:**  
   - Le richieste passano attraverso semplici link `mailto:` o un modulo contatti privo di configurazione per il caricamento dei loghi aziendali o delle quantità stimate.

---

## 2. La Visione del Nuovo Portale T-Works

Il nuovo sito non sarà una semplice vetrina statica, ma un **generatore di preventivi e clienti B2B per aziende ed enti in Ticino e Svizzera**.

```
[Visitatore Aziendale] 
       │
       ▼
[Nuovo Portale T-Works: Veloce, Moderno, Mobile-First]
       │
       ├─► Sfoglia Catalogo B2B per Settore (Lavoro, DPI, Promozionale, Gadget, Horeca)
       ├─► Seleziona Articoli, Colori e Volumi Stimati
       ├─► Carica direttamente il Logo Aziendale (Vettoriale / PDF)
       │
       ▼
[Ricezione Preventivo Strutturato su Misura per Emanuele]
  ↳ Con notifica immediata via Email & WhatsApp per chiusura commerciale rapida!
```

---

## 3. Moduli e Caratteristiche del Nuovo Progetto

### Modulo A — UI/UX e Visual Design Industriale Moderno
- Design grafico su misura, pulito e autorevole, ottimizzato per responsabili acquisti, PMI e studi professionali.
- Pieno rispetto della tipografia web e usabilità mobile (Core Web Vitals con caricamento sotto 1 secondo).
- Sezione "Lavorazioni e Personalizzazione" (Ricamo, Serigrafia, Stampa DTF, Incisione laser) per valorizzare il know-how aziendale.

### Modulo B — Catalogo Digitale B2B Interattivo
- Suddivisione chiara per categorie merceologiche e ambiti d'uso:
  - *Abbigliamento da Lavoro & Alta Visibilità (DPI)*
  - *Abbigliamento Promozionale & Corporate Identity*
  - *Horeca, Medicale & Benessere*
  - *Articoli Promozionali, Gadget Tecnologici e Merchandising*
- Schede prodotto con galleria foto ad alta definizione, tabella taglie e varianti colore.
- Ricerca rapida per parola chiave e filtro per brand trattati.

### Modulo C — "Quote Builder" (Carrello Preventivi con Upload Logo)
- Il cliente può aggiungere più articoli a una lista preventivo con quantità indicative.
- Modulo di richiesta arricchito con:
  - Caricamento del logo aziendale (`.ai`, `.eps`, `.svg`, `.pdf`, `.png`).
  - Scelta della tecnica desiderata (o richiesta di consiglio a T-Works).
  - Recapiti diretti e note speciali.

### Modulo D — SEO Territoriale & Ottimizzazione per la Svizzera
- Ottimizzazione locale per query ad alto valore commerciale in Ticino (*"abbigliamento da lavoro Chiasso"*, *"divise aziendali Lugano"*, *"gadget personalizzati Svizzera"*).
- Dati strutturati Schema.org `LocalBusiness` per presenza su Google Maps e rich snippet.
- Conformità completa con la nuova Legge federale sulla protezione dei dati (**nLPD**) e GDPR.

---

## 4. Fasi di Realizzazione e Tempistiche

La tempistica parte dal **completamento dei prerequisiti (Fase 0)**, non dalla firma: senza accesso a hosting, dominio e cataloghi originali il lavoro non può andare online.

| Fase | Descrizione | Durata |
|---|---|---|
| **Fase 0: Prerequisiti & Accessi** | Completamento del trasferimento del contratto Hostpoint a T-Work & Gadget Sagl, accesso alla gestione DNS di `t-workgadget.ch`, recupero dei cataloghi dei marchi scelti (file dei fornitori o PDF) dall'account Google. | 1 settimana *(dipende dai tempi di Hostpoint e Google)* |
| **Fase 1: Architettura & Visual Concept** | Albero di navigazione, categorie, wireframe e grafica. Include due giri di revisione e l'approvazione scritta di Emanuele. | 1–2 settimane |
| **Fase 2: Setup Piattaforma & Frontend** | Installazione WordPress + WooCommerce (modalità catalogo B2B) su Hostpoint, sviluppo interfaccia responsive, configuratore preventivi con upload logo. | 2 settimane |
| **Fase 3: Migrazione dei Cataloghi** | Caricamento di articoli, foto, varianti e taglie per gli 8–10 marchi scelti. Makito e midocean dal feed dati del fornitore; gli altri dai file ricevuti o, in mancanza, dai PDF. Parte in parallelo alla Fase 2. | 3–4 settimane |
| **Fase 4: SEO, Compliance & Integrazioni** | Schema.org `LocalBusiness`, SEO territoriale, tracciamento conversioni, informativa e cookie conformi nLPD, notifiche preventivi. | 1 settimana |
| **Fase 5: Collaudo & Messa Online** | Collaudo con Emanuele, switch DNS su Hostpoint, redirect dalle vecchie URL, verifica indicizzazione. | 1 settimana |

**Durata complessiva realistica: 6–8 settimane** dal completamento della Fase 0.
- **Go-live** con tutti i marchi che hanno file disponibili: circa **settimana 7**.
- I marchi senza file dal fornitore slittano a un lotto successivo, prezzato a parte (vedi sezione 6).

> **Perché la migrazione dei cataloghi non può aspettare:** oggi tutti i cataloghi dipendono da un singolo account Google. Se l'account viene sospeso o chiuso, i link dei cataloghi nel sito smettono di funzionare dall'oggi al domani. Spostarli sul dominio T-Work elimina questo rischio.

**Cosa serve da T-Work per rispettare i tempi:** accessi Hostpoint e DNS, file originali dei cataloghi, logo in formato vettoriale, testi aziendali, feedback sulle bozze entro 5 giorni lavorativi. Ritardi su questi punti spostano la consegna dello stesso numero di giorni.

## 5. Perché Scegliere Kraken

- **Nessun vincolo a piattaforme chiuse:** addio a costosi canoni Webflow per ospitare pagine statiche.
- **Piena proprietà del codice e dei dati:** la piattaforma appartiene al 100% a T-Work & Gadget Sagl.
- **Supporto locale e tempestività:** un team che comprende il mercato ticinese e svizzero e risponde rapidamente.


---

## 6. Investimento

*Importi in CHF, IVA [da definire]. Prezzo fisso per il perimetro descritto qui sotto.*

**Pacchetto unico, sito e catalogo T-Work: CHF 1'700** una tantum.

**Incluso:**
- Design su misura e sito responsive (Modulo A)
- Setup WordPress + WooCommerce in modalità catalogo B2B e preventivo, su Hostpoint
- Catalogo interattivo con **8–10 marchi**, scelti da Emanuele. Makito e midocean sono i primi candidati perché hanno un feed dati
- Circa **15–20 modelli per marchio** (proposta, totale 120–200 articoli), da confermare con Emanuele
- Richiesta preventivo con upload logo e lista multi-articolo (Modulo C, versione base)
- SEO tecnica, Schema.org `LocalBusiness`, conformità nLPD (Modulo D, versione base)
- Redirect dalle vecchie URL
- Un'ora di formazione sul pannello
- Primo anno di manutenzione (sezione 7)

**Esclusioni, non incluse nel prezzo:**
- Marchi senza file o feed dal fornitore: slittano a un lotto successivo, prezzato a parte. Se un fornitore rilascia solo file PDF e non un feed, i costi possono variare: l'inserimento manuale viene quantificato a ore e concordato prima di procedere.
- Cataloghi PDF scansionati o non leggibili: inseriti a ore, solo previo accordo.
- Foto di prodotto non fornite da T-Work o dal fornitore.
- Modifiche oltre il perimetro: preventivate prima di essere eseguite.
- Hosting e dominio su Hostpoint: costi a carico di T-Work [da confermare].
- Ore extra: CHF [70]/ora.

**Pagamento:** 40% alla firma · 30% all'approvazione del visual concept · 30% alla messa online.

---

## 7. Manutenzione e Assistenza

- **Primo anno:** incluso nel prezzo.
- **Dal secondo anno:** CHF 300 all'anno, fatturati in anticipo.

**Incluso nel canone annuale:**
- Aggiornamenti WordPress, WooCommerce e plugin
- Backup automatici
- Monitoraggio di sicurezza e disponibilità
- Assistenza via email, con risposta entro 2 giorni lavorativi

**Non incluso, a ore:** nuovi articoli o marchi, modifiche di contenuto e grafica.

- Il canone si rinnova tacitamente ogni anno, con disdetta scritta tre mesi prima della scadenza.
- I primi 30 giorni dopo il go-live sono in garanzia: i difetti di funzionamento vengono corretti senza costi.

---

## 8. Condizioni Generali

- **Proprietà:** al saldo, codice, contenuti, dominio e accessi amministratore appartengono interamente a T-Work & Gadget Sagl.
- **Contenuti:** testi, loghi e cataloghi sono forniti da T-Work, che ne garantisce i diritti d'uso. Servizi fotografici e copywriting non sono inclusi salvo accordo separato.
- **Modifiche di perimetro:** richieste oltre quanto descritto in questa proposta vengono preventivate prima di essere eseguite.
- **Revisioni:** inclusi due giri di revisione sulla grafica e uno sul sito completo prima del go-live.
- **Validità:** questa offerta è valida 30 giorni dalla data di invio.
- **Diritto applicabile e foro:** [diritto svizzero, foro di _____].

---

## 9. Accettazione

Con la firma, T-Work & Gadget Sagl conferma l'incarico a Kraken Web Development alle condizioni sopra descritte.

**Marchi scelti (8–10):** ______________________________________

| Per T-Work & Gadget Sagl | Per Kraken Web Development |
|---|---|
| Nome: Emanuele Frigerio | Nome: _______________________ |
| Ruolo: Titolare | Ruolo: _______________________ |
| Luogo e data: _______________ | Luogo e data: _______________ |
| Firma: | Firma: |
| <br><br>_______________________ | <br><br>_______________________ |
