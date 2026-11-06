PESO & PLICA - PWA CON ARCHIVIO SU FILE

ARCHIVIAZIONE
- Al primo utilizzo selezionare “Collega cartella”.
- Scegliere, ad esempio, Documenti/PesoPlica.
- La PWA crea e aggiorna automaticamente peso_plica_dati.json a ogni inserimento, modifica o cancellazione.
- IndexedDB è usato solo come cache locale. Il file JSON è l'archivio principale.
- Se Android o Chrome revocano l'autorizzazione, la PWA richiede nuovamente il permesso prima di salvare.
- Nessun dato storico è precaricato.

INSTALLAZIONE SU ANDROID 12
1. Pubblicare tutti i file su HTTPS, ad esempio GitHub Pages, Cloudflare Pages o Netlify.
2. Aprire l'indirizzo con Google Chrome aggiornato.
3. Installare dal pulsante “Installa” o dal menu di Chrome.
4. Dalla schermata Oggi scegliere “Collega cartella” e autorizzare una cartella del dispositivo.

LIMITI DI SICUREZZA DEL BROWSER
- Una PWA non può scegliere autonomamente una cartella. La prima autorizzazione deve essere concessa dall'utente.
- Il permesso può essere richiesto nuovamente dopo riavvii, pulizia dei dati del sito o aggiornamenti del browser.
- Il salvataggio viene bloccato se il file non può essere aggiornato, evitando che la sola cache del browser diventi inconsapevolmente l'unica copia.
