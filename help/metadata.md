---
title: Verwalten von Metadaten
description: Verwalten von Metadaten von Assets in  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: 02f28c00b387fbcac4cd917fab7763124fdd5d70
workflow-type: ht
source-wordcount: '1026'
ht-degree: 100%

---

# Metadaten in [!DNL Assets Essentials] {#metadata}

Metadaten sind Daten oder Beschreibungen zu den Daten. Beispielsweise können Ihre Bilder als Asset Informationen über die Kamera, mit der sie aufgenommen wurden, oder Copyright-Informationen enthalten. Diese Informationen sind Metadaten des Bildes. Metadaten sind für ein effizientes Asset-Management von entscheidender Bedeutung. Metadaten stellen die Sammlung aller für ein Asset verfügbaren Daten dar, sind aber nicht unbedingt im Bild selbst enthalten.

Mit Metadaten können Sie Assets genauer einteilen. Außerdem erweisen sie sich als nützlich, wenn die Menge digitaler Daten ansteigt. Es ist möglich, einige Hundert Dateien zu verwalten, die nur auf den Dateinamen, den Miniaturbildern und dem Speicherbedarf basieren. Dieser Ansatz ist jedoch nicht skalierbar. Er reicht nicht aus, wenn die Zahl der beteiligten Personen und die Zahl der verwalteten Assets steigt.

Durch das Hinzufügen von Metadaten steigt der Wert eines digitalen Assets, da das Asset folgende Eigenschaften aufweist:

* besser zugänglich – Systeme und Benutzer können es leicht finden.
* einfacher zu verwalten – Sie können Assets mit denselben Eigenschaften einfacher finden und Änderungen auf sie anwenden.
* vollständig – Asset enthält mehr Informationen und Kontext mit mehr Metadaten.

Aus diesen Gründen erhalten Sie mit Assets die richtigen Mittel, um Metadaten für digitale Assets zu erstellen, zu verwalten und auszutauschen.

## Anzeigen der Metadaten {#view-metadata}

Um die Metadaten eines Assets anzuzeigen, navigieren Sie zum Asset oder suchen Sie das Asset, wählen Sie das Asset aus und klicken Sie in der Symbolleiste auf **[!UICONTROL Details]**.

![Anzeigen von Metadaten eines Assets](assets/metadata-view1.png)

*Abbildung: Um ein Asset und seine Metadaten anzuzeigen, klicken Sie in der Symbolleiste auf **[!UICONTROL Details]** oder doppelklicken Sie auf das Asset.*

Die grundlegenden Metadaten wie Titel, Beschreibung und Upload-Datum sind auf der Registerkarte [!UICONTROL Standard] verfügbar. Die Registerkarte [!UICONTROL Erweitert] enthält erweiterte Metadaten wie Kameramodell, Informationen zum Objektiv und Geotags. Die Registerkarte [!UICONTROL Tags] enthält automatisch vergebene Tags, die auf dem Inhalt des Bildes basieren.

## Aktualisieren von Metadaten {#update-metadata}

Einige Metadatenfelder können Sie manuell aktualisieren. Diese Felder sind unter anderem [!UICONTROL Titel], [!UICONTROL Beschreibung], [!UICONTROL Autor] und [!UICONTROL Schlüsselwörter].

## Tags {#tags}

[!DNL Assets Essentials] verwendet künstliche Intelligenz, die von [Adobe Sensei](https://www.adobe.com/de/sensei.html) bereitgestellt wird, um automatisch relevante Tags zu allen hochgeladenen Assets hinzuzufügen. Diese Tags, auch Smart-Tags genannt, erhöhen die Geschwindigkeit der Inhaltserstellung Ihrer Projekte, da Sie relevante Assets schnell finden können. Die Smart-Tags sind ein Beispiel für Metadaten, die nicht im Bild enthalten sind.

Die Smart-Tags werden nahezu in Echtzeit hinzugefügt und basierend auf dem Inhalt des Bildes generiert. Wenn Sie ein Asset hochladen, zeigt die Benutzeroberfläche für einige Zeit [!UICONTROL Wird verarbeitet] auf der Asset-Miniaturansicht an. Sobald die Verarbeitung abgeschlossen ist, können Sie [die Metadaten und die Smart-Tags anzeigen](#view-metadata).

![Anzeigen von Smart-Tags eines Assets](assets/metadata-view-tags.png)

*Abbildung: Um die Smart-Tags eines Assets anzuzeigen, klicken Sie in der Symbolleiste auf **[!UICONTROL Details]** oder doppelklicken Sie auf das Asset.*

Smart-Tags enthalten auch einen Konfidenzwert in Prozent. Er zeigt die Konfidenz an, die mit dem angebrachten Tag verbunden ist. Sie können die automatisch angebrachten Smart-Tags moderieren.

## Hinzufügen oder Aktualisieren von Tags {#manually-tag}

Zusätzlich zu den Smart-Tags, die automatisch mit dem intelligenten Service [!DNL Adobe Sensei] hinzugefügt werden, können Sie Ihren Assets weitere Tags hinzufügen. Öffnen Sie ein Asset für die Vorschau, klicken Sie auf [!UICONTROL Tags] und geben Sie die gewünschten Keywords in das Feld [!UICONTROL Keywords] ein. Um das Tag hinzuzufügen, drücken Sie die Eingabetaste. [!DNL Assets Essentials] indiziert das Keyword nahezu in Echtzeit und Ihr Team kann die aktualisierten Assets bald mit den neuen Keywords durchsuchen.

Sie können Tags auch aus dem Abschnitt [!UICONTROL Smart-Tags] entfernen, die automatisch von [!DNL Assets Essentials] zu allen hochgeladenen Assets hinzugefügt werden.

## Metadatenformulare {#metadata-forms}

Assets Essentials bietet standardmäßig viele Standard-Metadatenfelder. Unternehmen haben zusätzliche Metadatenanforderungen und benötigen mehr Metadatenfelder, um geschäftsspezifische Metadaten hinzuzufügen. Mit Metadatenformularen können Unternehmen benutzerdefinierte Metadatenfelder zur Seite [!UICONTROL Details] eines Assets hinzufügen. Die geschäftsspezifischen Metadaten verbessern die Verwaltung und Erkennung der Assets.

Sie können Metadatenformulare für verschiedene Asset-Typen (verschiedene MIME-Typen) konfigurieren. Verwenden Sie denselben Formularnamen wie den MIME-Typ der Datei. Essentials ordnet die hochgeladenen Assets automatisch dem Namen des Formulars zu. Wenn beispielsweise ein Metadatenformular mit dem Namen `PDF` oder `pdf` vorhanden ist, enthalten die hochgeladenen PDF-Dokumente Metadatenfelder, wie sie im Formular definiert wurden. Sie können Formulare von Grund auf neu erstellen oder ein vorhandenes Formular wiederverwenden.

>[!IMPORTANT]
>
>Das neue Metadatenformular für einen bestimmten Dateityp ersetzt vollständig das Standard-Metadatenformular, das [!DNL Assets Essentials] bereitstellt. Wenn Sie ein Metadatenformular löschen oder umbenennen, sind die Standard-Metadatenfelder wieder für neue Assets verfügbar.

Gehen Sie wie folgt vor, um ein Metadatenformular zu erstellen:

1. Klicken Sie in der linken Leiste auf **[!UICONTROL Einstellungen]** > **[!UICONTROL Metadatenformulare]**.

   ![Option für Metadatenformulare in der linken Seitenleiste](assets/metadata-forms-sidebar.png)

1. Klicken Sie oben rechts in der Benutzeroberfläche auf **[!UICONTROL Erstellen]**.
1. Geben Sie einen Namen für das Formular an und klicken Sie auf **[!UICONTROL Erstellen]**.
1. Geben Sie in **[!UICONTROL Einstellungen]** in der rechten Leiste einen Namen für die Registerkarte ein.
1. Ziehen Sie die erforderlichen Komponenten aus den in der linken Leiste verfügbaren **[!UICONTROL Komponenten]** auf eine Registerkarte im Formular. Ziehen Sie die Komponenten in die gewünschte Sequenz.

   ![Option für Metadatenformulare in der linken Seitenleiste](assets/metadata-form-new.png)

   *Abbildung: Benutzeroberfläche zur Erstellung von Metadatenformularen mit Optionen zum Hinzufügen von Komponenten und der Option zum Anzeigen einer Vorschau des Formulars.*

1. Geben Sie in der rechten Leiste in den **[!UICONTROL Einstellungen]** für jede Komponente einen Namen für die Zuordnung mit den unterstützten Eigenschaften ein.
1. Optional können Sie für eine Komponente **[!UICONTROL Erforderlich]** auswählen, damit das Metadatenfeld ein Pflichtfeld wird, und Sie können **[!UICONTROL Schreibgeschützt]** auswählen, damit das Feld auf der Seite [!UICONTROL Details] nicht bearbeitbar ist.
1. Klicken Sie optional auf **[!UICONTROL Vorschau]**, um eine Vorschau des erstellten Formulars anzuzeigen.
1. Optional können Sie auf jeder Registerkarte weitere Register und die erforderlichen Komponenten hinzufügen.
1. Klicken Sie auf **[!UICONTROL Speichern]**, wenn das Formular vollständig ist.

Nachdem ein Formular erstellt wurde, wird es automatisch angewendet, wenn Benutzer ein Asset des entsprechenden MIME-Typs hochladen.

Wenn Sie ein vorhandenes Formular wiederzuverwenden wollen, um ein neues Formular zu erstellen, wählen Sie ein Metadatenformular aus, klicken Sie in der Symbolleiste auf **[!UICONTROL Kopieren]**, geben Sie einen Namen ein und klicken Sie auf **[!UICONTROL Bestätigen]**. Sie können ein Metadatenformular bearbeiten, um es zu ändern. Wenn Sie ein Formular ändern, wird es für Assets verwendet, die nach der Änderung hochgeladen wurden. Die vorhandenen Assets werden nicht geändert.

## Nächste Schritte {#next-steps}

* [Video zum Verwalten von Metadatenformularen in Assets Essentials ansehen](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html?lang=de)

* Geben Sie Produkt-Feedback über die Option [!UICONTROL Feedback] in der Benutzeroberfläche von Assets Essentials

* Geben Sie Feedback zur Dokumentation durch ![Bearbeiten der Seite](assets/do-not-localize/edit-page.png) über die Option [!UICONTROL Diese Seite bearbeiten] oder durch ![Erstellen eines GitHub-Themas](assets/do-not-localize/github-issue.png) über die Option [!UICONTROL Problem protokollieren] in der rechten Seitenleiste

* Kontaktieren Sie die [Kundenunterstützung](https://experienceleague.adobe.com/?support-solution=General&amp;lang=de#support)

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
