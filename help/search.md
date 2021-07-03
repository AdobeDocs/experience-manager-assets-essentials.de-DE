---
title: Suchen und Ermitteln von Assets in  [!DNL Assets Essentials]
description: Suchen und Ermitteln von Assets in [!DNL Assets Essentials].
role: User
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 2%

---


# Suchen nach Assets in [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] bietet eine effektive Suche, die standardmäßig funktioniert. Die Suche ist umfassend, da es sich um eine Volltextsuche handelt. Mit der leistungsstarken Suchfunktion können Sie schnell das entsprechende Asset ermitteln und Ihre Content-Geschwindigkeit verbessern. [!DNL Assets Essentials] bietet Volltextsuche und Suchvorgänge durch die Metadaten wie Smart-Tags, Titel, Erstellungsdatum und Copyright.

So suchen Sie nach Assets:

* Klicken Sie oben auf der Seite in das Suchfeld. Standardmäßig wird innerhalb des Ordners gesucht, den Sie gerade durchsuchen. Führen Sie einen der folgenden Schritte aus:

   ![Suchfeld](assets/search-box.png)

   * Suchen Sie mithilfe eines Suchbegriffs und ändern Sie optional den Ordner. Drücken Sie die Eingabetaste.

   * Beginnen Sie mit der Arbeit mit einem kürzlich angezeigten Asset, indem Sie direkt danach suchen. Klicken Sie in das Suchfeld und wählen Sie aus den Vorschlägen ein kürzlich angezeigtes Asset aus.

## Suchergebnisse filtern {#refine-search-results}

Sie können die Suchergebnisse anhand der folgenden Parameter filtern.

![Suchfilter](assets/filters1.png)

*Abbildung: Filtern gesuchter Assets basierend auf verschiedenen Parametern.*

* Dateityp: Filtern Sie die Suchergebnisse nach den unterstützten Dateitypen: `Images`, `Documents` und `Videos`.
* MIME-Typ: Filtern Sie nach einem oder mehreren der unterstützten Dateiformate. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Bildgröße: Geben Sie eine oder mehrere der minimalen und maximalen Abmessungen zum Filtern von Bildern an. Die Größe wird in Pixel angegeben und ist nicht die Dateigröße der Bilder.
* Erstellungsdatum: Das Erstellungsdatum des Assets, wie in den Metadaten angegeben. Das Standarddatumsformat ist `yyyy-mm-dd`.
* Änderungsdatum: Das Datum der letzten Änderung der Assets. Das Standarddatumsformat ist `yyyy-mm-dd`.

Sie können die gesuchten Assets in aufsteigender oder absteigender Reihenfolge von `Name`, `Relevancy`, `Size`, `Modified` und `Created` sortieren.

## Gespeicherte Suchvorgänge {#saved-search}

Die Suchfunktion ist in [!DNL Assets Essentials] recht einfach zu verwenden. Über das Suchfeld können Sie nicht nur einen Suchbegriff eingeben und die Eingabetaste drücken, um die Ergebnisse zu sehen, sondern auch schnell nach Ihren kürzlich gesuchten Suchbegriffen suchen.

Sie können die Suchergebnisse auch nach bestimmten Kriterien nach Metadaten und Asset-Typ filtern. Bei häufig verwendeten Filtern können Sie zur Verbesserung des Sucherlebnisses mit [!DNL Assets Essentials] die Suchparameter speichern. Sie können dann die gespeicherte Suche auswählen, um zu suchen, und den Filter auch mit nur einem Klick anwenden.

Um eine gespeicherte Suche zu erstellen, suchen Sie nach einem Asset, wenden Sie einen oder mehrere Filter an und klicken Sie im Bereich [!UICONTROL Filter] auf [!UICONTROL Suche speichern] .

![Gespeicherte Suche im Bereich &quot;Filter&quot;](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
