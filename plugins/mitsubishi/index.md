# MelCloud Mitsubishi

## Présentation

Ce plugin permet d'interconnecter Jeedom avec le cloud Mitsubishi (MelCloud)

Il permet ainsi de piloter une PAC ou des climatisations

Tous les équipements du compte MelCloud sont automatiquement créés

## Configuration

Le plugin nécessite le compte mail et mot de passe du compte MelCloud.

Une fois saisie, le plugin va récupérer les équipements présents sur l'API et les créer dans Jeedom.

Suivant si c'est une PAC ou une clim (non testée chez moi), il va créer les commandes infos et actions.

Pour une PAC :

 - slider pour paramétrer la consigne (pour les 2 zones)

 - la sonde de température (pour les 2 zones)

 - la consigne de température (pour les 2 zones)

 - le mode de chauffage (pour les 2 zones) en numérique (0,1,2) et texte (thermostat, température d'eau, loi d'eau)

 - la température extérieure

 - la température de l'ECS

 - la consigne ECS

 - si le mode Eco ECS est actif

 - forcer le mode chauffe de l'eau

 - eteindre le mode forcé du chauffage de l'eau

 - allumer/eteindre/statut de la PAC

Pour une climatisation :

 - modes chauffage/séchage/froid/ventile/auto

 - le mode en cours

 - la consigne température

 - la consigne ventilation

 - allumer/eteindre/statut de la PAC

## FAQ

> Est-ce que le plugin s'appuie sur des API tiers ?

Oui, le plugin utilise l'API MelCloud de Mitsubishi (qui permet de raccorder les PAC avec un module Wifi).


## Changelog

[Voir la page dédiée](changelog.md).