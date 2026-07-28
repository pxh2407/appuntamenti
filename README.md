# 📅 I Miei Appuntamenti

Applicazione semplice per gestire appuntamenti e promemoria. Funziona nel browser, senza installare nulla e senza connessione internet.

## Come si usa

Apri `index.html` con un doppio clic.

- **Aggiungi** un appuntamento indicando cosa, giorno, ora ed eventuali note
- **✏️ Modifica** o **🗑️ Elimina** ogni voce dell'elenco
- **🖨️ Stampa elenco** per averlo su carta
- **🔔 Prova suono** per verificare l'avviso sonoro

## Il rapporto con Google Calendar

Il pulsante **📆 Google** accanto a ogni appuntamento lo porta dentro Google Calendar, con titolo, data e note già compilati: basta premere *Salva*. Da quel momento l'appuntamento è sincronizzato su tutti i dispositivi e avvisa anche a telefono bloccato.

Il pulsante **📅 Vedi i miei appuntamenti su Google** apre il calendario vero e proprio (sul telefono l'app di Google).

L'app non incorpora il calendario nella pagina: sui telefoni Google blocca i cookie di terze parti e il riquadro resterebbe vuoto. Meglio un pulsante che funziona sempre.

## Avvisi

- Riquadro giallo con gli impegni di **oggi** e di **domani** all'apertura
- Campanella sonora quando ci sono impegni in vista
- Promemoria con suono **30 minuti prima** dell'orario, se la pagina è aperta

## Apertura automatica su Windows

Il file `promemoria.html` serve per le aperture automatiche: controlla il calendario e mostra l'app **solo se** ci sono impegni oggi o domani, altrimenti si chiude da solo dopo pochi secondi.

Sul computer è impostato per aprirsi all'accensione e ogni giorno alle 9:00, 11:00 e 15:30.

## Dove finiscono i dati

Gli appuntamenti restano salvati **nel browser del computer che stai usando** (localStorage): non vengono inviati da nessuna parte e non sono contenuti in questo repository.
