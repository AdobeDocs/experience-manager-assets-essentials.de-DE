---
title: Verwalten digitaler Assets
description: Verschieben, Löschen, Kopieren, Umbenennen, Aktualisieren und Versionieren von Assets in  [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 95%

---


# Verwalten von Assets {#manage-assets}

Mithilfe der benutzerfreundlichen Oberfläche von [!DNL Assets Essentials] können Sie mühelos verschiedene Aufgaben des Digital Asset Management (DAM) ausführen. Nachdem Sie die Assets hinzugefügt haben, können Sie sie suchen, herunterladen, verschieben, kopieren, umbenennen, löschen, aktualisieren und bearbeiten.

Verwenden Sie [!DNL Assets Essentials], um die folgenden Asset-Management-Aufgaben auszuführen. Wenn Sie ein Asset auswählen, werden die folgenden Optionen in der Symbolleiste oben angezeigt.

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-image-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für ein ausgewähltes Bild.*

* ![deselect icon](assets/do-not-localize/close-icon.png) Deaktivieren der Auswahl.
* ![details icon](assets/do-not-localize/edit-in-icon.png) Anklicken, um ein Asset in der Vorschau anzuzeigen und die detaillierten Metadaten anzuzeigen. Aus der Vorschau heraus können Sie die Versionen anzeigen und ein Bild bearbeiten.
* ![download icon](assets/do-not-localize/download-icon.png) Lädt das ausgewählte Asset in Ihr lokales Dateisystem herunter.
* ![delete icon](assets/do-not-localize/delete-icon.png) Löscht das ausgewählte Asset oder den ausgewählten Ordner.
* ![Checkout-](assets/do-not-localize/checkout-icon.png) SymbolCheckout für das ausgewählte Asset.
* ![copy icon](assets/do-not-localize/copy-icon.png) Kopiert die ausgewählte Datei oder den ausgewählten Ordner.
* ![move icon](assets/do-not-localize/move-icon.png) Verschiebt das ausgewählte Asset oder den ausgewählten Ordner an einen anderen Speicherort in der Repository-Hierarchie.
* ![rename icon](assets/do-not-localize/rename-icon.png) Benennt das ausgewählte Asset oder den ausgewählten Ordner um. Verwenden Sie einen eindeutigen Namen, sonst schlägt die Umbenennung mit einer Warnung fehl. Sie können es mit einem anderen Namen erneut versuchen.
* ![Aufgabensymbol zuweisen ](assets/do-not-localize/review-delegate-icon.png) Weisen Sie anderen Benutzern Aufgaben zu, um an einem Asset zusammenzuarbeiten.

Sie können die gleichen Optionen bei den Miniaturansichten der Assets anzeigen.

![Optionen für die Asset-Miniaturansicht zum Verwalten eines Assets](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] zeigt nur die relevanten Optionen in der Symbolleiste an, die vom Typ des ausgewählten Assets abhängen.

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-folder-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für einen ausgewählten Ordner.*

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-pdf-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für eine ausgewählte PDF-Datei.*

## Herunterladen und Verteilen von Assets {#download}

Sie können ein oder mehrere Assets oder Ordner oder eine Kombination aus beiden auswählen und die Auswahl in Ihr lokales Dateisystem herunterladen. Sie können die Assets bearbeiten und erneut hochladen oder die Assets außerhalb von [!DNL Assets Essentials] verteilen. Außerdem können Sie [die Ausgabeformate](/help/add-delete.md#renditions) eines Assets herunterladen.

## Asset-Versionierung {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] versioniert die Assets, wenn die Assets, die aktualisiert oder bearbeitet werden, erneut hochgeladen werden. Sie können den Versionsverlauf und frühere Versionen anzeigen und eine frühere Version von Assets als neueste Version wiederherstellen, die bei Bedarf auf eine frühere Version zurückgesetzt wird. Asset-Versionen werden in den folgenden Szenarien erstellt:

* Ein neues Asset wird mit demselben Dateinamen wie ein vorhandenes Asset und in denselben Ordner wie das vorhandene Asset hochgeladen. [!DNL Assets Essentials] fordert dazu auf, entweder das vorherige Asset zu überschreiben oder das neue Asset als Version zu speichern. Siehe [Hochladen von Asset-Duplikaten](/help/add-delete.md#resolve-upload-fails).

   ![Erstellen von Versionen beim Hochladen](assets/uploads-manage-duplicates.png)

   *Abbildung: Beim Hochladen eines Assets mit dem Namen eines vorhandenen Assets können Sie eine Version des Assets erstellen.*

* Bearbeiten Sie ein Bild und klicken Sie auf **[!UICONTROL Als Version speichern]**. Siehe [Bearbeiten von Bildern](/help/edit-images.md).

   ![Bearbeitetes Bild als Version speichern](assets/edit-image2.png)

   *Abbildung: Speichern Sie das bearbeitete Bild als Version.*

* Öffnen Sie die Versionen eines vorhandenen Assets. Klicken Sie auf **[!UICONTROL Neue Version]** und laden Sie eine neuere Version des Assets in das Repository hoch.

   ![Option zum Hochladen einer neuen Version eines Assets aus dem Versionsverlauf](assets/view-asset-versions2.png)

### Anzeigen von Versionen eines Assets {#view-versions}

Beim Hochladen eines Duplikats oder einer geänderten Kopie eines Assets können Sie dessen Versionen erstellen. Mit der Versionierung können Sie historische Assets überprüfen und bei Bedarf zu einer früheren Version zurückkehren.

Um Versionen anzuzeigen, öffnen Sie die Vorschau eines Assets und klicken Sie in der rechten Seitenleiste auf **[!UICONTROL Versionen]** ![Versions icon](assets/do-not-localize/versions-clock-icon.png). Um eine bestimmte Version in der Vorschau anzuzeigen, wählen Sie sie aus. Um zu ihr zurückzukehren, klicken Sie auf **[!UICONTROL Neueste erstellen]**.

Sie können Versionen auch aus der Versions-Zeitleiste erstellen. Wählen Sie die neueste Version aus, klicken Sie auf **[!UICONTROL Neue Version]** und laden Sie eine neue Kopie des Assets aus Ihrem lokalen Dateisystem hoch.

![Anzeigen von Versionen eines Assets](assets/view-asset-versions1.png)

*Abbildung: Zeigen Sie Versionen eines Assets an, kehren Sie zu einer früheren Version zurück oder laden Sie eine andere neue Version hoch.*
