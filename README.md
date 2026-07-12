# Bonifiche Ferraresi S.p.A. - Progetto Sostenibilità ESG

## Descrizione
Il progetto presenta una pagina web dedicata alla sostenibilità di Bonifiche Ferraresi S.p.A., impresa appartenente al settore primario/agroindustriale. La pagina sintetizza le informazioni dell'ultimo report disponibile e permette il download del documento inserito nella repository.

## Obiettivo
L'obiettivo è trasformare i contenuti del report di sostenibilità in una pagina semplice, ordinata e consultabile, realizzata esclusivamente con HTML e CSS.

## Funzionalità principali
- Presentazione dell'impresa e del contesto aziendale.
- Menu di navigazione con sezioni: Chi siamo, Azienda, ESG, Dove ci troviamo, Report e Contatti.
- Tre card cliccabili dedicate ad Ambiente, Sociale e Governance.
- Approfondimenti interni alle card senza JavaScript, usando gli elementi HTML `<details>` e `<summary>`.
- Inserimento di statistiche sintetiche tratte dal report: incidenti ambientali, rischi climatici, personale, costi del personale, amministratori indipendenti e controlli cybersecurity.
- Pulsante per il download del report PDF.
- Layout responsive per computer, tablet e smartphone.

## Tecnologie utilizzate
- HTML5
- CSS3

## Struttura consigliata
```text
tesi-bonifiche-ferraresi/
├── index.html
├── style.css
├── README.md
├── immagini/
│   ├── logo-bf.png
├── report/
│   └── Report_Sostenibilita_2025.pdf
└── relazione/
    └── Relazione.docx
```

## Avvio del progetto
Per visualizzare la pagina è sufficiente aprire il file `index.html` nel browser oppure usare l'estensione Live Server di Visual Studio Code.

## Nota sul report
Il file PDF deve essere inserito nella cartella `report/` e deve avere lo stesso nome indicato nel collegamento HTML:

```html
<a href="report/Report_Sostenibilita_2025.pdf" class="btn" download>
```

