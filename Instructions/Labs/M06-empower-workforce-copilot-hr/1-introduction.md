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
Ziel dieses Moduls ist es, Personalfachkräften die Fähigkeiten und Kenntnisse zu vermitteln, die sie benötigen, um das KI-gestützte Code-Vervollständigungstool von Copilot anzuwenden, um ihre Arbeitsabläufe zu optimieren und ihre Produktivität zu steigern. Für Personalverantwortliche ist die Fähigkeit, Microsoft 365 Copilot effektiv zu nutzen, entscheidend:

 -  **Rekrutierung**. Copilot kann Personalverantwortlichen helfen, den Einstellungsprozess zu optimieren. Es kann Ihnen zum Beispiel helfen, Stellenbeschreibungen zu erstellen, Lebensläufe zu prüfen und sogar Vorstellungsgespräche zu planen.
 -  **Onboarding.** Copilot kann Personalverantwortlichen bei der Aufnahme neuer Mitarbeitenden helfen. Es kann Ihnen beispielsweise dabei helfen, Onboarding-Pläne zu erstellen, Schulungsmaterial bereitzustellen und sogar häufige Fragen zu beantworten.
 -  **Leistungsverwaltung**. Copilot kann Personalverantwortlichen bei der Verwaltung der Mitarbeiterleistung helfen. Es kann Ihnen zum Beispiel dabei helfen, Ziele zu setzen, Fortschritte zu verfolgen und Feedback zu geben.
 -  **Mitarbeiterbindung**. Copilot kann Personalverantwortlichen helfen, die Mitarbeiterbindung zu verbessern. Es kann Ihnen zum Beispiel dabei helfen, Umfragen zu erstellen, die Ergebnisse zu analysieren und sogar Vorschläge zur Verbesserung der Einbindung zu machen.
 -  **Compliance**: Copilot kann Personalverantwortlichen helfen, die Einhaltung von Vorschriften zu gewährleisten. Es kann Ihnen beispielsweise dabei helfen, Richtlinien zu erstellen, die Einhaltung von Vorschriften zu verfolgen und sogar Schulungsmaterial bereitzustellen.

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Es versteht den Kontext, schlägt Phrasen vor und hilft bei der Erstellung von Inhalten, was alles die Qualität Ihrer Arbeit verbessern kann. Die Übungen in diesem Anwendungsfall-Modul sollen Personalverantwortlichen helfen, die folgenden Fähigkeiten zu erwerben:

 -  Verwenden von Microsoft 365 Copilot in Word zum Erstellen einer Stellenbeschreibung für eine neue Position.
 -  Verwenden von Microsoft 365 Copilot in Word, um mehrere Lebensläufe zu analysieren und einen Bericht zu erstellen, der die Stärken und Schwächen der einzelnen Kandidatinnen und Kandidaten vergleicht, eine Rangfolge der Kandidatinnen und Kandidaten von der höchsten bis zur niedrigsten Qualifikation erstellt und eine Empfehlung abgibt.
 -  Verwenden von Microsoft 365 Copilot in Loop, um eine Reihe von Interviewfragen für die Befragung von Kandidatinnen und Kandidaten für diese Rolle zu erstellen.
 -  Verwenden von Microsoft 365 Copilot in Outlook, um ein E-Mail-Angebotsschreiben an den ausgewählten Kandidatinnen und Kandidaten für diese Stelle zu erstellen.
