# Lab-Einrichtung:

In diesem Modul erstellen wir Prompts für Microsoft 365 Copilot, die auf Dateien verweisen. Zunächst laden wir alle erforderlichen Dateien auf OneDrive hoch, um sicherzustellen, dass sie im gesamten Lab zugänglich sind.


### Hochladen von Dateien in OneDrive

Führen Sie die folgenden Schritte aus, um alle erforderlichen Dateien auf **OneDrive** hochzuladen:

1. Melden Sie sich mit dem Kennwort `Pa55w.rd` beim virtuellen Computer an, der von Ihrem Mandanten-Anbieter bereitgestellt wird, und zwar als lokales **Administrator**-Konto.
2. Wählen Sie in der Windows-Taskleiste **Microsoft Edge** aus.
3. Geben Sie in der Adressleiste `https://www.office.com` ein.
4. Wählen Sie unter **Willkommen bei Microsoft 365** die Option **Anmelden** aus.
5. Geben Sie beim **Sign-in Prompt** `userx@yourtenant.onmicrosoft.com` ein (Benutzername und Mandant von Ihrem Mandanten bereitgestellt) und wählen Sie **Weiter**.
6. Geben Sie auf dem Bildschirm **Kennwort eingeben** das Kennwort (vom Mandanten-Anbieter) für das Benutzerkonto ein und wählen Sie dann **Anmelden** aus.
7. Wenn Sie aufgefordert werden, **Angemeldet zu bleiben**, wählen Sie **Dies nicht mehr anzeigen** und dann **Ja**.
8. In **Microsoft 365** wählen Sie **Apps**.
9. Wählen Sie unter **Apps** **OneDrive** aus.
10. Wählen Sie in **OneDrive** in der oberen linken Ecke **+** (neu hinzufügen) > **Datei hochladen**.
11. Wählen Sie im **Datei-Explorer** **Dieser PC** > **Lokaler Datenträger (C:)** und öffnen Sie den Ordner **ResourceFiles**.
12. Markieren Sie alle Dateien im Ordner **ResourceFiles** und wählen Sie dann **Öffnen**, um sie auf **OneDrive** hochzuladen.
13. Wenn der Upload abgeschlossen ist, sollten Sie unten in der Mitte des Bildschirms **29 Elemente in Meine Dateien hochgeladen** sehen.
14. Lassen Sie **Edge** geöffnet und gehen Sie zur nächsten Aufgabe über.

### Verweisen auf Dateien in Copilot

Wenn Sie Copilot verwenden, stellen Sie möglicherweise fest, dass einige Dateien in den Vorschlägen nicht sofort verfügbar sind. Dies liegt daran, dass bestimmte Copilot-Erfahrungen nur auf Dateien aus der **Zuletzt verwendet (MRU)**-Liste verweisen, während Sie bei anderen **OneDrive** direkt durchsuchen können. Um sicherzustellen, dass eine Datei in der **MRU**-Liste angezeigt wird, öffnen Sie sie einfach in der entsprechenden Microsoft 365-App, und sie wird automatisch hinzugefügt.

> [!IMPORTANT]
> Microsoft 365 Copilot kann nur mit Dateien arbeiten, die auf **OneDrive** gespeichert sind. Dateien, die lokal auf Ihrem PC gespeichert sind, müssen auf **OneDrive** für Copilot verschoben werden, um darauf zuzugreifen.

Im Laufe des Moduls haben Sie die Möglichkeit, verschiedene Prompts für diese Dateien auszuprobieren. Sie können mit verschiedenen Ansätzen experimentieren, um Ihre Fähigkeiten mit Copilot zu verbessern.

# Einführung
---
Dieses Modul vermittelt Betriebsleitern die Fertigkeiten und das Wissen, um das KI-gestützte Codevervollständigungstool von Copilot zu verwenden, um ihre Workflows zu optimieren und ihre Produktivität zu steigern. Als Betriebsleitung ist Ihre Fähigkeit, Microsoft 365 Copilot effektiv zu nutzen, entscheidend für:<br>

 -  **Projektverwaltung**. Copilot kann Betriebsleitern dabei helfen, Projekte effizienter zu verwalten. Er kann ihnen zum Beispiel bei der Aufgabenzuweisung und Terminplanung helfen und sogar Einblicke in die Projektleistung geben.
 -  **Prozessautomatisierung**. Copilot kann Betriebsleiter dabei unterstützen, sich wiederholende Aufgaben zu automatisieren. Er kann ihnen zum Beispiel bei der Dateneingabe, der Berichterstellung und sogar beim Korrekturlesen helfen.
 -  **Zusammenarbeit**: Copilot kann Betriebsleitern dabei helfen, effektiver zusammenzuarbeiten. Er kann ihnen zum Beispiel bei der Teamkommunikation und der Dokumentfreigabe helfen und sogar Erinnerung bereitstellen.
 -  **Anpassung**. Copilot kann angepasst werden, um die einzigartigen Anforderungen von Betriebsleitern zu erfüllen. Er kann ihnen zum Beispiel bei der Bestandsverwaltung, der Lieferkettenoptimierung und sogar bei der Qualitätskontrolle helfen.

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Er versteht Kontext, schlägt Formulierungen vor und hilft bei der Erstellung von Inhalten, was alles die Qualität Ihrer Arbeit verbessern kann. Die Übungen in diesem Anwendungsfallmodul helfen Betriebsleitern, die folgenden Fertigkeiten zu erwerben:

 -  Verwenden von Microsoft 365 Copilot in Whiteboard zum Brainstorming von Ideen für einen Projektplan zur Installation eines neuen Kesselsystems.
 -  Verwendung von Microsoft 365 Copilot in Outlook, um einen aktuellen E-Mail-Verlauf zusammenzufassen und eine Antwort zu erstellen.
 -  Verwendung von Microsoft 365 Copilot in Word, um einen Bericht zu erstellen, der Kessel- und Ofenheizungssysteme analysiert und vergleicht und gleichzeitig die von Copilot erzeugten Arten von Ausgaben vergleicht.
 -  Verwendung von Microsoft 365 Copilot in PowerPoint, um eine Präsentation basierend auf dem von Ihnen erstellten Bericht zu erstellen, der Kessel- und Ofenheizungssysteme analysiert.
