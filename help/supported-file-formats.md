---
title: Unterstützte Dateiformate
description: Unterstützte Dateiformate für die verschiedenen Anwendungsfälle von  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 02f28c00b387fbcac4cd917fab7763124fdd5d70
workflow-type: ht
source-wordcount: '355'
ht-degree: 100%

---

# Unterstützte Dateiformate in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] unterstützt eine breite Palette von Dateiformaten, und jede Funktionalität bietet unterschiedliche Unterstützung für verschiedene Dateitypen.

* ![Symbol für Bilddateityp](assets/image-icon.svg) Bilder: JPG, PNG, GIF, TIFF und andere
* ![Symbol für Creative Cloud-Typ](assets/creative-cloud-files.svg) Creative Cloud-Dateien: PSD, AI und INDD
* ![Symbol für Kameratyp](assets/camera-icon.svg) Camera Raw-Dateien: CR2/CR3, NEF, SRW/SRF und andere
* ![document file type icon](assets/document-icon.svg) Dokument-Typen: DOCX, PDF, PPTX und XLSX
* ![video file type icon](assets/video-icon.svg) Video-Typen: MP4

[!DNL Assets Essentials] unterstützt alle binären Dateiformate mit grundlegenden Services wie Speichern, Hochladen, Kopieren, Verschieben, Löschen und Hinzufügen von Metadaten.

[!DNL Assets Essentials] unterstützt auch Camera Raw-Dateien von einer Vielzahl führender Kamerahersteller, darunter Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF) und andere, unterstützt durch Adobe Camera Raw.

Die verschiedenen Dateitypen werden, wie unten beschrieben, in unterschiedlichem Maße von den Anwendungsfällen und Funktionen unterstützt. Die Legende gibt den Grad der Unterstützung an.

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
| RAW Dateien | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4-Videos | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD, AI und INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| Andere Binärdateien | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Suchen, Verwenden und Bearbeiten von Assets {#support-to-search-use-edit}

| Asset-Typ | [Download](/help/manage-organize.md#download) | Drag-and-Drop | [Bildeditor](/help/edit-images.md) | [Suchen](/help/search.md) | [Smart-Tags](/help/metadata.md#tags) | [Umbenennen](/help/manage-organize.md) | [Versionen](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW Dateien | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Videos | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC-Bibliotheken | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD, AI und INDD | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Andere Binärdateien | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## Überprüfen von Assets und Zusammenarbeit {#support-to-review-collaborate}

| Asset-Typ | Anmerken | Kommentar | Erstellen von Aufgaben und Überprüfen |
|---------------|----------|----------|-------------------------|
| Rasterbilder | ✓ | ✓ | ✓ |
| RAW Dateien | ✓ | ✓ | ✓ |
| Ordner | − | − | − |
| Videos | − | ✓ | ✓ |
| CC-Bibliotheken | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD, AI und INDD | − | ✓ | ✓ |
| Andere Binärdateien | − | ✓ | ✓ |

## Sonstige Asset-Management-Aufgaben {#support-to-manage-assets}

| Asset-Typ | [Metadaten](/help/metadata.md) | [Ausgabedarstellungen](/help/add-delete.md#renditions) | [Papierkorb](/help/add-delete.md#delete-assets) | Kopieren | Verschieben |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW Dateien | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | − | ✓ | ✓ | ✓ |
| Videos | ✓ | − | ✓ | ✓ | ✓ |
| CC-Bibliotheken | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| PSD, AI und INDD | ✓ | − | ✓ | ✓ | ✓ |
| Andere Binärdateien | ✓ | − | ✓ | ✓ | ✓ |

Benutzer von [!DNL Adobe Asset Link] können Dateien aus den unterstützten Desktop-Programmen von [!DNL Adobe Creative Cloud] in das [!DNL Assets Essentials]-Repository hochladen und einchecken (eine neue Version hochladen).

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

## Nächste Schritte {#next-steps}

* Geben Sie Produkt-Feedback über die Option [!UICONTROL Feedback] in der Benutzeroberfläche von Assets Essentials

* Geben Sie Feedback zur Dokumentation durch ![Bearbeiten der Seite](assets/do-not-localize/edit-page.png) über die Option [!UICONTROL Diese Seite bearbeiten] oder durch ![Erstellen eines GitHub-Themas](assets/do-not-localize/github-issue.png) über die Option [!UICONTROL Problem protokollieren] in der rechten Seitenleiste

* Kontaktieren Sie die [Kundenunterstützung](https://experienceleague.adobe.com/?support-solution=General&amp;lang=de#support)
