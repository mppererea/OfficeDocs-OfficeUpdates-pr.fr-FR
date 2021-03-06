---
title: Historique des publications de l’outil Déploiement d’Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fournit un historique des publications de l’outil Déploiement d’Office (ODT) destiné aux professionnels de l’informatique
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230062"
---
# <a name="release-history-for-office-deployment-tool"></a>Historique des publications de l’outil Déploiement d’Office

L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles qu’Office 365 ProPlus, sur vos ordinateurs clients. 


L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office. Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs. Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Systèmes d’exploitation pris en charge** : Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012 et Windows Server 2012 R2. 
 
 **Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml). 

[Télécharger l’outil Déploiement d’Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="january-16-2020"></a>16 janvier 2020

Version 16.0.12325.20288
- Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés
- Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés
- Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)


## <a name="october-31-2019"></a>31 octobre 2019

Version 16.0.12130.20272
- Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.
- Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.
- Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80


## <a name="july-10-2019"></a>10 juillet 2019

Version 16.0.11901.20022
- Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.
- Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.

## <a name="april-23-2019"></a>23 avril 2019

Version 16.0.11617.33601
- Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.
- Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).

## <a name="april-16-2019"></a>16 avril 2019

Version 16.0.11615.33602
- Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.
- Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).
- MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.

## <a name="march-13-2019"></a>13 mars 2019

Version 16.0.11509.33604
- Améliorations apportées aux scénarios de mise à niveau et de migration.

## <a name="january-14-2019"></a>14 janvier 2019

Version 16.0.11306.33602
- Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.


## <a name="related-links"></a>Liens associés

[Centre de téléchargement ODT](https://www.microsoft.com/en-us/download/details.aspx?id=49117)