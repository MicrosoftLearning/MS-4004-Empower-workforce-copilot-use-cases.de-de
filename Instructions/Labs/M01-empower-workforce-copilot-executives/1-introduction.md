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
Für Führungskräfte in einem dynamischen Geschäftsumfeld ist effektive Kommunikation unverzichtbar. In diesem Anwendungsfallmodul erfahren Sie, wie Führungskräfte die Effektivität von Microsoft 365 Copilot maximieren können, indem sie ihre Fähigkeit verbessern, nahtlos Prompts zu erstellen, Nachforschungen anzustellen und Ideen zu formulieren.<br>

Für Personen in Führungspositionen ist es wichtig, Copilot effektiv zu nutzen, um das volle Potenzial von Copilot auszuschöpfen. Diese Fähigkeit kann in verschiedenen Aufgaben von Führungskräften in allen Microsoft 365-Apps genutzt werden – von der Erstellung von Berichten in Microsoft Word über die zur Analyse von Daten in Excel bis hin zur Erstellung von Präsentationen in PowerPoint und darüber hinaus.<br>

Dieses Modul unterstützt Sie bei der Entwicklung der differenzierten Prompterstellungstechniken, die für eine effiziente Nutzung von Copilot benötigt werden. Dadurch können Sie Zeit sparen und Ihre täglichen Aufgaben produktiver erledigen. Für Führungskräfte ist eine effektive Nutzung von Microsoft 365 Copilot in folgenden Bereichen essenziell:

 -  **Produktivität:** Copilot kann repetitive Aufgaben automatisieren und so Führungskräften dabei helfen, Zeit zu sparen. So kann Copilot Sie beispielsweise bei der Zeitplanung, bei der E-Mail-Verwaltung und sogar beim Korrekturlesen unterstützen.<br>
 -  **Erkenntnisse**. Copilot kann Führungskräften dabei helfen, Einblicke in ihr Geschäft zu gewinnen. Beispielsweise kann Copilot Ihnen dabei helfen, Finanzdaten zu analysieren, Trends zu identifizieren und sogar zukünftige Ergebnisse vorherzusagen.<br>
 -  **Zusammenarbeit**: Copilot kann Führungskräften dabei helfen, effektiver zusammenzuarbeiten. Beispielsweise kann Copilot Sie bei der Projektverwaltung, bei der Teamkommunikation und sogar bei der Dokumentfreigabe unterstützen.<br>
 -  **Anpassung**. Copilot kann an die individuellen Bedürfnisse von Führungskräften angepasst werden. So kann die Lösung Ihnen beispielsweise bei der strategischen Planung, beim Risikomanagement und sogar beim Krisenmanagement helfen.<br>
 -  **Integration in Microsoft 365:** Copilot ist in Microsoft 365-Apps wie Teams, Word, Outlook, PowerPoint und Excel integriert. Das bedeutet, dass Führungskräfte Copilot in diesen Apps nutzen können, um Hilfe bei der Arbeit zu erhalten.<br>

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Die Lösung versteht den Kontext, schlägt Formulierungen vor und hilft bei der Erstellung von Inhalten, was jeweils zur Verbesserung Ihrer Produktivität beitragen kann. Die Übungen in diesem Anwendungsfallmodul helfen Führungskräften beim Aufbau folgender Fähigkeiten:<br>

 -  Verwendung von Microsoft 365 Business Chat in Teams, um Ihre Kommunikationserkenntnisse zu einem bestimmten Thema zusammenzufassen.
 -  Verwendung von Microsoft 365 Copilot in Word, um eine Rede zu erstellen, die Sie vor Aktionären des Unternehmens halten möchten.<br>
 -  Verwendung von Microsoft 365 Copilot in PowerPoint, um eine PowerPoint-Präsentation zu erstellen, die auf der von Ihnen erstellten Rede basiert.
 -  Verwendung von Microsoft 365 Copilot in Teams, um eine Besprechung zusammenzufassen, an der Sie teilgenommen haben, und um die wichtigsten Punkte auflisten