# GitHub Workflow
Dieses Repository dient als Demonstration für einen grundlegenden GitHub-Workflow.  
Der Workflow ist so konzipiert, dass er bei jedem Push-Ereignis zum Hauptzweig automatisch ausgelöst wird.

# Anleitung
1. Repository-Einrichtung -> Erstellen Sie ein neues GitHub-Repository für Ihre Anwendung.

2. GitHub Actions Workflow-Konfiguration -> Navigieren Sie zur Registerkarte "Actions" in Ihrem GitHub-Repository.
 Klicken Sie auf "Set up a workflow yourself" und fügen Sie einen Workflow YAML hinzu, der automatisch bei jedem Push auf den Hauptzweig ausgelöst wird.
 Fügen Sie den mitgelieferten YAML-Code für den ersten einfachen Workflow ein.

3. Testen Sie den Workflow (Erster Schritt) -> Nehmen Sie eine kleine Änderung am Repository vor (z. B. einen Kommentar hinzufügen).
   Commit und Push der Änderungen. Überprüfen Sie auf der Registerkarte "Actions", ob der Workflow automatisch initiiert wurde und die Ausgabe "Hello, CI Workflow!" angezeigt wird.

4. Fügen Sie einen zusätzlichen Schritt hinzu -> Erweitern Sie den Arbeitsablauf durch einen weiteren Schritt, der eine zusätzliche Begrüßungsnachricht druckt.

5. Testen Sie den Workflow (Zweiter Schritt) -> Nehmen Sie eine weitere kleine Änderung am Repository vor. Commit und Push der Änderungen.
   Überprüfen Sie auf der Registerkarte "Actions", dass der Workflow automatisch gestartet wurde und beide Ausgaben angezeigt werden: "Hello, CI Workflow!" und "Welcome to CI Workflow!"
   Wenn Sie diese Schritte befolgen, wird Ihr Repository mit einem unkomplizierten GitHub-Workflow konfiguriert, der bei jedem Push an den Hauptzweig bestimmte Aktionen ausführt.
