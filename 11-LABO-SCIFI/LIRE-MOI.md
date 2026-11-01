# Labo SciFi — export Draco

Glisser le dossier **11-LABO-SCIFI** à la racine du dépôt **corpMonde**.
Chemin du modèle publié : **11-LABO-SCIFI/labo_scifi.glb**.

Le GLB est autonome : **2,91 Mo**, avec compression Draco et textures intégrées.
Il contient 196 nœuds, 165 objets maillés, 36 matériaux et 228 748 triangles avec les instances.
Les 11 images source donnent 16 images intégrées : les 5 images supplémentaires sont les masques alpha des hologrammes, distincts de leurs images de couleur.

Animations conservées : **Ascenseur_Porte** et **Socle_Detachement**.
Les caméras et lumières de travail sont exclues selon le profil LABO_EXPORT. L’app devra fournir son éclairage et démarrer les animations souhaitées.

Deux groupes d’écrans d’anatomie sans UV ont reçu une projection plane par face dans la copie d’export. Positions et topologie conservées ; aucune décimation.

Contrôles réussis : décodage de toutes les primitives Draco, matériaux et images identiques entre les deux exports, animations identiques, réimport Blender avec tous les objets et triangles. Aucun rendu de l’app n’a été effectué à cette étape.

Voir ATTRIBUTION.md pour la provenance. Le fichier Blender de travail, ses sauvegardes et les rapports complets sont conservés hors de ce dossier d’envoi.
