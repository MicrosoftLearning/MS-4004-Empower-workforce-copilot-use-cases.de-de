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
Einführung
---
Microsoft 365 Copilot ermöglicht es IT-Fachleuten, ihre Effizienz zu verbessern, komplexe Aufgaben zu vereinfachen und technische Workflows zu optimieren. Mit Copilot können IT-Experten den IT-Betrieb nahtlos verwalten, technische Probleme beheben, Systemsicherheit gewährleisten und datengesteuerte Erkenntnisse für die strategische Entscheidungsfindung nutzen.

Microsoft 365 Copilot ist ein wertvolles Tool für IT-Fachleute, mit dem sie komplexes Technologiemanagement einfacher bewältigen können. Mit Copilot können sie technische Probleme umgehend identifizieren und beheben, um die Systemleistung zu optimieren. Copilot wird damit zu einem unverzichtbaren Hilfsmittel im Toolkit der IT-Experten. Mit Copilot können IT-Experten Zeit sparen und sich auf kritische Aspekte ihrer Aufgaben konzentrieren, z. B. auf die Verbesserung der Systemzuverlässigkeit, die Implementierung innovativer Lösungen und die proaktive Bewältigung von IT-Herausforderungen.

Dieses Modul vermittelt IT-Experten die erforderlichen Fähigkeiten und Kenntnisse, um das KI-gestützte Code-Vervollständigungstool von Copilot einzusetzen, um ihre Arbeitsabläufe zu optimieren und ihre Produktivität zu steigern. Als IT-Experte ist Ihre Fähigkeit, Microsoft 365 Copilot effektiv zu nutzen, entscheidend für:

 -  **Automatisierung.** Copilot kann IT-Experten dabei helfen, sich wiederholende Aufgaben zu automatisieren. Beispielsweise kann er bei der Patchverwaltung, der Softwarebereitstellung und sogar bei der Netzwerküberwachung helfen.
 -  **Sicherheit:** Copilot kann IT-Experten dabei helfen, die Sicherheit ihrer Systeme zu gewährleisten. Er kann z. B. bei der Erkennung von Bedrohungen, beim Management des Sicherheitsrisikos und sogar bei der Reaktion auf Vorfälle helfen.
 -  **Problembehandlung** Copilot kann IT-Experten dabei helfen, Probleme effizienter zu beheben. Er kann beispielsweise bei der Ursachen- und Protokollanalyse helfen und sogar Lösungen für häufige Probleme vorschlagen.
 -  **Zusammenarbeit**: Copilot kann IT-Experten helfen, effektiver zusammenzuarbeiten. Beispielsweise kann er bei der Projektverwaltung, der Teamkommunikation und sogar bei der Dokumentfreigabe helfen.
 -  **Integration in Microsoft 365**. Copilot ist in Microsoft 365-Apps wie Teams, Word, Outlook, PowerPoint und Excel integriert. Das bedeutet, dass IT-Experten Copilot in diesen Apps nutzen können, um Hilfe bei der Arbeit zu erhalten.

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Er versteht den Kontext, schlägt Formulierungen vor und hilft bei der Erstellung von Inhalten, was die Qualität Ihrer Arbeit verbessern kann. Die Übungen in diesem Anwendungsfallmodul helfen IT-Experten, die folgenden Fähigkeiten zu erwerben:

 -  Verwendung von Microsoft 365 Business Chat, um die Informationen in einer Produktspezifikation zusammenzufassen und einen Projektplan zur Implementierung des Produkts zu erstellen.
 -  Verwendung von Microsoft 365 Copilot in PowerPoint, um eine Präsentation basierend auf Ihrem erstellten Projektplan zu erstellen.
 -  Verwenden von Microsoft 365 Copilot in Word zum Ändern eines technischen Spezifikationsberichts.
 -  Verwendung von Microsoft 365 Copilot in Outlook, um eine E-Mail mit den wichtigsten Highlights aus dem Bericht zur technischen Spezifikation zu verfassen.
