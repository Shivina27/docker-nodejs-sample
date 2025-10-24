

### **Aufgabenstellung:**

 1. ** GitHub-Fork erstellen:**

Clone deinen Fork lokal auf deinen Computer.

**Schritte**

**1.**  Um eine Fork zu ertsellen muss man zuerst auf Github oben rechts auf Fork klicken und das führt zu einem Fenster beidem man ein neuen Fork erstellen kann.

**2.**  Danach öffnet man Git Bash und gibt git clone https://gethub.com/Shivina27/docker-nodejs-sample.git  ein damit man die geforkte Repositorie klonen kann. 

**3.**  Anschlissend gibst du Cd docker-nodejs-sample ein damit du zum Ordner des geklonten Projekts wechseln kannst. 

 2. **. Instalation der notwendige Pakete**
 **Schritte**
 **1**  Gehe auf Open Folder und öffne dann deine docker-nodejs-sample Folder auf Visual Studio Code.

 **2**  Da sind die Pakete
   **"dependencies": {
    "express": "^4.18.2",
    "pg": "^8.11.2",
    "sqlite3": "^5.1.2",
    "uuid": "^9.0.0",
    "wait-port": "^1.0.4"**
  
 3. **Docker-Konfiguration und -Installation**

**Schritte**

**1.**  Lade Docker Desktop und Docker for Visual Studio Code von Moodle herunter 
- Es wird ein Auswahl haben zwischen ARM und Amd im Cmd. Falls du  nicht weisst welche auszuwählen dann gib bei Cmd echo %PROCESSOR_ARCHITECTURE%  ein.

**2.**  Drücke auf die Windowa Tastatur und schreibe Powershell rein .Rechtsclick drauf und öffne es als Administrator und gib diese 2 Befehele rein.  **dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart** und **dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart**.

**3.**  Anschlissend musst du schauen das wsl klappt indem du den Befehl **wsl --set-default-version 2** in Powershell rein schreibst.

4. **Starten der Applikation in einem Docker-Container**

Wechsle im Terminal in den Ordner docker-nodejs-sample und gib den Befehl docker init ein. Beantworte die Fragen im Terminal, um das Projekt für Docker einzurichten.

Danach startest du die Anwendung mit:
docker compose up --build

Öffne im Browser http://localhost:3000
, um die App zu sehen.
Wenn es nicht funktioniert, öffne in Visual Studio Code die Datei Dockerfile und ändere die Node.js-Version von 18.0.0 auf 22.18.0. Speichere die Datei und starte den Befehl erneut.
