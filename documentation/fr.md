<!-- ELUCENIA technical documentation · pressao-arterial-media · fr · no clinical/professional/rights approval -->

# Pression artérielle moyenne et pression pulsée

[conditions, sources et autorisations](https://elucenia.org/fr/outils/pressao-arterial-media)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Pression systolique

`pas`

mmHg · intervalle: 50–300

### Pression diastolique

`pad`

mmHg · intervalle: 20–200

## Édition de la méthode

PAM=(PAS+2 PAD)/3 ; pression pulsée PAS−PAD ; approximation adulte à rythme habituel ; guide brésilien 2020

## Formule documentée

PAM = PA diastolique + (PA systolique − PA diastolique) ÷ 3

Pression pulsée = PA systolique − PA diastolique

## Limites et population

L’approximation par la pression diastolique plus un tiers de la pression pulsée suppose une fréquence cardiaque normale, selon la déclaration AHA 2019 ; il ne s’agit pas de l’intégration directe de la courbe de pression. Utilisez les pressions systolique et diastolique en mmHg, obtenues avec une technique et un appareil appropriés, et documentez les conditions de mesure. La différence systolique moins diastolique est la pression pulsée, pas la fréquence du pouls. Le résultat seul n’établit ni diagnostic d’hypertension ni cible universelle pour les patients en état critique.

## Références

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

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
