# Mobile Development - Assignment 1

## Specifiche generali
**Nome Applicazione:** MedsReminder
**Tipologia:** Health tracker
**Autore/i:** Eugenio Marzona - Mat. 128623

**Oggetto:** Progettare la "visione" di un'applicazione mobile utilizzando gli stumenti visti a lezione.

Devono essere prodotti, come minimo:
- Un *System Concept Statement*
- Una lista dei requisiti (*Requirements Brief*)
- Questi devono essere ordinati secondo *priorit&agrave;* (bassa/media/alta). Non &egrave; necessario utilizzare modelli cost/impact o kano per la loro organizzazione.

Altre tecniche possono essere applicate per delineare la visione dell'applicazione se ritenuto utile/necessario.

---
## 1. Envision - System Concept Statement

Per il paziente posto d'innanzi ad un nuovo percorso terapeutico, tenere traccia di appuntamenti e analisi ed assicurarsi dell'assunzione puntuale di farmaci, pu&ograve; diventare un compito complesso.
 
Affidarsi ai soli appunti e alle agende cartacee si rivela spesso inefficace e puo& capitare di dimenticare di fissare una visita specialistica per tempo o di assumere in ritardo la pastiglia della giornata.
 
L’applicazione per piattaforme mobile MedsReminder permette all’utente di creare la propria agenda elettronica, per memorizzare scadenze e tenere traccia dell’assunzione giornaliera di farmaci.
 
Utilizzando inoltre il sistema di “reminders”, l'utente potr&agrave; scegliere di ricevere, nei momenti della giornata che ritiene pi&ugrave; opportuni, una serie di promemoria interattivi.


---
## 2. Envision - Requirements Brief

Per delineare in maniera accurata lo "scope" dell'applicazione, le features elencate nelle successive sezioni sono state suddivise in due gruppi:
- **Core:** Ossia tutto cio' che ha a che fare, in maniera diretta o indiretta, con le feature *principali* dell'applicazione.
Queste sono state espresse in maniera succinta nel SCS e vengono qui espanse.
- **Possible Extensions:** Tutte le feature ritenute secondarie. Hanno a che fare solo tangenzialmente con la visione principale dell'applicazione ma, potrebbero essere utili per offrire all'utente un valore aggiunto rispetto ad altre applicazioni simili.
Nel contesto delle applicazioni di health tracking, alcuni esempi di feature secondarie potrebbero essere: registrare peso corporeo, tasso glicemico, pressione sanguigna ecc...

### Feature List - Core
| Nome | Descrizione | Priorit&agrave; |
|:---:|:---|:---:|
| **(Route) Dashboard** | Schermata riassuntiva di prossimi appuntamenti e farmaci assunti/da assumere nel corso della giornata. | _alta_ |
| **(Route) Appointments** | Visualizzazione, in stile agenda/calendario, di tutti gli appuntamenti inseriti dall'utente. | _alta_ |
| **(Route) Meds** | Check-list delle assunzioni giornaliere di farmaci dell'utente. La visualizzazione potrebbe essere giornaliera, settimanale, o altro. La schermata &egrave; interattiva e permette all'utente di "spuntare" i farmaci che ha gi&agrave; assunto. | _alta_ |
| **(Sub-Route) Insert Appointment** | Form per l'inserimento in agenda di appuntamenti. | _alta_ |
| **(Sub-Route) Insert Meds** | Form per l'aggiunta di farmaci alla lista delle assunzioni giornaliere dell'utente. | _alta_ |
| **(Sub-Route) Global settings** | Settings globali dell'applicazione, per la gestione di lingua di interfaccia, notifiche, ecc... | _media_ |
| **(Sub-Route) Appointment Details** | Visualizzazione dettagliata di uno specifico appuntamento inserito in agenda dall'utente. | _media_ |
| **Auto-schedule recurring appointments** | Sistema di auto-scheduling di appuntamenti ricorrenti. | _bassa_ |
| **Opt-in reminders** | Reminders opzionali, con notifica push, per ricordare all'utente appuntamenti e assunzione di farmaci. | _alta_ |
| **Color coded reminders** | Reminders colorati per aiutare l'utente a differenziare a colpo d'occhio reminders per appuntamenti e per assunzione di farmaci. | _bassa_ |
| **Interactive Meds reminders** | Reminders per l'assunzione di farmaci interattivi. Con l'obiettivo di permettere all'utente di "spuntare" i farmaci gi&agrave; assunti senza dover per forza accedere all'applicazione. | _bassa_ |
| **Multi-language Interfaces** | Supporto per altre lingue, focus principale su supporto italiano/inglese. | _media_ |
| **Multi-locales Support** | Supporto altri formati di data/ora, unit&agrave; di misura ecc... | _media_ |
| **Google Calendar Sync** | Sincronizzazione (one-way) degli appuntamenti fissati sull'applicazione con google calendar. | _media_ |
| **Outlook Calendar Sync** | Sincronizzazione (one-way) degli appuntamenti fissati sull'applicazione con outlook calendar. | _bassa_ |
| **On-device data store** | Organizzazione dei dati inseriti dall'utente in database locale basato su modello relazionale. | _alta_ |
| **Password Protected Login** | Sistema opzionale di login con codice o pin per preservare la privacy dell'utente. | _media_ |
| **Google Maps integration** | Integrazione con google maps per poter assegnare un luogo specifico agli appuntamenti inseriti dall'utente. | _bassa_ |
| **Low/Impaired Vision Support** | Supporto, con visualizzazione alternativa dell'interfaccia (high contrast/larger fonts and buttons), ad utenti con problemi di visione. | _media_ |

### Feature List - Possible extensions
| Nome | Descrizione | Priorit&agrave; |
|:---:|:---|:---:|
| **Secure sign-in & log-in** | Sistema di registrazione e login sicuro on-app, con l'obiettivo di dare all'utente la possibilit&agrave; di accedere ai propri dati su diversi dispositivi. | _alta_ |
| **Off-device data store** | Organizzazione dei dati dell'utente in database remoto (varie soluzioni possibili, sql/nosql). | _alta_ |
| **ICal Calendar Sync** | Sincronizzazione (one-way) degli appuntamenti fissati sull'applicazione con iCalendar. | _media_ |
| **(Sub-Route) On-app Medical Records** | Cartella clinica dell'utente on-app. | _media_ |
| **(Route) Weight tracking** | Sistema di tracking del peso corporeo, con grafici e indicazione di indice di massa corporeo.| _bassa_ |
| **(Route) Blood Pressure tracking** | Sistema di tracking della pressione sanguigna. | _bassa_ |
| **(Route) Glycemic levels tracking** | Sistema di tracking del livello di glicemia. | _bassa_ |
| **Integration with Google Health** | Integrazione con l'app di sistema Google Health. | _bassa_ |

---
## 3. Envision - Assign Priorities
Come ulteriore strumento di modellazione ho deciso di provare ad inserire i requisiti core, definiti nella fase precedente, in un diagramma 2x2 cost/impact.

![Image](./costimpact.png)