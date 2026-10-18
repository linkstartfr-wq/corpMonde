# Glucose 18E — textures partagées

Parcours 1–4616 à 30 images/s. Les données de caméra, les 606 objets, les animations et le binaire de géométrie sont conservés.

Le catalogue commun est `../../shared/textures/catalog.json`. Neuf textures réutilisent les adresses GitHub enregistrées des fichiers déjà publiés, dont trois PNG identiques en pixels mais encodés différemment. Les trois nouvelles images sont dans le même dossier partagé, avec un nom issu de leur empreinte. Il n'y a plus de dossier de textures propre au parcours.

Les URI du GLB et les chemins dans les bindings sont déjà corrigés. Les anciens lots 01–07 gardent leurs chemins ; aucune réimportation de leurs images n'est nécessaire. Pour les prochains parcours, réutiliser le même catalogue et ses URI.

`data/*.json.gz` nécessite une décompression par le chargeur ou l'en-tête HTTP adapté. Les matériaux procéduraux restent à reprendre depuis `materialbindings18E.json`. Les contrats du dissolve/float et des modales sont conservés dans `app-contracts` ; l'app reste à intégrer.

Les gros rapports de travail et les fichiers Blender restent dans `outputs/route18e-final-20261018`, hors du dossier à envoyer. `validation.json` décrit les contrôles de ce paquet. Aucun push, déploiement ou lancement de l'app effectué.
