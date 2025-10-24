# **Thema:** Erstellen einer ToDo-Applikation mit Markdown, Git, GitHub und Docker

In dieser Abschlussaufgabe werden alle erlernten Fähigkeiten in den Bereichen **Markdown**, **Git**, **GitHub** und **Docker** kombiniert. Die Aufgabe besteht darin, eine ToDo-Applikation zu erstellen und diese in einem Docker-Container bereitzustellen.

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

 **2**  S
  

 3. **Docker-Konfiguration und -Installation**

**Schritte**

**1.**  Lade Docker Desktop und Docker for Visual Studio Code von Moodle herunter 
- Es wird ein Auswahl haben zwischen ARM und Amd im Cmd. Falls du  nicht weisst welche auszuwählen dann gib bei Cmd echo %PROCESSOR_ARCHITECTURE%  ein.

**2.**  Drücke auf die Windowa Tastatur und schreibe Powershell rein .Rechtsclick drauf und öffne es als Administrator und gib diese 2 Befehele rein.  **dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart** und **dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart**.

**3.**  Anschlissend musst du schauen das wsl klappt indem du den Befehl **wsl --set-default-version 2** in Powershell rein schreibst.

4. **Starten der Applikation in einem Docker-Container**
   - Verfolge die Anleitung unter [docs.docker.com](https://docs.docker.com/guides/language/nodejs/containerize/) ab dem Schritt **"Initialize Docker assets"**.
   - Dein Ziel ist es, das Projekt in einem Docker-Container lauffähig zu machen, sodass am Ende eine **ToDo-Applikation** in einem Docker-Container bereitsteht.

5. **Git-Workflows:**
   - Arbeite mit **Git**, um Änderungen regelmäßig zu committen und auf GitHub zu pushen.
   - Verwende sinnvolle Commit-Nachrichten, um deinen Fortschritt zu dokumentieren.
   - Stelle sicher, dass dein finaler Stand auf GitHub vorhanden ist.

6. **Abgabe:**
   - **Dokumentation:** Lade die erstellte Word-Dokumentation (inkl. Screenshots und Beschreibung der Schritte) in dein Repository hoch.
   - **GitHub-Link:** Stelle den Link zu deinem GitHub-Repository bereit, das den finalen Stand des Projekts enthält.

### **Ziele der Aufgabe:**
- Anwendung und Vertiefung von Git und GitHub.
- Verfassen einer strukturierten Anleitung mit Markdown.
- Containerisieren einer Node.js-Anwendung mit Docker.
- Dokumentation des gesamten Prozesses in einem Word-Dokument.
  
