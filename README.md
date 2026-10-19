# Modèles VGP gratuits : tableau de suivi Excel, registre de sécurité, rapport à imprimer

Classeurs Excel et trames Word gratuits pour préparer, documenter et suivre les **vérifications générales périodiques (VGP)** des appareils et accessoires de levage : chariots élévateurs, nacelles, grues, palans, hayons, élingues.

Chaque fichier est la version publiée sur [modele-vgp.fr](https://modele-vgp.fr/modeles/), où vous trouverez aussi la notice de chaque trame et les sources de chaque champ.

## Classeurs Excel

| Fichier | À quoi il sert |
|---|---|
| [`excel/tableau-suivi-vgp.xlsx`](excel/tableau-suivi-vgp.xlsx) | Tableau de suivi des échéances : prochaine VGP et jours restants calculés depuis la date de la dernière vérification, statut en couleur (à jour, à planifier sous 30 jours, en retard), périodicité proposée par type d'équipement avec son texte de référence, 200 lignes prêtes. |
| [`excel/registre-securite-vgp.xlsx`](excel/registre-securite-vgp.xlsx) | Registre de sécurité : une ligne par vérification (mise en service, périodique, remise en service), vérificateur interne ou externe, alerte si un rapport externe n'est pas annexé ou si une observation n'a pas de suite. |
| [`excel/suivi-reserves-vgp.xlsx`](excel/suivi-reserves-vgp.xlsx) | Suivi des observations et levée des réserves : action corrective, responsable, échéance, statut calculé (en cours, en retard, preuve à joindre, levée). |

Chaque classeur contient un tableau de bord, un onglet d'exemple rempli et un mode d'emploi. Aucune macro.

## Trames Word et CSV

| Trame | Word | CSV |
|---|---|---|
| Rapport VGP (appareil de levage) | [docx](word/rapport-vgp-appareil-levage.docx) | [csv](csv/rapport-vgp-appareil-levage.csv) |
| Checklist avant contrôle | [docx](word/checklist-avant-controle-vgp.docx) | [csv](csv/checklist-avant-controle-vgp.csv) |
| Fiche d'observations | [docx](word/registre-observations-vgp.docx) | [csv](csv/registre-observations-vgp.csv) |
| Suivi de levée des réserves | [docx](word/fiche-levee-reserves.docx) | [csv](csv/fiche-levee-reserves.csv) |
| Planning des contrôles | [docx](word/planning-echeances-controles.docx) | [csv](csv/planning-echeances-controles.csv) |
| Registre de sécurité | [docx](word/registre-securite-vgp.docx) | [csv](csv/registre-securite-vgp.csv) |

Les CSV utilisent le point-virgule et l'encodage UTF-8, pour une ouverture directe dans Excel en français.

## Sources

Les champs et les périodicités s'appuient sur :

- l'[arrêté du 1er mars 2004](https://www.legifrance.gouv.fr/loda/id/JORFTEXT000000439029/) relatif aux vérifications des appareils et accessoires de levage ;
- l'[arrêté du 2 mars 2004](https://www.legifrance.gouv.fr/loda/id/LEGITEXT000005765633/) relatif au carnet de maintenance ;
- les [articles R4323-23 à R4323-26 du Code du travail](https://code.travail.gouv.fr/code-du-travail/r4323-23) ;
- la brochure [INRS ED 6339](https://www.inrs.fr/media.html?refINRS=ED%206339).

Ce sont des outils de travail, pas des documents de conformité : le rapport de vérification reste celui de la personne qualifiée.

## Outils en ligne

- [Calculateur d'échéance VGP](https://modele-vgp.fr/outils/calculateur-echeance/)
- [Mes équipements](https://modele-vgp.fr/mes-equipements/), avec rappel par e-mail avant chaque échéance
- [Périodicités par équipement](https://modele-vgp.fr/periodicites/)

## Licence et citation

[CC BY 4.0](LICENSE) : réutilisation, modification et diffusion libres, y compris commerciales, en citant « modele-vgp.fr ». Pour citer ce dépôt, voir [`CITATION.cff`](CITATION.cff).

Une erreur, une trame à ajouter : ouvrez une [issue](../../issues).
