---
title: Integrieren von Assets Essentials mit Adobe Workfront
description: Integrieren Sie Assets Essentials in die Adobe Workfront-Anwendung, damit Sie in der Workfront-Anwendung auf das Assets Essentials-Repository zugreifen können.
source-git-commit: 7d49060ba2e02bd9c5caf9753ef56b5feed5b3df
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 19%

---


# Integrieren von Assets Essentials mit Adobe Workfront {#integrate-assets-essentials-workfront}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-workfront.png)

## Die Geschichte bis jetzt

Nachher [Konfigurieren von Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) und [Integration der Creative Cloud-Anwendungen in Assets Essentials](integrate-assets-essentials-creative-cloud.md)können Sie auf aufbauen, um die Adobe Workfront-Anwendung in Assets Essentials zu integrieren.

## Ziel

* **Zielgruppe**: Adobe Workfront-Administratoren

* **Ziel**: Integrieren Sie Assets Essentials in die Adobe Workfront-Anwendung, damit Sie in der Workfront-Anwendung auf das Assets Essentials-Repository zugreifen können.

## Übersicht

[[!DNL Adobe Workfront]](https://www.workfront.com/) ist ein Programm für das Arbeits-Management, mit dem Sie den gesamten Arbeitszyklus an einem Ort verwalten können. Die native Integration zwischen [!DNL Adobe Workfront] und [!DNL Assets Essentials] ermöglicht Unternehmen, die Geschwindigkeit von Inhalten und die Time-to-Market zu steigern, indem sie Arbeit und Asset-Management systematisch miteinander verbinden. Im Rahmen der Verwaltung ihrer Arbeit haben Benutzer in derselben Lösung Zugriff auf die erforderlichen Dokumente und Bilder.

Führen Sie die folgenden Aufgaben aus, um Workfront in Experience Manager Assets Essentials zu integrieren:

* [Hinzufügen von Benutzern zu Workfront-Produktprofilen](#add-users-to-product-profiles)

* [Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen](#add-workfront-users-assets-essentials-product-profiles)

* [Konfigurieren der Integration von Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Hinzufügen von Benutzern zu Workfront-Produktprofilen {#add-users-to-product-profiles}

So fügen Sie Workfront-Produktprofilen Benutzer hinzu:

1. Zugriff [Admin Console](https://adminconsole.adobe.com) Klicken Sie für Ihre Organisation auf **[!UICONTROL Produkte]** Klicken Sie in der oberen Leiste auf **[!UICONTROL Workfront]** und klicken Sie auf die erste Instanz in der Liste. Klicken Sie nicht auf die zweite und dritte Instanz in der Liste.

   ![Admin-Profil der Admin Console](assets/workfront-instances.png)

   Admin Console zeigt das einzige verfügbare Produktprofil an.

1. Um einen Benutzer zu einem Produktprofil hinzuzufügen, klicken Sie auf das Profil und anschließend auf **[!UICONTROL Benutzer hinzufügen]**, geben Sie die Benutzerdetails an und klicken Sie auf **[!UICONTROL Speichern]**.

   ![Hinzufügen des Administratorprofils für Benutzer](assets/add-users-workfront.png)

   Wenn Sie einen Benutzer hinzufügen, erhält der Benutzer eine Einladung per E-Mail. Sie können die E-Mail-Einladungen in den Produktprofileinstellungen in der [!DNL Admin Console] deaktivieren.

1. Um einen Benutzer aus einer Gruppe zu entfernen, klicken Sie auf die Gruppe, wählen Sie einen vorhandenen Benutzer aus und wählen Sie **[!UICONTROL Benutzer entfernen]** aus.

Weitere Informationen zum Erstellen von Benutzern und Systemadministratoren in Workfront mit Adobe Admin Console finden Sie unter [Benutzer in Adobe Admin Console verwalten](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen {#add-workfront-users-assets-essentials-product-profiles}

Weisen Sie die Workfront-Benutzer einem der folgenden Assets Essentials-Produktprofile zu:

* **[!DNL Assets Essentials]Benutzer** haben Zugriff auf die gesamte Assets Essentials-Benutzeroberfläche. Diese Benutzer können digitale Assets in der Assets Essentials-Anwendung hochladen, organisieren, taggen und suchen. Darüber hinaus haben die Benutzer Zugriff auf das Erlebnis der Asset-Auswahl in [!DNL Adobe Workfront] Anwendung.
* **[!DNL Assets Essentials]Verbraucherbenutzer**: Zugriff auf das integrierte Asset-Auswahlerlebnis in [!DNL Adobe Workfront] Anwendung.

Weitere Informationen zum Zuweisen von Benutzern zu Assets Essentials-Produktprofilen finden Sie unter [Zuweisen von Benutzern zu Assets Essentials-Produktprofilen](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Konfigurieren der Integration von Experience Manager Assets Essentials {#configure-assets-essentials-integration}

Nachdem Sie Benutzer mithilfe der Admin Console zu den Workfront- und Assets Essentials-Produktprofilen hinzugefügt haben, können Sie [Experience Manager Assets Essentials-Integration konfigurieren](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Nach der Einrichtung der Integration haben Sie folgende Möglichkeiten:

* [Verknüpfen von Assets und Ordnern aus Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Senden eines Dokuments an Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Testen eines verknüpften Assets für Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Verknüpfte Assets aus Experience Manager Assets Essentials anzeigen oder herunterladen](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
