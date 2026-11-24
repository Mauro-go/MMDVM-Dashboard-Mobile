# MMDVM Dashboard Mobile v0.5.0
<img src="https://github.com/user-attachments/assets/280588f1-c8de-4f82-b3d0-7d4e4032e83e" width="250" alt="MMDVM Dashboard Mobile Screenshot" />

**Client Android universale per MMDVM Dashboard MQTT Multi.**

**Universal Android companion for MMDVM Dashboard MQTT Multi.**

Applicazione Android per monitorare e controllare da remoto i ripetitori radioamatoriali MMDVM attraverso API HTTPS e MQTT.

Android application for monitoring and remotely controlling amateur radio MMDVM repeaters through HTTPS APIs and MQTT.

---

## 🇮🇹 Italiano

### Funzionalità principali

- Dashboard con monitoraggio in tempo reale.
- Supporto per più ripetitori e selezione del nodo.
- Visualizzazione delle modalità operative e dei servizi.
- Monitoraggio dei gateway e dei collegamenti.
- Comunicazione tramite API HTTPS e MQTT.
- Interfaccia ottimizzata per smartphone.
- Lingue italiano e inglese, con selezione automatica o manuale.
- Icona personalizzata.

### Controllo remoto — ADMIN

La versione v0.5.0 introduce il controllo remoto delle modalità MMDVM tramite la Dashboard MQTT Multi e il relativo Agent.

- Accesso con credenziali amministratore.
- Attivazione e disattivazione individuale di D-Star, DMR, YSF, FM, P25, NXDN e M17, quando supportate.
- Visualizzazione degli stati ATTIVO/DISATTIVO.
- Pulsanti ON/OFF aggiornati in base allo stato.
- Comandi speciali MMDVMHost.
- Invio di messaggi CW.
- Conferma prima dell'invio dei comandi.
- Verifica dell'esecuzione tramite coda dei comandi.
- Aggiornamento automatico degli stati dopo le operazioni.
- Utilizzo dell'indirizzo HTTPS della Dashboard configurato nelle impostazioni.

### ⚠️ Requisiti importanti

**Per utilizzare tutte le funzionalità dell'applicazione è necessario installare l'ultima versione di MMDVM Dashboard MQTT Multi.**

Il controllo remoto richiede inoltre:

- Agent MQTT remoto correttamente configurato.
- Funzionalità Mobile Control abilitate.
- Account amministratore della Dashboard.
- Connessione HTTPS funzionante.

Le versioni precedenti della Dashboard potrebbero consentire soltanto alcune funzionalità di monitoraggio.

### Installazione APK

1. Aprire la sezione **Releases** del repository.
2. Scaricare l'APK firmato della versione più recente.
3. Installare l'APK sul dispositivo Android.
4. Aprire CONFIG e impostare l'indirizzo HTTPS della Dashboard.
5. Configurare gli eventuali parametri MQTT.
6. Accedere alla sezione ADMIN per utilizzare il controllo remoto.

### Compilazione dei sorgenti

1. Aprire Android Studio.
2. Selezionare la cartella `MMDVM-Mobile` contenente `settings.gradle.kts`.
3. Impostare Gradle JDK 17.
4. Eseguire Gradle Sync.
5. Compilare l'applicazione.

### Firma APK

Il keystore privato non è incluso nel repository.

Per creare un APK Release firmato utilizzare **Build → Generate Signed App Bundle / APK** in Android Studio.

Per aggiornare un'app già installata è necessario utilizzare la stessa chiave di firma e incrementare `versionCode`.

---

## 🇬🇧 English

### Main features

- Real-time repeater monitoring dashboard.
- Multiple repeater support and node selection.
- Operating mode and service status display.
- Gateway and connection monitoring.
- HTTPS API and MQTT communication.
- Smartphone-optimized interface.
- Italian and English languages with automatic or manual selection.
- Custom application icon.

### Remote control — ADMIN

Version v0.5.0 introduces remote MMDVM mode control through MMDVM Dashboard MQTT Multi and its Agent.

- Administrator authentication.
- Individual enable/disable control for D-Star, DMR, YSF, FM, P25, NXDN and M17, where supported.
- Enabled/disabled mode status display.
- ON/OFF buttons updated according to mode status.
- Special MMDVMHost commands.
- CW message sending.
- Confirmation before executing commands.
- Command execution verification through the command queue.
- Automatic status refresh after operations.
- Automatic use of the Dashboard HTTPS address configured in Settings.

### ⚠️ Important requirements

**The latest version of MMDVM Dashboard MQTT Multi is required to use all application features.**

Remote control also requires:

- Properly configured remote MQTT Agent.
- Mobile Control functionality enabled.
- Dashboard administrator account.
- Working HTTPS connection.

Older Dashboard versions may support only some monitoring features.

### APK installation

1. Open the repository **Releases** section.
2. Download the latest signed APK.
3. Install the APK on your Android device.
4. Open CONFIG and enter your Dashboard HTTPS address.
5. Configure MQTT settings if required.
6. Open ADMIN to access remote control features.

### Building from source

1. Open Android Studio.
2. Open the `MMDVM-Mobile` directory containing `settings.gradle.kts`.
3. Select Gradle JDK 17.
4. Run Gradle Sync.
5. Build the application.

### APK signing

The private signing keystore is not included in the repository.

To generate a signed Release APK, use **Build → Generate Signed App Bundle / APK** in Android Studio.

Updating an existing installation requires the same signing key and an increased `versionCode`.

---

## Repository Dashboard / Dashboard repository

https://github.com/Mauro-go/MMDVM-Dashboard-MQTT-Multi

## Versione / Version

**v0.5.0 — Android Release**

Controllo remoto MMDVM, monitoraggio MQTT, supporto multiripetitore e interfaccia bilingue.

MMDVM remote control, MQTT monitoring, multi-repeater support and bilingual interface.

---

**Progetto radioamatoriale / Amateur radio project.**
