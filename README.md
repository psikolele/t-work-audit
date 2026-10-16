# T-Work & Gadget Sagl — Audit & Proposta Nuovo Sito Web

Dossier esecutivo, analisi tecnica e prototipo interattivo per il rilancio digitale e la generazione preventivi B2B di **T-Work & Gadget Sagl** (Chiasso, Canton Ticino).

---

## 🌐 Risorse Live Online (GitHub Pages)

- 📊 **[Presentazione Esecutiva & Audit](https://psikolele.github.io/t-work-audit/)**  
  Analisi completa delle criticità del sito attuale (`t-workgadget.ch`), confronto prima/dopo e piano di rifacimento.
  
- 🚀 **[Prototipo Funzionante Nuovo Sito](https://psikolele.github.io/t-work-audit/demo-prototype/)**  
  Demo interattiva con catalogo prodotti B2B (Portwest, Clique, Sol's, Giblor's, Rossini, Makito), filtri istantanei e carrello preventivi con caricamento logo.

- 📄 **[Scarica Report Ufficiale in PDF](https://psikolele.github.io/t-work-audit/Audit_e_Proposta_TWorks_Kraken.pdf)**  
  Documento formale impaginato per Emanuele Frigerio.

---

## 🧱 Stack del Sito Definitivo
- **Piattaforma:** WordPress + WooCommerce in modalità B2B Catalogo & Preventivo (ADR-002 in `DESIGN-LOG.md`)
- **Automazione catalogo:** WooCommerce REST API (`/wp-json/wc/v3/`) con Application Passwords
- **Dominio & hosting:** `t-workgadget.ch` già su Hostpoint (resta il passaggio del contratto all'account di Emanuele)

## 🛠️ Stack Tecnologico Prototipo
> Il prototipo è una demo statica di interfaccia; il sito definitivo sarà su WordPress + WooCommerce.

- **Frontend:** HTML5, Tailwind CSS (Mobile-First responsive), Lucide Icons
- **SEO & Microdati:** Schema.org `LocalBusiness` per Chiasso/Ticino, OpenGraph `it_CH`
- **Features B2B:** Carrello quotazione in slide-over, simulazione upload logo aziendale, ricerca live articoli
