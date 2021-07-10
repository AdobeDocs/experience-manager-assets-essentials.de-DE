---
title: Unterstützte Dateiformate
description: Unterstützte Dateiformate für die verschiedenen Anwendungsfälle von [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 33%

---


# Unterstützte Dateiformate in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] unterstützt eine breite Palette von Dateiformaten und jede Funktionalität unterstützt unterschiedliche Dateitypen.

* ![Bilddateityp ](assets/do-not-localize/image-icon.png) iconImages: GIF, JPG, PNG und TIFF
* ![Dokumentdateityp ](assets/do-not-localize/document-icon.png) iconDocuments: DOCX, PDF, PPTX und XLSX
* ![Videodateityp ](assets/do-not-localize/video-icon.png) iconVideos: MP4

Die verschiedenen Dateitypen unterstützen die Anwendungsfälle und Funktionen unterschiedlich, wie unten beschrieben. Die Legende gibt den Grad der Unterstützung an.

| Unterstützungsebene | Beschreibung |
|-------------------|-------------------------|
| ✓ | Unterstützt |
| ‡ | Bedingt unterstützt |
| - | Nicht zutreffend |

## Hinzufügen, Hochladen und Anzeigen von Assets {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Asset-Typ | [Durchsuchen](/help/navigate-view.md) | Kopieren | [Hochladen](/help/add-delete.md) | Erstellen | [Löschen](/help/add-delete.md#delete-assets) | Details | Bild-Zoom | [Kürzlich angesehen](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Rasterbilder | verwalten | verwalten | verwalten | - | verwalten | verwalten | verwalten | verwalten |
| Ordner | verwalten | verwalten | verwalten | verwalten | verwalten | verwalten | - | - |
| MP4-Videos | verwalten | verwalten | verwalten | - | verwalten | ‡ | - | verwalten |
| PDF | verwalten | verwalten | verwalten | - | verwalten | verwalten | - | verwalten |
| PSD, AI und INDD | verwalten | verwalten | verwalten | - | verwalten | ‡ | - | verwalten |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Suchen, Verwenden und Bearbeiten von Assets {#support-to-search-use-edit}

| Asset-Typ | [Download](/help/manage-organize.md#download) | Drag &amp; Drop | [Bildeditor](/help/edit-images.md) | [Suchen](/help/search.md) | [Smart-Tags](/help/metadata.md#tags) | [Umbenennen](/help/manage-organize.md) | [Versionen](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterbilder | verwalten | verwalten | verwalten | verwalten | verwalten | verwalten | verwalten |
| Ordner | verwalten | verwalten | - | verwalten | - | verwalten | - |
| Videos | verwalten | verwalten | - | verwalten | verwalten | verwalten | - |
| CC-Bibliotheken | - | - | - | - | - | verwalten | - |
| PDF | verwalten | verwalten | - | verwalten | verwalten | verwalten | - |
| PSD | verwalten | verwalten | - | verwalten | verwalten | verwalten | - |
| AI | verwalten | verwalten | - | verwalten | verwalten | verwalten | - |
| INDD | verwalten | verwalten | - | verwalten | verwalten | verwalten | - |

## Überprüfen von Assets und Zusammenarbeit {#support-to-review-collaborate}

| Asset-Typ | Anmerken | Kommentar | Erstellen von Aufgaben und Überprüfen |
|---------------|----------|----------|-------------------------|
| Rasterbilder | verwalten | verwalten | verwalten |
| Ordner | - | - | - |
| Videos | - | verwalten | verwalten |
| CC-Bibliotheken | - | - | - |
| PDF | - | verwalten | verwalten |
| PSD | - | verwalten | verwalten |
| KI | - | verwalten | verwalten |
| INDD | - | verwalten | verwalten |

## Sonstige Asset-Management-Aufgaben {#support-to-manage-assets}

| Asset-Typ | [Metadaten](/help/metadata.md) | [Ausgabeformate](/help/add-delete.md#renditions) | [Papierkorb](/help/add-delete.md#delete-assets) | Kopieren | Verschieben |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterbilder | verwalten | verwalten | verwalten | verwalten | verwalten |
| Ordner | verwalten | - | verwalten | verwalten | verwalten |
| Videos | verwalten | - | verwalten | verwalten | verwalten |
| CC-Bibliotheken | verwalten | - | - | - | - |
| PDF | verwalten | - | verwalten | verwalten | verwalten |
| PSD | verwalten | - | verwalten | verwalten | verwalten |
| KI | verwalten | - | verwalten | verwalten | verwalten |
| INDD | verwalten | - | verwalten | verwalten | verwalten |

Benutzer von [!DNL Adobe Asset Link] können die Rasterbilder aus den unterstützten [!DNL Adobe Creative Cloud]-Desktop-Programmen in das [!DNL Assets Essentials]-Repository einchecken.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
