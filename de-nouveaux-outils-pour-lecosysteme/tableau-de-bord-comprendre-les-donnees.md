---
description: >-
  Ici, on vous explique en toute transparence comment sont calculés les chiffres
  que vous consultez
---

# Tableau de bord : comprendre les données

## D'où viennent ces chiffres ?

Nous collectons des données auprès des CFA en nous connectant à leur ERP.

A ce jour 759 CFA utilisateurs de Gesti ou Yparéo transmettent leurs données.

## Quelles sont les données collectées ?

Les données collectées sont : 

* **Apprenant** : INE, Nom, Prénoms, Adresse mail
* **Statut :**
  * Apprenti : apprenant en formation et en contrat dans une entreprise
  * Apprenant sans Contrat : apprenant affecté à un groupe ou ayant démarré sa formation mais qui n'a pas encore signé de contrat avec une entreprise
  * Abandon : apprenant sans contrat ou apprenti ayant quitté définitivement la formation 
* **Formation**  : Certification, date de début, date de fin, localisation
* **Apprenant** : INE, Nom, Prénoms, Adresse mail
* **Statut :**
  * Apprenti : apprenant en formation et en contrat dans une entreprise
  * Apprenant sans Contrat : apprenant affecté à un groupe ou ayant démarré sa formation mais qui n'a pas encore signé de contrat avec une entreprise
  * Abandon : apprenant sans contrat ou apprenti ayant quitté définitivement la formation 
* **Formation**  : Certification, date de début, date de fin, localisation

## A quelle date les données sont-elles arrêtées ?

A ce jour Yparéo nous transmet les données de manière quotidienne et Gesti chaque lundi. De fait les données sont constamment rafraîchies.

Lorsque vous consultez le mois en cours, les données affichées sont celles du dernier jour disponible : 

_ex : si je sélectionne janvier 2021, je visualise les effectifs à la date du 31 janvier 2021 : nb Apprentis, Nb Apprenants sans contrat, Nb Abandon sur les formations en cours_

_ex : si je sélectionne janvier 2021, je visualise les effectifs à la date du 31 janvier 2021 : nb Apprentis, Nb Apprenants sans contrat, Nb Abandon sur les formations en cours_

Lorsque vous sélectionnez un mois antérieur, les données affichées sont une photographie "fin de mois", c'est à dire au dernier jour du mois consulté _\(si vous sélectionnez décembre, les données affichées sont celle du 31 décembre\)_

## Il y a un écart entre mes chiffres et ceux du tableau de bord

Si cet écart est faible, il peut s'expliquer par un dédoublonnement qui ne s'est pas fait correctement. En effet, nous importons les données chaque nuit et nous construisons un historique des statuts des jeunes afin de pouvoir vous restituer les données rétrospectivement. Afin de ne pas comptabiliser un apprenant 2 fois, nous procédons à un dédoublonnement basé sur : l'INE \(lorsqu'il est renseigné\) ou Nom-Prenoms-Mail. Il pourra arriver que cette opération ne suffise pas à identifier un apprenant : 

_Par exemple : si l'apprenant a changé d'adresse mail, alors il ne sera pas reconnu comme doublon et pourra être comptabilisé 2 fois._ 

_Par exemple : si l'apprenant a changé d'adresse mail, alors il ne sera pas reconnu comme doublon et pourra être comptabilisé 2 fois._ 

Si cet écart est supérieur à quelques unités, nous vous invitons à nous écrire pour nous le signaler afin de nous permettre d'améliorer en cliquant sur le lien **je signale une anomalie** sur la page de votre CFA

##  Je ne retrouve pas mon CFA

La recherche se fait par numéro d'UAI.

Par ailleurs, la transmission de données est conditionnée à l'identification de l'établissement par son SIRET. Assurez-vous que le SIRET renseigné dans votre base de comporte pas d'erreur.

Enfin, si vous utilisez Yparéo, un paramétrage est nécessaire. Pour obtenir le pas à pas de paramétrage, écrivez-nous à l'adresse suivante :  ****[**tableau-de-bord@apprentissage.beta.gouv.fr**](mailto:tableau-de-bord@apprentissage.beta.gouv.fr)

## Mon réseau n'apparaît pas dans la liste proposée

Nous référençons les différents réseaux au fur et à mesure que nous collectons les informations. Si vous faîtes partie d'un réseau, vous pouvez demander à être référencé en nous fournissant la liste exhaustive des établissements sur le plan national : SIRET - UAI - Nom du CFA, à l'adresse suivante :  ****[**tableau-de-bord@apprentissage.beta.gouv.fr**](mailto:tableau-de-bord@apprentissage.beta.gouv.fr)

## Pourquoi ne peut-on pas avoir accès aux données hors Normandie ?

Le Tableau de bord est déployé en version Bêta, c'est à dire que nous continuons à travailler sur les données exposées avec les utilisateurs. Nous conduisons pour cela un déploiement incrémental qui démarre par la Région Normandie. Lorsque nous aurons achevé la première phase de validation des données, nous étendrons le périmètre géographique

## Y a-t-il un traitement statistique des données ?

Non. Nous effectuons un dédoublonnement à partir des données personnelles des apprentis et nous constituons un historique afin de pouvoir tracer les changements de statut d'un apprenant _\(d'Apprenti à Abandon, par exemple\)_ mais nous ne faisons aucun traitement statistique. 

Les données exposées correspondent aux effectifs des CFA en temps réel. De ce fait, lorsqu'un établissement enregistre une information dans son Système d'Information \(Inscription, Nouveau Contrat...\) l'information est restituée le lendemain ou la semaine suivante au plus tard \(Gesti\) dans le Tableau de bord

## Vous avez une autre question &gt; écrivez nous !

Vous pouvez adresser vos questions à notre équipe en écrivant à :  ****[**tableau-de-bord@apprentissage.beta.gouv.fr**](mailto:tableau-de-bord@apprentissage.beta.gouv.fr)





