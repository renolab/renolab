# @renolab - Base Travaux

Une base de données des travaux d'économies d'énergie utilisée par l'ensemble des outils et services du programme Rénolab. Inspiré de [publicodes](https://github.com/publicodes/publicodes), la nomenclature de la Base Travaux respecte le format `namespace . valeur`.

A titre d'exemple, la valeur `isolation des murs par l'extérieur` est rattachée au namespace `rénovation . isolation . isolation des murs`.

Afin de garantir l'interopérabilité de la Base Travaux avec les outils existant, notamment Publicodes, chaque entrée est divisée en deux champs `option` et `valeur`.

## Arbres des options (tree view)

- rénovation
    - rénovation globale
    - isolation
        - isolation des murs
        - isolation des combles et toitures
        - isolation des plancher
        - ouvrants
        - protections solaires
    - chauffage et eau chaude sanitaire
        - chaudières
        - poêles et inserts
        - pompes à chaleur
        - réseaux de chaleur
        - émetteurs
        - régulation
        - réseau
        - chauffe-eaux
    - refroidissement
    - ventilation
    - équipements
    - services
