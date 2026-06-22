# Informativa sulla privacy — OmniHealth

**Ultimo aggiornamento:** giugno 2026  
**App:** OmniHealth (`com.gigidevelop.omnihealth`)  
**Contatto:** develop@abcdef.it

---

## 1. Chi siamo

OmniHealth è un'applicazione Android per la gestione personale di terapie farmacologiche, parametri di salute, visite mediche e monitoraggio del sonno.  
**Non esiste un account utente** e **non raccogliamo dati su server nostri**.

---

## 2. Quali dati trattiamo

I dati restano **sul tuo dispositivo**, salvo dove indicato sotto.

| Dato | Uso |
|------|-----|
| Terapie, farmaci, assunzioni | Promemoria e storico |
| Parametri vitali (pressione, glicemia, SpO₂, peso, temperatura, ecc.) | Registro e grafici |
| Visite, esami, referti (testo e foto) | Promemoria e archivio |
| Audio visita medica | Registrazione in «In visita», solo con tuo consenso e consenso del medico |
| Foto prescrizioni | Archivio locale |
| Audio sonno | Analisi russamento **sul dispositivo** (TensorFlow Lite) |
| Profilo paziente (nome, indirizzo, città, telefono) | Messaggi caregiver / emergenza (se attivi la funzione) |
| Contatti emergenza (nome, telefono) | SMS e chiamate che **tu** configuri |
| Posizione | Solo se attivi il panico e concedi il permesso; inclusa nell'SMS ai contatti scelti |

**Non** leggiamo la rubrica del telefono. **Non** usiamo pubblicità né strumenti di tracciamento analytics.

---

## 3. Dove sono conservati i dati

- Database locale **cifrato** (SQLCipher)
- File audio/foto nello storage dell'app
- Backup JSON **cifrato** sul dispositivo; copia opzionale in `Documenti/OmniHealth` (se la memoria esterna è disponibile)

I file audio del sonno **non** sono inclusi nel backup automatico.

---

## 4. Condivisione con terzi

**Non vendiamo né cediamo i tuoi dati.**

I dati lasciano il telefono **solo se tu lo scegli**:

- **SMS** verso numeri che hai inserito (caregiver, escalation dose saltata, panico)
- **Chiamate** verso numeri che hai inserito
- **Posizione** nel testo SMS di panico (se permesso concesso)

Il contenuto degli SMS dipende dalle impostazioni e dai template che configuri. I destinatari sono operatori di telefonia e le persone i cui numeri hai indicato.

**Non** inviamo dati a server OmniHealth: l'app funziona offline e local-first.

---

## 5. Permessi Android

Microfono, SMS, telefono, posizione, notifiche e sveglie sono usati solo per le funzioni descritte sopra e solo quando le attivi o le usi.

---

## 6. Sicurezza

Database e backup cifrati sul dispositivo. Nessuna trasmissione verso backend dello sviluppatore.

---

## 7. Conservazione ed eliminazione

I dati restano finché non li elimini tu:

- **Impostazioni Android → App → OmniHealth → Cancella dati**, oppure
- **disinstallazione** dell'app

---

## 8. Minori

L'app è pensata per la gestione della propria salute o di un assistito con consenso del titolare del dispositivo. Non è destinata a bambini senza supervisione di un adulto.

---

## 9. Modifiche

Eventuali aggiornamenti di questa informativa saranno indicati con nuova data. Per modifiche rilevanti, l'aggiornamento sarà comunicato tramite note di rilascio o nell'app.

---

## 10. Contatti

Per domande su privacy e dati: **develop@abcdef.it**
