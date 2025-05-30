---
title: Massenbearbeitung von Metadaten in Assets Essentials
description: Erfahren Sie, wie Sie einen vordefinierten Satz von Standard-Metadatenfeldern für mehrere Assets aktualisieren können, die gleichzeitig in Assets Essentials verfügbar sind.
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
source-git-commit: 461773235cb2d27d334b5ceb23f959dc9a848716
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 4%

---


<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="Neu">
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime und Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="Neu">
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="Neu">
            <a href="http://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>AEM Assets-Integration mit Edge Delivery Services</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="Neu">
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>Erweiterbarkeit der Benutzeroberfläche</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="Neu">
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>Benutzerdefinierte Suchfilter</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>Best Practices für die Suche</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>Best Practices für Metadaten</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Content Hub</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>Dynamic Media mit OpenAPI-Funktionen</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>Entwicklerdokumentation zu AEM Assets</b></a>
        </td>
    </tr>
</table>

# Massenbearbeitung von Metadaten in Assets Essentials{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Mit **Funktion „Massenbearbeitung von Metadaten** in Assets Essentials können Benutzer einen vordefinierten Satz von Standard-Metadatenfeldern für mehrere Asset-Dateien gleichzeitig bearbeiten. Wählen Sie mehrere Assets aus und führen Sie eine Massenaktualisierung ihres vordefinierten Satzes von Standardmetadaten gleichzeitig durch, anstatt diese Standardmetadaten für jedes Asset einzeln zu aktualisieren. Diese Funktion verbessert die Effizienz, Konsistenz und Genauigkeit von Standard-Metadateneigenschaften in einem großen Satz von Assets und verbessert so die Durchsuchbarkeit und Organisation von Assets.

## Massenbearbeitung von Asset-Metadaten {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

Führen Sie diese Schritte aus, um die Metadaten mehrerer Assets gleichzeitig in großen Mengen zu bearbeiten:

1. Klicken Sie in Assets Essentials auf **Assets**.
1. Suchen Sie nach bestimmten Assets oder suchen Sie sie mithilfe von Keywords in der Suchleiste.
1. Wählen Sie die Assets aus und klicken Sie **oberen Menü auf**&#x200B;Massenbearbeitung von Metadaten“.
   ![bulk-metadata-edit](/help/using/assets/bulk-metadata-edit1.png)
1. Bearbeiten Sie auf der Seite „Metadaten bearbeiten“ die folgenden Felder im Bedienfeld **Eigenschaften**:
   * **Status** Wählen Sie einen Status für die ausgewählten Assets aus.
   * **Ablaufdatum:** Sie ein Datum ein, nach dem die Assets nicht mehr gültig oder benötigt werden.
   * **Autor:** Geben Sie den Namen des Autors an.
   * **Schlüsselwörter:** Fügen Sie bestimmte Begriffe oder Textzeichenfolgen hinzu, die allgemeine Informationen über die Assets enthalten, um ihre Auffindbarkeit zu verbessern. Fügen Sie ein Keyword hinzu und drücken Sie die Eingabetaste oder die Eingabetaste, um der Liste ein weiteres Keyword hinzuzufügen.
   * **Tags:** Klicken Sie auf ![Tags-Symbol](/help/using/assets/tags-icon.svg), um Tags aus den verfügbaren Optionen auszuwählen. Tags bieten spezifischere Informationen über die Assets und verbessern ihre Auffindbarkeit. Auf die ausgewählten Assets bereits angewendete Tags werden im Bedienfeld **Eigenschaften** angezeigt. Wenn Sie die entsprechenden Tags nicht finden können, erstellen Sie sie und weisen Sie sie den ausgewählten Assets zu. Weitere [ zum Erstellen und Zuweisen von Tags zu Assets finden Sie unter ](/help/using/tagging-management.md)Verwalten von Tags in Assets Essentials“.
   * Klicken Sie **Speichern**, um die oben genannten Metadaten-Aktualisierungen auf die ausgewählten Assets anzuwenden. Nach dem Speichern werden Keywords und Tags angehängt, während die aktualisierten Details für Status, Ablaufdatum und Autor ihre vorhandenen Details überschreiben.

     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >Sie können die Metadaten von jeweils 100 Assets gleichzeitig bearbeiten.

Um die auf ein Asset angewendeten Metadaten-Aktualisierungen anzuzeigen, navigieren Sie zur Asset-Detailseite (wählen Sie das Asset aus und klicken Sie auf **Details**) und klicken Sie auf ![](/help/using/assets/info-icon-solid-black.svg), um die Metadaten des Assets im Bedienfeld **Informationen** anzuzeigen.

>[!NOTE]
>
>**Status**, **Ablaufdatum**, **Autor**, **Keywords** und **Tags** sind Standard-Metadateneigenschaften, die unabhängig von ordnerspezifischen Metadaten für die Massenbearbeitung verfügbar sind. Diese Metadateneigenschaften werden nur dann auf der Seite mit den Asset-Details angezeigt, wenn sie in dem Metadatenformular enthalten sind, das auf den Ordner des Assets angewendet wurde. Wenn Sie diese Standard-Metadateneigenschaften auf der Seite mit den Asset-Details nicht finden können, bearbeiten Sie das Metadatenformular des Asset-Ordners, um sie einzuschließen. Unter [Metadaten in Assets Essentials](/help/using/metadata.md) erfahren Sie, wie Sie ein Metadatenformular erstellen oder bearbeiten und es auf einen Ordner anwenden.
