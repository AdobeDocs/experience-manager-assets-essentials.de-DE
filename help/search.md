---
title: Suchen und Auffinden von Assets in  [!DNL Assets Essentials]
description: Suchen und Auffinden von Assets in  [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: 0420b0836affe453cced6789ea4a7c56660e9f0a
workflow-type: tm+mt
source-wordcount: '686'
ht-degree: 57%

---

# Suchen nach Assets in [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] bietet eine effektive Suche, die einfach standardmäßig funktioniert. Die Suche ist umfassend, da es sich um eine Volltextsuche handelt. Mit der leistungsstarken Suchfunktion können Sie schnell das passende Asset ermitteln und die Geschwindigkeit Ihrer Inhaltserstellung steigern. [!DNL Assets Essentials] bietet Volltextsuche und Suchvorgänge durch die Metadaten wie Smart-Tags, Titel, Erstellungsdatum und Copyright.

Um nach Assets zu suchen,

* klicken Sie oben auf der Seite in das Suchfeld. Standardmäßig wird innerhalb des Ordners gesucht, den Sie gerade durchsuchen. Führen Sie einen der folgenden Schritte aus:

   ![Suchfeld](assets/search-box.png)

   * Suchen Sie mithilfe eines Keywords und ändern Sie optional den Ordner. Drücken Sie die Eingabetaste.

   * Beginnen Sie die Arbeit mit einem kürzlich angezeigten Asset, indem Sie direkt danach suchen. Klicken Sie in das Suchfeld und wählen Sie aus den Vorschlägen ein kürzlich angezeigtes Asset aus.

## Filtern von Suchergebnissen {#refine-search-results}

Sie können die Suchergebnisse anhand der folgenden Parameter filtern.

![Suchfilter](assets/filters1.png)

*Abbildung: Filtern gesuchter Assets basierend auf verschiedenen Parametern.*

* Asset-Status: Filtern Sie die Suchergebnisse mithilfe einer `Approved` oder `Rejected` Asset-Status.

* Asset-Typ: Filtern von Suchergebnissen nach den unterstützten Dateitypen: `Images`, `Documents` und `Videos`.
* MIME-Typ: Filtern nach einem oder mehreren der unterstützten Dateiformate. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Bildgrösse: Geben Sie eine oder mehrere der minimalen und maximalen Abmessungen zum Filtern von Bildern an. Die Größe wird in Pixeln angegeben und ist nicht die Dateigröße der Bilder.
* Erstellungsdatum: Das Erstellungsdatum des Assets, wie in den Metadaten angegeben. Das verwendete Standarddatumsformat ist `yyyy-mm-dd`.
* Änderungsdatum: Das Datum der letzten Änderung der Assets. Das verwendete Standarddatumsformat ist `yyyy-mm-dd`.

Sie können die gesuchten Assets in aufsteigender oder absteigender Reihenfolge von `Name`, `Relevancy`, `Size`, `Modified` und `Created` sortieren.

## Benutzerdefinierte Filter verwalten {#custom-filters}

**Erforderliche Berechtigungen:**  `Can Edit`, `Owner`oder Administrator.

Mit Assets Essentials können Sie auch benutzerdefinierte Filter zur Benutzeroberfläche hinzufügen. Sie können diese benutzerdefinierten Filter dann zusätzlich zum [Standardfilter](#refine-search-results) , um die Suchergebnisse zu verfeinern.

Assets Essentials bietet die folgenden benutzerdefinierten Filter:

<table>
    <tbody>
     <tr>
      <th><strong>Benutzerspezifischer Filtername</strong></th>
      <th><strong>Beschreibung</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>Filtern von Assets mit dem Asset-Titel. Der Titel, den Sie in den Suchkriterien angeben, bei denen zwischen Groß- und Kleinschreibung unterschieden werden soll, muss mit dem genauen Titel des Assets übereinstimmen, das in den Ergebnissen angezeigt werden soll.</td>
     </tr>
     <tr>
      <td>Name</td>
      <td>Filtern von Assets mit dem Asset-Dateinamen. Der Name, den Sie in den Suchkriterien angeben, bei denen die Groß-/Kleinschreibung beachtet wird, muss mit dem exakten Dateinamen des Assets übereinstimmen, der in den Ergebnissen angezeigt werden soll.</td>
     </tr>
     <tr>
      <td>Asset-Größe</td>
      <td>Filtern Sie Assets, indem Sie einen Größenbereich in Byte in den Suchkriterien für ein Asset definieren, das in den Ergebnissen angezeigt werden soll.</td>
     </tr>
     <tr>
      <td>Prognostizierte Tags</td>
      <td>Filtern von Assets mit dem Asset-Smart-Tag . Der Smart-Tag-Name, den Sie in den Suchkriterien angeben, bei denen die Groß-/Kleinschreibung beachtet wird, muss mit dem genauen Smart-Tag-Namen des Assets übereinstimmen, das in den Ergebnissen angezeigt werden soll. Sie können nicht mehrere Smart-Tags in Suchkriterien angeben.</td>
     </tr>    
    </tbody>
   </table>

### Hinzufügen benutzerdefinierter Filter {#add-custom-filters}

So fügen Sie benutzerdefinierte Filter hinzu:

1. Klicken **[!UICONTROL Filter]**.

1. Im **[!UICONTROL Benutzerdefinierte Filter]** Abschnitt, klicken Sie auf **[!UICONTROL Bearbeiten]** oder **[!UICONTROL Filter hinzufügen]**.

   ![Hinzufügen benutzerdefinierter Filter](assets/add-custom-filters.png)

1. Im **[!UICONTROL Verwaltung benutzerdefinierter Filter]** wählen Sie die Filter aus, die Sie der vorhandenen Filterliste hinzufügen möchten. Auswählen **[!UICONTROL Benutzerdefinierte Filter]** , um alle Filter auszuwählen.

1. Klicken **[!UICONTROL Bestätigen]** , um die Filter zur Benutzeroberfläche hinzuzufügen.

### Benutzerdefinierte Filter entfernen {#remove-custom-filters}

So entfernen Sie benutzerdefinierte Filter:

1. Klicken **[!UICONTROL Filter]**.

1. Im **[!UICONTROL Benutzerdefinierte Filter]** Abschnitt, klicken Sie auf **[!UICONTROL Bearbeiten]**.

1. Im **[!UICONTROL Verwaltung benutzerdefinierter Filter]** deaktivieren Sie die Auswahl der Filter, die Sie aus der Liste der vorhandenen Filter entfernen müssen.

1. Klicken **[!UICONTROL Bestätigen]** , um die Filter aus der Benutzeroberfläche zu entfernen.


## Gespeicherte Suchvorgänge {#saved-search}

In [!DNL Assets Essentials] ist die Suchfunktion recht einfach zu verwenden. Über das Suchfeld können Sie nicht nur ein Keyword eingeben und die Eingabetaste drücken, um die Ergebnisse zu sehen, sondern auch schnell mit einem einzigen Klick erneut nach Ihren kürzlich gesuchten Keywords suchen.

Sie können die Suchergebnisse auch nach bestimmten Kriterien rund um Metadaten und Art der Assets filtern. Mit [!DNL Assets Essentials] können Sie bei häufig verwendeten Filtern die Suchparameter speichern, um das Sucherlebnis zu verbessern. Um zu suchen und den Filter mit nur einem Klick anzuwenden, können Sie auch die gespeicherte Suche auswählen.

Um eine gespeicherte Suche zu erstellen, suchen Sie nach einem Asset, wenden Sie einen oder mehrere Filter an und klicken Sie im Bereich [!UICONTROL Filter] auf [!UICONTROL Suche speichern].

![Gespeicherte Suche im Bereich „Filter“](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
