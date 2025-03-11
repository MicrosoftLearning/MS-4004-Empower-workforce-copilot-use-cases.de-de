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
Microsoft 365 Copilot kann Marketingfachleuten auf vielfältige Weise helfen. Sie können z. B. Inhalte für ihre Kampagnen generieren, die Produktivität verbessern, Einblicke in ihre Kampagnen erhalten, effektiver zusammenarbeiten und vieles mehr. Copilot kann Ihnen relevante Hashtags, Bilder und sogar Social-Media-Beiträge vorschlagen. Und wenn Sie einen Blogbeitrag erstellen, kann Copilot Themen vorschlagen, Recherchematerial bereitstellen und Ihnen sogar beim Verfassen des Beitrags helfen.

Copilot kann Marketingexperten auch helfen, Zeit zu sparen, indem sich wiederholende Aufgaben wie das Formatieren, das Hinzufügen von Diagrammen und Graphen und sogar das Korrekturlesen von Dokumenten automatisiert werden. Zudem kann Copilot Analysen darüber bereitstellen, wie Ihre Social-Media-Beiträge abschneiden, welche Beiträge die größte Resonanz finden und zu welcher Tageszeit sie am besten veröffentlicht werden sollten. Copilot kann Sie auch dabei unterstützen, effektiver mit Ihrem Team zusammenzuarbeiten, indem er Ihnen hilft, Aufgaben zuzuweisen, Fristen festzulegen und sogar Erinnerungen bereitzustellen.

Dieses Modul vermittelt Marketingexperten die erforderlichen Fähigkeiten und Kenntnisse, um das KI-gestützte Code-Vervollständigungstool von Copilot zu nutzen, um ihre Arbeitsabläufe zu optimieren und ihre Produktivität zu steigern. Ihre Fähigkeit, nahtlos mit Copilot zu kommunizieren und präzise Antworten zu erlangen, ist von größter Bedeutung für:

 -  **Generieren von Inhalten**: Copilot kann Marketingexperten dabei helfen, Inhalte für ihre Kampagnen zu generieren. Wenn Sie z. B. einen Social-Media-Beitrag erstellen, kann Copilot relevante Hashtags und Bilder vorschlagen und sogar den Beitrag für Sie verfassen. Und wenn Sie einen Blogbeitrag erstellen, kann Copilot Themen vorschlagen, Recherchematerial bereitstellen und Ihnen sogar beim Verfassen des Beitrags helfen.
 -  **Verbessern der Produktivität**: Copilot kann Marketingexperten helfen, Zeit zu sparen, indem sich wiederholende Aufgaben automatisiert werden. Wenn Sie beispielsweise einen Bericht erstellen, kann Copilot Ihnen beim Formatieren, Hinzufügen von Diagrammen und Graphen und sogar beim Korrekturlesen des Dokuments helfen.
 -  **Gewinnen von Erkenntnissen**: Copilot kann Marketingexperten dabei helfen, Erkenntnisse zu ihren Kampagnen zu gewinnen. Bei einer Social-Media-Kampagne kann Copilot beispielsweise Analysen darüber bereitstellen, wie Ihre Beiträge abschneiden, welche Beiträge die größte Resonanz finden und zu welcher Tageszeit sie am besten veröffentlicht werden.
 -  **Zusammenarbeit**: Copilot kann Marketingexperten helfen, effektiver zusammenzuarbeiten. Wenn Sie beispielsweise mit einem Team an einem Projekt arbeiten, kann Copilot Ihnen helfen, Aufgaben zuzuweisen, Fristen festzulegen und sogar Erinnerungen bereitzustellen.
 -  **Integration in Microsoft 365**: Copilot ist in Microsoft 365-Apps wie Teams, Word, Outlook, PowerPoint und Excel integriert. Das bedeutet, dass Marketingexperten Copilot in diesen Apps nutzen können, um Hilfe bei der Arbeit zu erhalten.

Microsoft 365 Copilot fungiert als KI-gestützter Schreibassistent. Er versteht den Kontext, schlägt Formulierungen vor und hilft bei der Erstellung von Inhalten, was die Qualität Ihrer Arbeit verbessern kann. Die Übungen in diesem Anwendungsfallmodul helfen Marketingexperten, die folgenden Fähigkeiten zu erwerben:

 -  Verwendung von Microsoft 365 Business Chat zur Analyse von Markttrends, Bereitstellung von Umsatzprognosen und Identifizierung neuer Umsatzmöglichkeiten.
 -  Verwendung von Microsoft 365 Copilot in Loop, um Ideen für Marketingkampagnen für eine neue Produktlinie zu generieren.
 -  Verwenden von Microsoft 365 Copilot in Word, um drei Produktmarketingberichte in einem einzigen Marktanalysebericht zusammenzufassen.
 -  Verwendung von Microsoft 365 Copilot in Excel zur Analyse von Markttrends in einer Tabelle.
