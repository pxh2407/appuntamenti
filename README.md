# 📅 I Miei Appuntamenti

Applicazione semplice per gestire appuntamenti e promemoria. Funziona nel browser, senza installare nulla e senza connessione internet.

## Come si usa

Apri `index.html` con un doppio clic.

- **Aggiungi** un appuntamento indicando cosa, giorno, ora ed eventuali note
- **✏️ Modifica** o **🗑️ Elimina** ogni voce dell'elenco
- **🖨️ Stampa elenco** per averlo su carta
- **🔔 Prova suono** per verificare l'avviso sonoro

## Avvisi

- Riquadro giallo con gli impegni di **oggi** e di **domani** all'apertura
- Campanella sonora quando ci sono impegni in vista
- Promemoria con suono **30 minuti prima** dell'orario, se la pagina è aperta

## Apertura automatica su Windows

Il file `promemoria.html` serve per le aperture automatiche: controlla il calendario e mostra l'app **solo se** ci sono impegni oggi o domani, altrimenti si chiude da solo dopo pochi secondi.

Sul computer è impostato per aprirsi all'accensione e ogni giorno alle 9:00, 11:00 e 15:30.

## Dove finiscono i dati

Gli appuntamenti restano salvati **nel browser del computer che stai usando** (localStorage): non vengono inviati da nessuna parte e non sono contenuti in questo repository.
