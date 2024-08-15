---
title: Unterstützte Dateiformate
description: Unterstützte Dateiformate für die verschiedenen Anwendungsfälle von  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 243a41aef81cd1fdcbad8f4355fe2d888db394d1
workflow-type: ht
source-wordcount: '527'
ht-degree: 100%

---

# Unterstützte Dateiformate in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] unterstützt eine breite Palette von Dateiformaten, und jede Funktionalität bietet unterschiedliche Unterstützung für verschiedene Dateitypen.

* ![Symbol für Bilddateityp](assets/image-icon.svg) Bilder: JPG, PNG, GIF, TIFF und andere
* ![Symbol für Creative Cloud-Typ](assets/creative-cloud-files.svg) Creative Cloud-Dateien: PSD, PSB, AI und INDD
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

| Asset-Typ | [Durchsuchen](/help/using/navigate-view.md) | Kopieren | [Hochladen](/help/using/add-delete.md) | Erstellen | [Löschen](/help/using/add-delete.md#delete-assets) | Details | Bild-Zoom | [Kürzlich angesehen](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Rasterbilder | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Raw-Dateien | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4-Videos | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD, AI, PSB und INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| Andere Binärdateien | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Suchen, Verwenden und Bearbeiten von Assets {#support-to-search-use-edit}

| Asset-Typ | [Download](/help/using/manage-organize.md#download) | Drag-and-Drop | [Bildeditor](/help/using/edit-images.md) | [Suchen](/help/using/search.md) | [Smart-Tags](/help/using/metadata.md#tags) | [Umbenennen](/help/using/manage-organize.md) | [Versionen](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Raw-Dateien | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Videos | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC-Bibliotheken | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD und PSB | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| AI und INDD | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Andere Binärdateien | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## Überprüfen von Assets und Zusammenarbeit {#support-to-review-collaborate}

| Asset-Typ | Anmerken | Kommentar | Erstellen von Aufgaben und Überprüfen |
|---------------|----------|----------|-------------------------|
| Rasterbilder | ✓ | ✓ | ✓ |
| Raw-Dateien | ✓ | ✓ | ✓ |
| Ordner | − | − | − |
| Videos | − | ✓ | ✓ |
| CC-Bibliotheken | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD, PSB, AI und INDD | − | ✓ | ✓ |
| Andere Binärdateien | − | ✓ | ✓ |
| DOC | − | ✓ | ✓ |
| DOCX | − | ✓ | ✓ |
| PPT | − | ✓ | ✓ |
| PPTX | − | ✓ | ✓ |
| XLS | − | ✓ | ✓ |
| XLSX | − | ✓ | ✓ |
| TXT | − | ✓ | ✓ |
| RTF | − | ✓ | ✓ |

## Sonstige Asset-Management-Aufgaben {#support-to-manage-assets}

| Asset-Typ | [Metadaten](/help/using/metadata.md) | [Ausgabedarstellungen](/help/using/add-delete.md#renditions) | [Papierkorb](/help/using/add-delete.md#delete-assets) | Kopieren | Verschieben |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ |
| Raw-Dateien | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ordner | ✓ | − | ✓ | ✓ | ✓ |
| Videos | ✓ | − | ✓ | ✓ | ✓ |
| CC-Bibliotheken | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| AI und INDD | ✓ | − | ✓ | ✓ | ✓ |
| PSD und PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
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
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## Nächste Schritte {#next-steps}

* Geben Sie Produkt-Feedback über die Option [!UICONTROL Feedback] in der Benutzeroberfläche von Assets Essentials

* Geben Sie Feedback zur Dokumentation durch ![Bearbeiten der Seite](assets/do-not-localize/edit-page.png) über die Option [!UICONTROL Diese Seite bearbeiten] oder durch ![Erstellen eines GitHub-Themas](assets/do-not-localize/github-issue.png) über die Option [!UICONTROL Problem protokollieren] in der rechten Seitenleiste

* Kontaktieren Sie die [Kundenunterstützung](https://experienceleague.adobe.com/de?support-solution=General#support)
