# Audit Tecnico, SEO & UI/UX — T-Work & Gadget Sagl (t-workgadget.ch)

**Cliente:** T-Work & Gadget Sagl  
**Referente:** Emanuele Frigerio  
**Data Audit:** 21 Settembre 2026  
**Agenzia / Redattore:** Kraken Web Development  
**Stato Attuale:** Piattaforma Webflow obsoleta, gravi errori strutturali, blocco della conversione e invisibilità SEO.

---

## 🎯 Executive Summary (Sintesi per la Direzione)

L'attuale sito web di **T-Work & Gadget Sagl** (`https://t-workgadget.ch/`) presenta una serie di **criticità bloccanti** che vanificano ogni sforzo commerciale, danneggiano la reputazione aziendale e impediscono l'acquisizione organica di clienti B2B in Ticino e in Svizzera.

Il sito non è una risorsa commerciale attiva, ma un semplice "biglietto da visita statico" assemblato a partire da un template Webflow in lingua tedesca riadattato in modo superficiale. La presenza di **refusi grammaticali grossolani nei titoli principali**, **icone fantasma non cliccabili**, **cataloghi relegati a link esterni su Google Drive** e una **configurazione SEO che dichiara il sito in lingua tedesca** rende non solo opportuno, ma **urgente e indispensabile un rifacimento integrale della piattaforma**.

---

## 1. 🔍 Audit SEO & Architettura dell'Informazione (Criticità Gravi)

### 1.1 Errore di Localizzazione Linguistica (`lang="de"`)
- **Il problema:** Nel tag `<html>` di tutte le pagine è presente l'attributo `lang="de"`:
  ```html
  <html data-wf-domain="t-workgadget.ch" ... lang="de">
  ```
- **L'impatto SEO:** Il sito è interamente scritto in italiano, ma comunica ai motori di ricerca (Google, Bing) di essere in tedesco. Questo disorienta gli algoritmi di indicizzazione geografica e penalizza drasticamente il posizionamento per tutte le ricerche in lingua italiana provenienti dal Canton Ticino e dall'area insubrica/italiana.

### 1.2 Tag `<title>` e Meta Tag Inconsistenti
- **Home:** `<title>Home</title>`
- **Chi siamo:** `<title>Chi siamo</title>`
- **Cataloghi:** `<title>Cataloghi</title>`
- **Contatto:** `<title>Contatto</title>`
- **L'impatto:** I titoli di pagina sono il fattore on-page n°1 per il ranking SEO. Avere titoli generici di una sola parola senza indicazione del brand (`T-Work & Gadget`), dei servizi (`Abbigliamento da lavoro`, `Gadget promozionali`) né della località (`Chiasso, Ticino`) significa **essere invisibili sui motori di ricerca per qualsiasi ricerca di settore**.

### 1.3 Black-Hole dei Cataloghi su Google Drive (Nessuna Indicizzazione Prodotti)
- **Il problema:** I cataloghi dei brand trattati (Portwest, Sol's, Giblor's, Clique, Neri, Rossini, Makito, Siggi, ecc.) sono linkati come **file PDF esterni su Google Drive** (`drive.google.com/file/d/...`).
- **L'impatto:**
  1. Google non indicizza i singoli prodotti o marchi sul dominio `t-workgadget.ch`.
  2. L'utente che cerca "giacche alta visibilità Portwest Chiasso" o "divise chef Giblor Ticino" non approderà mai sul sito di T-Work.
  3. L'autorità di dominio non cresce perché il traffico viene regalato all'infrastruttura Google Drive.

### 1.4 Assenza Totale di Dati Strutturati (Schema.org / JSON-LD)
- Non esiste alcun markup Schema.org: assenti `LocalBusiness`, `Organization`, `PostalAddress`, `geo` (coordinate di Chiasso), `openingHours` e `contactPoint`.
- Google non è in grado di mostrare snippet arricchiti, box di contatto aziendale verificato o geolocalizzazione automatica nei risultati di ricerca.

### 1.5 File Tecnici: Robots.txt & Sitemap
- Il file `robots.txt` è completamente vuoto (0 direttive, nessuna referenza alla sitemap).
- Nessuna strategia di canonizzazione esplicita dei link.

---

## 2. 🎨 Audit UI/UX, Design e Web Typography

### 2.1 Refusi Imbarazzanti nei Titoli di Primo Piano
Nei blocchi promozionali della Home page sono visibili errori ortografici che minano immediatamente l'autorevolezza del brand agli occhi di un responsabile acquisti aziendale:
1. **`Abbigliamentpo promozionale`** (errore di battitura evidente ripetuto nel titolo H3).
2. **`Abbigliamentpo da lavoro`** (stesso errore ripetuto nel secondo blocco H3).
3. **`Richiedi un offerta`** (manca l'apostrofo obbligatorio in italiano: "un'offerta").

### 2.2 Icone Fantasma nella Barra di Navigazione (*Phantom Affordances*)
- Nella testata (a destra del menù principale) compaiono 3 icone ben visibili:
  - Icona Cuore / Preferiti (`favourite_icon_navi_neu.svg`)
  - Icona Borsa Spesa / Carrello (`shopping_bag.svg`)
  - Icona Omino / Profilo Utente (`profile_icon_navi.svg`)
- **Problema gravissimo:** Queste icone **non sono cliccabili e non hanno alcun link**. Sono elementi grafici statici lasciati lì dal template di partenza.
- **Effetto sull'utente:** Il visitatore presume che il sito sia un e-commerce o che vi sia un'area personale; cliccando e non ottenendo alcuna reazione, percepisce il sito come **rotto o non funzionante**.

### 2.3 Scheletro di Template Tedesco Non Bonificato
Nel codice sorgente emergono chiaramente le classi originali del template Webflow tedesco mai ripulite o ristrutturate:
- `container_begruessung` (da *Begrüssung* = Benvenuto)
- `padding_klein` (*klein* = piccolo)
- `teaserdiv_right` e classi duplicate

### 2.4 Esperienza Utente Mobile & Cataloghi Inutilizzabili
- Cliccare su uno dei 14 cataloghi da smartphone costringe l'utente a scaricare o visualizzare pesanti PDF su Google Drive (da 30 a oltre 100 MB).
- L'esperienza su rete mobile è disastrosa: tempi di caricamento lunghi, consumo dati elevato, difficoltà di zoom e impossibilità di richiedere un preventivo per un articolo specifico mentre si sfoglia.

### 2.5 Web Typography & Layout Rhythm
- Font utilizzato: *Lato*, richiamato tramite script WebFont esterno bloccante.
- Assenza di una chiara gerarchia visiva: i blocchi di testo ("Benvenuti alla T-work & gadget...") sono muri di testo indifferenziati, privi di punti d'appoggio per la scansione visiva veloce (niente bullet point, niente numeri chiave, niente evidenziazioni visive).

---

## 3. 💼 Audit Tecnico & Conversion Rate (CRO)

### 3.1 Form Contatti con Metodo HTTP GET (Falla di Privacy e Standard)
- Nella pagina `/contatto`, il form invia i dati tramite `method="get"`:
  ```html
  <form id="email-form" name="Email Form" method="get" ...>
  ```
- **Conseguenza:** I dati inseriti dall'utente (Nome, Cognome, Società, Telefono, Indirizzo E-mail e Testo del Messaggio) vengono accodati nell'URL in chiaro come parametri query string. È una pratica sconsigliata e contraria ai basilari standard web, che espone dati di contatto nella cronologia del browser e nei log di rete.

### 3.2 CTA Basate su Link `mailto:`
- I bottoni "Richiedi un'offerta" sulla Home rimandano direttamente a un link `mailto:info@t-workgadget.ch`.
- Su desktop senza client email preconfigurato (situazione comunissima con webmail come Gmail o Outlook 365 nel browser) il click non produce alcun effetto o tenta di aprire l'applicazione di sistema non configurata, provocando la perdita immediata del lead.

### 3.3 Dipendenza da Webflow & Canoni Ricorrenti Ingiustificati
- Il sito è ospitato su Webflow, comportando un costo di abbonamento ricorrente in valuta estera per mantenere online 4 pagine statiche di testo e link Google Drive.
- La manutenzione dei cataloghi tramite Webflow è macchinosa e non offre le funzionalità di un vero catalogo B2B.

---

## 4. 🚀 La Soluzione Strategica: Il Nuovo Sito T-Works

Per trasformare il sito web da costo passivo a **generatore automatico di preventivi e clienti B2B**, la strategia consigliata da Kraken prevede:

### 4.1 Architettura e Tecnologia
- **Sito Web ad alte prestazioni (Next.js / Astro o WordPress Headless ultra-veloce):**
  - Hosting moderno ad alte prestazioni con SSL svizzero/europeo conforme alla **nLPD** (Legge federale sulla protezione dei dati).
  - Codice pulito, accessibile e conforme ai Core Web Vitals (punteggio 95+ su Google PageSpeed).
  - Nessun canone gonfiato Webflow: controllo totale dei dati e scalabilità.

### 4.2 Catalogo Prodotti B2B Interattivo
- **Addio ai PDF su Google Drive:**
  - Creazione di sezioni dedicate per categoria: *Abbigliamento da Lavoro*, *Alta Visibilità*, *Horeca & Medicale*, *Abbigliamento Promozionale*, *Gadget Aziendali & Tech*.
  - Schede prodotto indicizzabili singolarmente su Google con foto, varianti colore e dettagli di personalizzazione (serigrafia, ricamo, transfer, incisione laser).
  - Funzionalità **"Aggiungi a Richiesta Preventivo" (Request a Quote)**: il cliente aziendale seleziona i prodotti, specifica le quantità stimate, carica il proprio logo vettoriale e invia la richiesta con un solo click.

### 4.3 Strategia SEO Locale (Ticino & Svizzera)
- Ottimizzazione semantica specifica:
  - *Abbigliamento da lavoro Chiasso, Mendrisiotto, Lugano, Canton Ticino*
  - *Gadget personalizzati aziendali Svizzera*
  - *Forniture antinfortunistiche e DPI Ticino*
- Implementazione Schema.org LocalBusiness completo con geolocalizzazione, orari, recapiti telefonici diretti e WhatsApp Business per conversione immediata.
- Predisposizione bilingue reale (Italiano / Tedesco) per aggredire anche il mercato della Svizzera interna e gli ordini corporate d'Oltralpe.

### 4.4 Identità Visiva e Brand Authority
- Design moderno, solido e industriale coerente con il settore "Work & Gadget".
- Eliminazione di elementi decorativi rotti (icone carrello/profilo finte).
- Sezione "Come Lavoriamo / Tecniche di Personalizzazione" (Ricamo, Serigrafia, Sublimazione, Tampografia) per rassicurare il cliente sulla qualità manifatturiera.

---

## 5. 📊 Tabella Comparativa: Stato Attuale vs. Nuovo Sito Kraken

| Parametro | Stato Attuale (Webflow) | Nuovo Sito T-Works (Kraken) |
|---|---|---|
| **Lingua HTML** | Errata (`lang="de"`) | Corretta (IT nativo + DE opzionale) |
| **Titoli SEO & Meta** | Generici (`Home`, `Chi siamo`) | Ottimizzati per parole chiave territoriali |
| **Cataloghi** | Link esterni Google Drive | Catalogo interattivo navigabile e indicizzato |
| **Richiesta Preventivo** | `mailto:` e Form GET con falle | Carrello preventivi B2B con upload logo |
| **Testate & UI** | Icone finte e refusi nei titoli | UI/UX professionale ad alta conversione |
| **Dati Strutturati** | Assenti (0 schema JSON-LD) | `LocalBusiness` + `Product` completi |
| **Prestazioni & Hosting** | Dipendente da Webflow ($$$) | Stack proprietario, veloce e scalabile |
