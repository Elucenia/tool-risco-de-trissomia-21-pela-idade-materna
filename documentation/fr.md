<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · fr · no clinical/professional/rights approval -->

# Risque de trisomie 21 selon l’âge maternel

[conditions, sources et autorisations](https://elucenia.org/fr/outils/risco-de-trissomia-21-pela-idade-materna)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Âge maternel à la date prévue d’accouchement

`idade`

ans · intervalle: 15–50

## Édition de la méthode

Morris–Mutton–Alberman 2002 : modèle logistique nés vivants anglais/gallois 1989–1998 ; pas de risque gestationnel universel

## Formule documentée

Morris, Mutton, Alberman (2002): risque = 1 ÷ \[1 + e(7,330 − 4,211 ÷ (1 + e−0,282 × (âge − 37,23)))\]

Modèle logistique du registre national de Down d’Angleterre/Galles (1989 à 1998), corrigé pour absence de dépistage et interruption.

## Limites et population

Cette formule décrit la prévalence du syndrome de Down chez les enfants nés vivants selon l’âge maternel, à partir de données d’Angleterre et du pays de Galles de 1989–1998, en estimant l’absence de dépistage et d’interruption sélective. Elle ne fournit pas le risque à tout âge gestationnel et ne remplace pas le dépistage ou le diagnostic individuel.

## Références

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
