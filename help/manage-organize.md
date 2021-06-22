---
title: Verwalten digitaler Assets
description: Verschieben, Löschen, Kopieren, Umbenennen, Aktualisieren und Versions Ihrer Assets in [!DNL Assets Essentials].
role: Business Practitioner,Leader
contentOwner: AG
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 0%

---


# Verwalten von Assets {#manage-assets}

Mithilfe der benutzerfreundlichen Oberfläche von [!DNL Assets Essentials] können Sie mühelos verschiedene Aufgaben des Digital Asset Management (DAM) ausführen. Nachdem Sie die Assets hinzugefügt haben, können Sie Assets suchen, herunterladen, verschieben, kopieren, umbenennen, löschen, aktualisieren und bearbeiten.

Verwenden Sie [!DNL Assets Essentials] , um die folgenden Asset-Management-Aufgaben auszuführen. Wenn Sie ein Asset auswählen, werden die folgenden Optionen in der Symbolleiste oben angezeigt.

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-image-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für ein ausgewähltes Bild.*

* ![Deaktivieren Sie ](assets/do-not-localize/close-icon.png) iconDeaktivieren Sie die Auswahl.
* ![Detailsymbol ](assets/do-not-localize/edit-in-icon.png) Klicken Sie auf , um ein Asset in der Vorschau anzuzeigen und die detaillierten Metadaten anzuzeigen. Bei der Vorschau können Sie die Versionen anzeigen und ein Bild bearbeiten.
* ![Download-](assets/do-not-localize/download-icon.png) SymbolLaden Sie das ausgewählte Asset in Ihr lokales Dateisystem herunter.
* ![Symbol &quot;Löschen&quot;](assets/do-not-localize/delete-icon.png) Löschen Sie das ausgewählte Asset oder den ausgewählten Ordner.
* 

   <!-- ![checkout icon](assets/do-not-localize/checkout-icon.png) --> Checkout an asset.
* ![Kopieren Sie ](assets/do-not-localize/copy-icon.png) iconKopieren Sie die ausgewählte Datei oder den ausgewählten Ordner.
* ![Verschieben-](assets/do-not-localize/move-icon.png) SymbolVerschieben Sie das ausgewählte Asset oder den ausgewählten Ordner an einen anderen Speicherort in der Repository-Hierarchie.
* ![Symbol ](assets/do-not-localize/rename-icon.png) umbenennen: Benennen Sie das ausgewählte Asset oder den ausgewählten Ordner um. Die Verwendung eines eindeutigen Namens schlägt andernfalls fehl und es wird ein Warnhinweis angezeigt. Sie können es mit einem neuen Namen erneut versuchen.
* 
   <!-- ![assign task icon](assets/do-not-localize/assign-task-icon.png) --> Assign tasks to other users to collaborate on an asset.

Sie können dieselben Optionen für Asset-Miniaturansichten anzeigen.

![Optionen für die Asset-Miniaturansicht zum Verwalten eines Assets](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] zeigt nur die relevanten Optionen in der Symbolleiste an, die vom Typ des ausgewählten Assets abhängen.

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-folder-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für einen ausgewählten Ordner.*

![Symbolleistenoptionen bei der Auswahl eines Assets](assets/toolbar-pdf-selected.png)

*Abbildung: In der Symbolleiste verfügbare Optionen für eine ausgewählte PDF-Datei.*

## Herunterladen und Verteilen von Assets {#download}

Sie können ein oder mehrere Assets oder Ordner oder eine Kombination aus beiden auswählen und die Auswahl in Ihr lokales Dateisystem herunterladen. Sie können die Assets bearbeiten und erneut hochladen oder die Assets außerhalb von [!DNL Assets Essentials] verteilen. Sie können auch [die Ausgabeformate](/help/add-delete.md#renditions) eines Assets herunterladen.

## Asset-Versionierung {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] Versionen der Assets, wenn die Assets erneut hochgeladen werden, die aktualisiert oder bearbeitet werden. Sie können den Versionsverlauf und frühere Versionen anzeigen und eine frühere Version von Assets als neueste Version wiederherstellen, die bei Bedarf auf eine frühere Version zurückgesetzt wird. Asset-Versionen werden in den folgenden Szenarien erstellt:

* Laden Sie ein neues Asset mit demselben Dateinamen wie ein vorhandenes Asset hoch und befinden Sie sich im selben Ordner wie das vorhandene Asset. [!DNL Assets Essentials] werden aufgefordert, entweder das vorherige Asset zu überschreiben oder das neue Asset als Version zu speichern. Siehe [Hochladen doppelter Assets](/help/add-delete.md#resolve-upload-fails).

   ![Erstellen von Versionen beim Hochladen](assets/uploads-manage-duplicates.png)

   *Abbildung: Beim Hochladen eines Assets mit dem Namen eines vorhandenen Assets können Sie eine Version des Assets erstellen.*

* Bearbeiten Sie ein Bild und klicken Sie auf **[!UICONTROL Als Version speichern]**. Siehe [Bilder bearbeiten](/help/edit-images.md).

   ![Bearbeitetes Bild als Version speichern](assets/edit-image2.png)

   *Abbildung: Speichern Sie das bearbeitete Bild als Version.*

* Öffnen Sie die Versionen eines vorhandenen Assets. Klicken Sie auf **[!UICONTROL Neue Version]** und laden Sie eine neuere Version des Assets in das Repository hoch.

   ![Option zum Hochladen einer neuen Version eines Assets aus dem Versionsverlauf](assets/view-asset-versions2.png)

### Anzeigen von Versionen eines Assets {#view-versions}

Beim Hochladen einer doppelten Kopie oder einer geänderten Kopie eines Assets können Sie dessen Versionen erstellen. Mit der Versionierung können Sie historische Assets überprüfen und bei Bedarf zu einer früheren Version zurückkehren.

Um Versionen anzuzeigen, öffnen Sie die Vorschau eines Assets und klicken Sie in der rechten Seitenleiste auf **[!UICONTROL Versionen]** ![Versionssymbol](assets/do-not-localize/versions-clock-icon.png) . Um eine bestimmte Version in der Vorschau anzuzeigen, wählen Sie sie aus. Um darauf zurückzukehren, klicken Sie auf **[!UICONTROL Neueste]**.

Sie können auch Versionen über die Timeline der Versionen erstellen. Wählen Sie die neueste Version aus, klicken Sie auf **[!UICONTROL Neue Version]** und laden Sie eine neue Kopie des Assets aus Ihrem lokalen Dateisystem hoch.

![Anzeigen von Asset-Versionen](assets/view-asset-versions1.png)

*Abbildung: Zeigen Sie Versionen eines Assets an, kehren Sie zu einer früheren Version zurück oder laden Sie eine andere neue Version hoch.*
