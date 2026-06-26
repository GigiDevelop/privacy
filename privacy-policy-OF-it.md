# Informativa sulla privacy — OmniFitness

**Ultimo aggiornamento:** giugno 2026  
**App:** OmniFitness (`com.gigidevelop.omnifitness`)  
**Contatto:** develop@abcdef.it

---

## 1. Chi siamo

OmniFitness è un'applicazione Android per **attività fisica e sport** (corsa, ciclismo, trekking, padel, HIIT, passi, gruppo in uscita).  
**Non è un'app medica** e **non fornisce diagnosi o consigli clinici**.

**Non esiste un account utente obbligatorio** e **non raccogliamo dati su server gestiti da noi** per le funzioni principali dell'app.

---

## 2. Quali dati trattiamo

Per impostazione predefinita i dati restano **sul tuo dispositivo**.

| Dato | Uso |
|------|-----|
| Posizione GPS | Tracking corsa, ciclismo, trekking; mappa percorso; gruppo in uscita |
| Passi giornalieri | Dashboard attività (sensore / riconoscimento attività) |
| Metriche allenamento | Distanza, tempo, ritmo/velocità, dislivello, tracciato opzionale |
| Tracciati GPX | Import, navigazione sentiero, export |
| Storico sessioni | Elenco uscite GPS completate |
| Dati «Ghost» | Confronto con le tue sessioni passate (calcolo locale) |
| Attrezzatura (scarpe, catena, ecc.) | Conteggio chilometri e avvisi usura |
| Obiettivo settimanale | Km o minuti in movimento |
| Partite padel | Punteggio, timeline punti, impostazioni partita |
| Frequenza cardiaca (padel) | Solo se autorizzi **Health Connect**; intensità e tenuta sportiva |
| Sessioni HIIT | Durata, round, ripetizioni, modalità |
| Promemoria | Giorni, orario e testo che inserisci tu |
| Nome visualizzato (gruppo) | Etichetta sulla mappa di gruppo |
| Preferenze app | Lingua, tema, modalità dati, impostazioni funzioni |

**Non** usiamo pubblicità. **Non** integriamo SDK di analytics o profilazione pubblicitaria di terze parti.

---

## 3. Dove sono conservati i dati

- Database locale **Room (SQLite)** sul dispositivo
- **DataStore** per preferenze (lingua, tema, impostazioni)
- File GPX importati nello storage dell'app

`android:allowBackup` è disabilitato nell'app: il backup automatico di Android verso Google non è utilizzato da OmniFitness per i dati dell'app.

---

## 4. Condivisione con terzi

**Non vendiamo né cediamo i tuoi dati.**

I dati possono lasciare il dispositivo **solo nei casi sotto indicati**:

### 4.1 Gruppo in uscita (opzionale)

Se attivi la funzione **Gruppo** e configuri un **relay WebSocket** (server o dispositivo scelto da te o dal tuo club), la app invia periodicamente la tua **posizione** e, se disponibile, **quota** al relay, per mostrarla agli altri membri del gruppo.  
Il relay **non è gestito da OmniFitness**: responsabilità e policy del server sono del soggetto che lo ospita.

### 4.2 Mappe

Per visualizzare le mappe dei percorsi salvati, l'app può scaricare **tile cartografiche** da fornitori terzi (es. OpenStreetMap) via Internet. In quel caso viene inviata solo la richiesta di tile necessaria alla visualizzazione, non l'intero storico allenamenti.

### 4.3 Health Connect

Se autorizzi l'accesso, OmniFitness **legge** la frequenza cardiaca da **Health Connect** (dati sincronizzati dal tuo orologio o da altre app che tu usi).  
OmniFitness **non scrive** dati sanitari in Health Connect. L'uso è limitato al modulo padel e ha finalità **sportiva**, non medica.

### 4.4 Nessun cloud OmniFitness

Le funzioni core (GPS, storico, padel, HIIT, equipment, promemoria) **non richiedono** un server dello sviluppatore. La modalità «Server» nelle impostazioni riguarda eventuale sincronizzazione su **infrastruttura configurata dall'utente**, non un servizio cloud proprietario obbligatorio.

---

## 5. Permessi Android

| Permesso | Motivo |
|----------|--------|
| Posizione (precisa / approssimativa) | Tracking GPS e mappa; gruppo attivo |
| Posizione in background | Solo durante sessione GPS o gruppo attivo, con **notifica persistente** |
| Attività fisica | Conteggio passi |
| Notifiche | Sessioni in corso, promemoria, avvisi equipment/gruppo |
| Internet | Mappe, relay gruppo (se configurato) |
| Fotocamera | Lettura QR invito gruppo (non obbligatoria se incolli il testo) |
| Vibrazione | Avvisi fuori sentiero, gruppo, equipment |
| Sveglie / avvio al boot | Rischedulazione promemoria dopo riavvio |
| Health Connect (frequenza cardiaca) | Solo padel, solo su tua richiesta |

I permessi sensibili sono richiesti **al momento dell'uso** della funzione correlata, quando possibile.

---

## 6. Finalità e base giuridica (UE / GDPR)

Trattiamo i dati per:

- erogare le funzioni dell'app che attivi (esecuzione del contratto / richiesta dell'interessato);
- migliorare l'esperienza sportiva sul dispositivo (interesse legittimo, senza profilazione commerciale).

Non effettuiamo decisioni automatizzate con effetti giuridici su di te.

**Titolare del trattamento:** lo sviluppatore raggiungibile a **develop@abcdef.it**.

---

## 7. I tuoi diritti

Hai diritto di accesso, rettifica, cancellazione, limitazione, opposizione e portabilità nei limiti applicabili.  
Poiché i dati sono in locale, puoi esercitarli in larga parte **eliminando i contenuti nell'app** o **cancellando i dati dell'app** dalle impostazioni Android.

Per richieste: **develop@abcdef.it**.

Hai diritto di proporre reclamo all'autorità di controllo del tuo Paese (in Italia: Garante per la protezione dei dati personali).

---

## 8. Sicurezza

I dati restano sul dispositivo sotto la protezione del sistema operativo Android. Le comunicazioni verso relay di gruppo usano il protocollo configurato dall'host (consigliato **WSS** in produzione).  
Non trasmettiamo i tuoi allenamenti a backend OmniFitness.

---

## 9. Conservazione ed eliminazione

I dati restano finché non li elimini tu:

- eliminazione singola di sessioni, partite padel, promemoria, equipment dall'app;
- **Impostazioni Android → App → OmniFitness → Cancella dati**;
- **disinstallazione** dell'app.

---

## 10. Minori

OmniFitness è destinata a un pubblico generale per attività sportiva. Non è progettata per bambini sotto i 13 anni. Se un minore usa l'app, deve farlo con consenso e supervisione di un genitore o tutore.

---

## 11. Modifiche

Aggiornamenti di questa informativa saranno indicati con nuova data in cima al documento. Per modifiche rilevanti, comunicazione tramite note di rilascio o nell'app.

---

## 12. Contatti

Per domande su privacy e dati: **develop@abcdef.it**

---

*Versione pubblicabile su Google Play — URL consigliato: repository `GigiDevelop/privacy` o pagina GitHub Pages del progetto.*
