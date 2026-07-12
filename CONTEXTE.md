# Contexte complet — Site Truck Race & Delivery Contest (Umami Restaurant)

## Historique complet depuis le début

1. **Point de départ**
   - Demande initiale : créer un site pour un évènement organisé par Umami Restaurant — Course de camion 250kg inter-entreprise & Concours de livery, à l'aéroport de Sandy Shore
   - Logo Umami fourni (dragon rouge/noir)

2. **Idée de tracé de circuit**
   - Une proposition de tracé (circuit fermé sur les pistes/taxiways de l'aéroport, chicanes en pneus, épingle, sens horaire) a été montrée à titre d'aperçu
   - **Non encore intégrée au site** — mise de côté ("on verra plus tard")

3. **Création du site**
   - Bannière officielle de l'évènement (poster Truck Race & Delivery Contest) intégrée en page d'accueil
   - Logo Umami intégré en navigation et en footer
   - Sections d'origine : évènement (course + concours), infos pratiques, lieu

4. **Mise en place GitHub**
   - Dépôt git initialisé, connecté à `https://github.com/Antho6262/umami-truck-race.git`
   - Site publié via GitHub Pages : `https://antho6262.github.io/umami-truck-race`

5. **Mise à jour visuelle**
   - Remplacement du visuel d'accueil par la nouvelle bannière (2ème édition)
   - Logo Umami ajouté en fond de page (filigrane discret)
   - Mention "Restaurant Umami — Organisateur" ajoutée

6. **Palette graphique**
   - Passage à une palette dominante rouge / noir / dorée

7. **Section infos pratiques**
   - Suppression du bloc "Livraisons stratégiques"
   - Grille repassée à 3 colonnes (Courses intenses, Lots exclusifs, Ambiance garantie)

8. **Onglet Inscription**
   - Formulaire créé : nom entreprise, 3 pilotes titulaires + 1 remplaçant, participation financière (oui/non + montant), participation aux lots (oui/non), RIB
   - Envoi d'abord prévu par mail, puis basculé vers **Formspree** (formulaire visible uniquement par toi via ton compte, pas par les entreprises)
   - Endpoint Formspree corrigé : `https://formspree.io/f/xbdnrkyo`

9. **Nom de domaine**
   - Tentative avec `truckraceumami.com` (non acheté, abandonné)
   - Retour à l'URL GitHub Pages gratuite : `https://antho6262.github.io/umami-truck-race`
   - Fichier `CNAME` retiré, restriction de domaine Formspree mise à jour sur `antho6262.github.io`

10. **Onglet Règlement**
    - 8 sections initiales : objet, conditions de participation, la course, sécurité/fair-play, concours de livery, participation financière/lots, récompenses, responsabilité
    - Corrections : la course se joue au premier arrivé (pas de chrono) ; collisions/sorties de piste font perdre du temps sans disqualifier ; couper le circuit = disqualification de la manche ; concours de livery jugé au nombre de likes sur la publication Weazel News
    - 4 sections ajoutées : Partenaires (respect obligatoire), Droit à l'image, Report/annulation, Modification du règlement

11. **Onglet Partenaires**
    - Nouvelle section dédiée avec message de remerciement
    - 4 emplacements logos (en pointillés) prêts à recevoir les images des partenaires

12. **Décoration**
    - Deux dragons stylisés dessinés en linework doré/rouge, fixés en fond (haut droite / bas gauche), faible opacité

## État actuel du site (onglets)

- Accueil (bannière + logo en fond)
- L'évènement
- Infos pratiques
- Lieu
- Règlement
- Partenaires
- Inscription

## En attente / non fait

- Tracé du circuit : pas encore intégré au site (idée visuelle seulement)
- Logos partenaires : emplacements prêts mais vides, à compléter

## Pour ajouter un logo partenaire

```html
<img src="assets/partenaire-nom.png" alt="Nom du partenaire">
```

Remplace `<span>Logo</span>` par ce code, et place l'image dans le dossier `assets`.

## Git (dernière modification en date)

```
git add .
git commit -m "Ajout onglet Partenaires"
git push
```
