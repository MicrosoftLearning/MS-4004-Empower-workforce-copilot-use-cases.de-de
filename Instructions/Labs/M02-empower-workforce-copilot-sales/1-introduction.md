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
Für Vertriebsexperten ist effektive Kommunikation der Grundstein des Erfolgs. In diesem Modul erfahren Sie, was Microsoft 365 Copilot alles kann und wie Vertriebsfachleute durch strategische Anwendung von Prompts noch besser werden können.

Für Vertriebsexperten ist es nicht nur vorteilhaft, an der effizienten Nutzung von Copilot zu arbeiten. Es trägt auch erheblich zur Maximierung ihrer Produktivität bei. Diese Kompetenz stellt einen strategischen Vorteil in verschiedenen Vertriebsszenarien mit Microsoft 365-Anwendungen dar – ganz gleich, ob Sie überzeugende E-Mails für die Öffentlichkeitsarbeit in Outlook verfassen, Kundeninteraktionen in Excel verwalten, wirkungsvolle Vertriebspräsentationen in PowerPoint erstellen oder nahtlos in Teams zusammenarbeiten möchten.<br>

In diesem Modul für Vertriebsexperten werden differenzierte Techniken vermittelt, die dabei helfen, im Vertrieb noch erfolgreicher zu sein. Für Vertriebsfachleute ist eine effektive Nutzung von Microsoft 365 Copilot in folgenden Bereichen essenziell:

 -  **Automatisieren der Dateneingabe:** Copilot kann Vertriebsexperten dabei helfen, repetitive Aufgaben wie die Dateneingabe zu automatisieren. So kann Copilot Ihnen beispielsweise dabei helfen, Daten in einem beliebigen CRM-System (Customer Relationship Management; Kundenbeziehungsmanagement) zu erfassen, auf sie zuzugreifen und sie zu registrieren.<br>
 -  **Gewinnen von Erkenntnissen:** Copilot kann Vertriebsexperten bei der Leadgenerierung sowie bei der Gewinnung von Erkenntnissen aus ihren Vertriebsdaten helfen. Die Lösung kann Ihnen beispielsweise dabei helfen, Verkaufstrends zu analysieren, Verkaufschancen zu identifizieren und sogar zukünftige Ergebnisse vorherzusagen.<br>
 -  **Verbessern der Produktivität:** Copilot kann manuelle Aufgaben von Vertriebsexperten automatisieren und sich um die Pipelineverwaltung kümmern, um Zeit zu sparen. So kann Copilot Sie beispielsweise bei der Zeitplanung, bei Follow-Ups und sogar beim Korrekturlesen unterstützen.<br>
 -  **Zusammenarbeit**: Copilot kann Vertriebsexperten dabei helfen, effektiver zusammenzuarbeiten. Beispielsweise kann Copilot Sie bei der Teamkommunikation und bei der Dokumentfreigabe unterstützen und sogar Erinnerungen bereitstellen.

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Die Lösung versteht den Kontext, schlägt Formulierungen vor und hilft bei der Erstellung von Inhalten, was die Qualität Ihrer Arbeit verbessern kann. Die Übungen in diesem Anwendungsfallmodul helfen Vertriebsexperten beim Aufbau folgender Fähigkeiten:<br>

 -  Verwenden von Microsoft 365 Copilot in Loop zur Erstellung eines Marktforschungsberichts.
 -  Verwenden von Microsoft 365 Copilot in PowerPoint, um eine Verkaufspräsentation zu erstellen und anzupassen.
 -  Verwenden von Microsoft 365 Copilot, um Ihre E-Mails, Besprechungen und Chats der letzten 30 Tage für ein bestimmtes Projekt zusammenzufassen und anschließend eine Liste mit Aktionselementen sowie Aktionselemente mit einer bestimmten Person oder einem bestimmten Thema zu generieren.
 -  Verwenden von Microsoft 365 Copilot in Word, um drei Lieferantenvereinbarungen miteinander zu vergleichen, die Unterschiede zu identifizieren und empfohlene Aktionen bereitzustellen.
