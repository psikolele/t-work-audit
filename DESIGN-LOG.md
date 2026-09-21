# DESIGN-LOG — T-Works (T-Work & Gadget Sagl)

## 📌 Concetto Condiviso (Integrità Concettuale Brooks)
- **Cliente:** Emanuele Frigerio — T-Work & Gadget Sagl (Chiasso, Svizzera)
- **Obiettivo Primario:** Audit spietato dello stato attuale del sito webflow per guidare e motivare il rifacimento totale della piattaforma da parte di Kraken.
- **Missione del Nuovo Progetto:** Trasformare una vetrina statica con link Google Drive esterni e gravi bug di usabilità in un portale B2B interattivo con catalogo prodotti indicizzabile, carrello preventivi con caricamento loghi e SEO territoriale per il Canton Ticino e Svizzera.

## 🧱 Stato Attuale & Debito Rilevato (Audit del 21/09/2026)
1. **SEO:** `lang="de"` su testo italiano, title tag generici a parola singola, zero dati strutturati, zero indicizzazione dei marchi/prodotti (tutti su PDF Google Drive).
2. **UI/UX:** *Phantom affordances* (icone carrello/profilo finte e non cliccabili), refusi madornali nei titoli H3 ("Abbigliamentpo", "Richiedi un offerta"), residui di classi template tedesco.
3. **Conversione:** Form in GET che espone dati lead in URL, CTA `mailto:` che blocca la conversione su desktop/mobile.

## 🧭 Budgeted Resource & Vincoli
- **Budgeted Resource Principale:** Tasso di conversione B2B (lead caldi da preventivatore con logo aziendale) e velocità/semplicità di consultazione mobile.
- **Vincoli Rigidi:** Rispetto conformità svizzera nLPD, interfaccia pulita e professionale B2B, nessuna dipendenza da PDF esterni per il catalogo principale.
- **Out-of-Scope (Fase 1):** E-commerce transazionale con gateway di pagamento con carta di credito immediato (il modello di business è quotazione preventivo su misura B2B in base a quantitativi e tecnica di personalizzazione).

---
## 📝 Registro Decisioni Architetturali (ADR)
- **ADR-001 (21/09/2026): Scelta di rifacimento completo rispetto a patch Webflow.**
  - *Motivazione:* Modificare l'attuale template Webflow lascerebbe in piedi il costo ricorrente, l'impossibilità di gestire un vero configuratore preventivi e la complessità di un catalogo prodotti serio. Il ROI per il cliente si ottiene solo con una piattaforma dedicata Kraken.
