---
title: Unterstützte Dateiformate
description: Unterstützte Dateiformate für die verschiedenen Anwendungsfälle von  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: ht
source-wordcount: '206'
ht-degree: 100%

---


# Unterstützte Dateiformate in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] unterstützt eine breite Palette von Dateiformaten und jede Funktionalität bietet unterschiedliche Unterstützung für verschiedene Dateitypen.

* ![image file type icon](assets/do-not-localize/image-icon.png) Bild-Typen: GIF, JPG, PNG, und TIFF
* ![document file type icon](assets/do-not-localize/document-icon.png) Dokument-Typen: DOCX, PDF, PPTX und XLSX
* ![video file type icon](assets/do-not-localize/video-icon.png) Video-Typen: MP4

Die verschiedenen Dateitypen haben unterschiedliche Grade der Unterstützung für die unten beschriebenen Anwendungsfälle und Funktionen. Die Legende gibt den Grad der Unterstützung an.

| Unterstützungsebene | Beschreibung |
|-------------------|-------------------------|
| ✓ | Unterstützt |
| ✓ ‡ | Bedingt unterstützt |
| − | Nicht zutreffend |

## Hinzufügen, Hochladen und Anzeigen von Assets {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Asset-Typ | [Durchsuchen](/help/navigate-view.md) | Kopieren | [Hochladen](/help/add-delete.md) | Erstellen | [Löschen](/help/add-delete.md#delete-assets) | Details | Bild-Zoom | [Kürzlich angesehen](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Rasterbilder | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4-Videos | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD, AI und INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Suchen, Verwenden und Bearbeiten von Assets {#support-to-search-use-edit}

| Asset-Typ | [Download](/help/manage-organize.md#download) | Drag-and-Drop | [Bildeditor](/help/edit-images.md) | [Suchen](/help/search.md) | [Smart-Tags](/help/metadata.md#tags) | [Umbenennen](/help/manage-organize.md) | [Versionen](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | − | ✓ | − | ✓ | − |
| Videos | ✓ | ✓ | − | ✓ | ✓ | ✓ | − |
| CC-Bibliotheken | − | − | − | − | − | ✓ | − |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | − |
| PSD | ✓ | ✓ | − | ✓ | ✓ | ✓ | − |
| AI | ✓ | ✓ | − | ✓ | ✓ | ✓ | − |
| INDD | ✓ | ✓ | − | ✓ | ✓ | ✓ | − |

## Überprüfen von Assets und Zusammenarbeit {#support-to-review-collaborate}

| Asset-Typ | Anmerken | Kommentar | Erstellen von Aufgaben und Überprüfen |
|---------------|----------|----------|-------------------------|
| Rasterbilder | ✓ | ✓ | ✓ |
| Ordner | − | − | − |
| Videos | − | ✓ | ✓ |
| CC-Bibliotheken | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD | − | ✓ | ✓ |
| AI | − | ✓ | ✓ |
| INDD | − | ✓ | ✓ |

## Sonstige Asset-Management-Aufgaben {#support-to-manage-assets}

| Asset-Typ | [Metadaten](/help/metadata.md) | [Ausgabedarstellungen](/help/add-delete.md#renditions) | [Papierkorb](/help/add-delete.md#delete-assets) | Kopieren | Verschieben |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | − | ✓ | ✓ | ✓ |
| Videos | ✓ | − | ✓ | ✓ | ✓ |
| CC-Bibliotheken | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| PSD | ✓ | − | ✓ | ✓ | ✓ |
| AI | ✓ | − | ✓ | ✓ | ✓ |
| INDD | ✓ | − | ✓ | ✓ | ✓ |

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
