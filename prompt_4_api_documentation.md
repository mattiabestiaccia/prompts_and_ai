# Esempio Prompt: Creazione Documentazione API

Agisci come un technical writer esperto con anni di esperienza nella documentazione di API REST.

Ho sviluppato un'API per la gestione di un sistema di prenotazioni. Ecco i dettagli:

## Informazioni Base API

- **Base URL:** `https://api.example.com/v1`
- **Autenticazione:** Bearer Token (JWT)
- **Formato risposte:** JSON
- **Versioning:** URL path

## Endpoints da Documentare

### 1. Gestione Utenti
- `POST /users` - Registrazione nuovo utente
- `GET /users/{id}` - Dettagli utente
- `PUT /users/{id}` - Aggiorna profilo
- `DELETE /users/{id}` - Elimina account

### 2. Gestione Prenotazioni
- `POST /bookings` - Crea prenotazione
- `GET /bookings` - Lista prenotazioni (con filtri)
- `GET /bookings/{id}` - Dettaglio prenotazione
- `PATCH /bookings/{id}` - Modifica prenotazione
- `DELETE /bookings/{id}` - Cancella prenotazione

### 3. Risorse Disponibili
- `GET /resources` - Lista risorse prenotabili
- `GET /resources/{id}/availability` - Verifica disponibilità

## Ti chiedo di generare:

1. **Documentazione completa per ogni endpoint** che includa:
   - Descrizione funzionale
   - Metodo HTTP e URL
   - Headers richiesti
   - Parametri (path, query, body) con tipi e validazioni
   - Esempio di request
   - Esempio di response (successo e errore)
   - Codici di stato HTTP possibili

2. **Sezione introduttiva** con:
   - Overview dell'API
   - Guida all'autenticazione
   - Rate limiting e best practices
   - Gestione errori e codici comuni

3. **Esempi pratici** di:
   - Flow completo di prenotazione
   - Gestione refresh token
   - Paginazione delle liste

Formato output:
- Usa Markdown con syntax highlighting per i blocchi di codice
- Organizza in sezioni chiare e navigabili
- Includi un indice/table of contents
- Aggiungi note e warning dove appropriato
