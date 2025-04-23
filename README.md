# DatingApp

Benvenuto in **DatingApp**! Questa applicazione è progettata per connettere persone e facilitare incontri.

## Descrizione del Progetto

DatingApp è un'applicazione sviluppata interamente in **Java** che fornisce una piattaforma per creare un profilo personale, cercare persone con interessi simili e iniziare conversazioni. L'obiettivo principale dell'app è creare connessioni significative tra gli utenti.

## Funzionalità Principali

- **Registrazione e Login**: Gli utenti possono creare un account e accedere alla piattaforma in modo sicuro.
- **Creazione Profilo**: Personalizza il tuo profilo con informazioni personali e interessi.
- **Ricerca Utenti**: Trova persone
- **Chat in Tempo Reale**: Inizia conversazioni con altri utenti attraverso il sistema di messaggistica integrato.
- **Sicurezza e Privacy**: I dati degli utenti sono protetti grazie a protocolli di sicurezza avanzati.

## Tecnologie Utilizzate

Framework: Spring Boot
Persistenza dei Dati: JPA con supporto per database MySQL
Autenticazione: Spring Security e JWT
Validazione: Jakarta Validation API e Spring Validation
Documentazione API: Swagger (Springdoc OpenAPI)
Gestione delle Dipendenze: Maven
Altre Librerie:
Lombok per la riduzione del codice boilerplate
Firebase SDK per funzionalità avanzate


L'applicazione è sviluppata utilizzando il framework Spring Boot, che garantisce un'architettura scalabile e robusta. Integra anche strumenti moderni per la sicurezza e la validazione dei dati, rendendola affidabile e sicura.

### Prerequisiti
Assicurati di avere installati i seguenti strumenti:
- **Java 21** o versione successiva.
- **Maven** (per la gestione delle dipendenze).
- **MySQL** (come database).


### Download progetto
- git clone https://github.com/Angeloamenta/datingApp.git
- cd datingApp
- mvn clean install


### Configurazione del Database
1. Crea un database MySQL chiamato `dating_app`.
2. Configura il file `application.properties` nella directory `src/main/resources/` con i dettagli del database:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/dating_app
   spring.datasource.username=TUO_USERNAME
   spring.datasource.password=LA_TUA_PASSWORD
   spring.jpa.hibernate.ddl-auto=update


##  Come Avviare il Progetto
- mvn spring-boot:run
