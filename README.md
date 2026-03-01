# Veronik (MVP)

App Android (Kotlin + Jetpack Compose) che importa un Excel dei turni e risponde in chat.

## Domande supportate
- "Giovedì Cognome Nome che turno ha?"
- "Settimana 2 giovedì Cognome Nome che turno ha?"
- "05/03/2026 Cognome Nome che turno ha?" (anche 5/3/2026 o 05-03-2026)

## Risposta
Sempre nel formato: **Giorno dd/MM/yyyy — Cognome Nome: Codice/Numero turno**.

## Nota data iniziale
La data iniziale viene letta dal nome file con pattern dd-mm-yyyy.
Esempio: `Ciclazione_Terracina_T100_02-03-2026 3.xlsx` -> startDate = 02/03/2026.

## Avvio
1) Apri la cartella `Veronik` in Android Studio
2) Sync Gradle
3) Run su emulatore o telefono