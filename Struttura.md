# Tesi di laurea di Informatica

## Struttura del documento

1. Introduzione
      1. L'azienda
            1. Di cosa si occupa e servizi offerti
            2. Nascita
            3. Progetti importanti
            4. Premi e certificazioni
            
      2. Progetto di stage
            1. Descrizione del progetto
            2. Motivo della nascita del progetto
      
      3. Obiettivi dello stage
            1. Obiettivi obbligatori
            2. Obiettivi desiderabili
            3. Vincoli tecnologici
      
      4. Pianificazione del lavoro

2. Analisi dei formati e dei protocolli di trasmissione standard
      1. Codifica video
            1. Storia dei formati
            2. Formati comunemente usati
                  - Pregi
                  - Difetti
                  - Applicabilità

      2. Protocolli
            1. Storia dei protocolli e loro standardizzazione
            2. Differenza tra protocolli real time e on demand
            3. Problemi dell'UDP con i firewall

      3. Architettura di una piattaforma di streaming
            1. Struttura di massima
            2. Inbound
                  - Streaming
                  - Upload file
            3. Storage
                  - Sistemi elastici
                  - Organizzazione dei contenuti
            4. Outbound
                  - Relay streaming
                  - Codifica al volo
                  - CDN
                  - Standard e reti

      4. Trasmissione di contenuti in mobilità
            1. Difficoltà della trasmissione in mobilità
            2. Reti
                  1. WiFi
                  2. Bluetooth
                  3. Rete 4G 

      5. Soluzioni esistenti
            1. YouTube
            2. Red5 Pro
            3. Contus Vplay
            4. Streamroot
            5. Wowza Streaming Engine

      6. Nuovi orizzonti
            1. Blockchain
            2. Streaming peer to peer

3. Analisi dei requisiti
      1. Elenco dei requisiti
            1. Classificazione dei requisiti
            2. Notazione dei requisiti
            3. Requisiti funzionali
            4. Requisiti di qualità
            5. Requisiti di ambiente

      2. Usecase e diagrammi UML

4. Tecnologie utilizzate
      1. Linguaggi di programmazione
            - Perché Java?
                  - Integrazione con Android
                  - Sistemi virtualizzati e multipiattaforma
                  - Facile parallelismo

      2. Piattaforma di sviluppo (TomCat8)
            - Perché TomCat8?
                  - Piattaforma di riferimento
                  - Codice open source
                  - Facile configurazione

      3. WebSocket in Java
            - Interfacce
            - Implementazioni
                  - javax.WebSocket espone solo l'interfaccia
            - Librerie utilizzate
                  - Scelta delle librerie utilizzate

      4. JSON con GSON
            - Molto meno prolisso di XML
            - Scelto per semplificare il debugging della piattaforma
            - Semplice da comprendere

      5. Strumenti di supporto
            1. Strumenti di test e verifica
                  - JUnit
            2. Strumenti di analisi di rete
                  - Wireshark
      
      6. Ambiente di sviluppo e versionamento
            1. IntelliJ Idea Community edition
            2. Git e Bitbucket
            3. Docker
      
5. Progettazione e codifica
      1. Scelta dei formati e dei potocolli
      2. Scelta dei componenti riutilizzabili dell'architettura
      3. Progettazione del sistema di autenticazione
      4. Progettazione del sistema di relay
            - Scalabilità

      6. Codifica del sistema di autenticazione
      7. Codifica del sistema di relay

6. Qualifica
      1. Verifica
            1. Analisi statica
            2. Analisi dinamica
      
      2. Validazione
            1. Validazione interna
            2. Validazione esterna

7. Conclusioni
      1. Obiettivi
      2. Conoscenze acquisite
      3. Futuri sviluppi del progetto di stage
      4. Valutazione personale
