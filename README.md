# CultureSup — Édition Salon des métiers artistiques

> Explorer les écoles supérieures d'art sous tutelle du ministère de la Culture, sur un stand, sans connexion réseau (sauf pour accéder aux pages des établissements".

**CultureSup – Salon** est une page HTML autoportante qui présente, sous forme de fiches, les établissements d'enseignement supérieur artistique du réseau Culture. Elle est pensée pour être consultée par des lycéen·nes, des familles et des professionnel·les de l'orientation lors des salons, forums et journées d'information sur les métiers artistiques.

Tout tient dans un seul fichier : il s'ouvre dans un navigateur, depuis GitHub Pages ou depuis un ordinateur de stand totalement hors ligne.

---

## Sommaire

- [Pourquoi cette variante](#pourquoi-cette-variante)
- [Fonctionnalités](#fonctionnalités)
- [Utilisation sur un salon](#utilisation-sur-un-salon)
- [Mise à jour annuelle](#mise-à-jour-annuelle)
- [Limites et précautions](#limites-et-précautions)
- [Licence et crédits](#licence-et-crédits)

---

## Pourquoi cette variante

CultureSup existe d'abord comme outil d'analyse des données ParcourSup (attractivité, sélectivité, diversité, ancrage territorial) à destination des équipes du réseau. L'édition **Salon** en reprend la base de données mais change de public et d'usage :

| | CultureSup – Analyse | CultureSup – Salon |
|---|---|---|
| Public | Équipes de direction, pilotage | Futur·es candidat·es, familles, prescripteurs |
| Contenu | Indicateurs pluriannuels, comparaisons | Fiches de présentation des écoles |
| Connexion | En ligne | **Hors ligne possible** |
| Format | Page interactive + JSON | **Un seul fichier HTML** |

L'objectif est simple : permettre à une personne qui passe devant le stand de trouver en quelques gestes les écoles qui l'intéressent, de comprendre ce qu'on y apprend et comment on y entre.

## Fonctionnalités

- **Fiches établissement** reprenant la présentation des fiches Sextant : identité de l'école, statut (territoriale / nationale), localisation, formations proposées.
- **Offre pédagogique** : diplômes (DNA, DNSEP…), options et mentions.
- **Accès via ParcourSup** : critères d'examen des vœux et profil des admis, extraits des données publiques, avec le lien direct vers la fiche ParcourSup de chaque formation.
- **Recherche et filtres** : par nom, ville, région, statut, diplôme ou option.
- **Carte des écoles** (optionnelle) : vue géographique du réseau pour repérer les établissements proches de chez soi.
- **Lien vers le site web** de chaque école.
- **100 % autonome** : aucune ressource externe, aucun appel réseau ; données, styles et scripts sont embarqués dans le fichier. Sauf pour les sites établissements.

## Utilisation sur un salon

**Préparer le poste**

1. Copier `culturesup-salon.html` sur l'ordinateur du stand ou sur une clé USB.
2. L'ouvrir dans un navigateur récent (Firefox, Chrome, Edge).
3. Passer en plein écran (`F11`) pour un affichage type borne.
4. Tester la recherche, les filtres et la carte **avant l'ouverture du salon**, réseau désactivé.

**Conseils pour l'accueil du public**

- Laisser la page sur la vue d'ensemble ou sur la carte entre deux visiteurs.
- Utiliser les filtres par région pour orienter rapidement vers les écoles proches.
- Montrer le lien ParcourSup de la fiche pour que la personne puisse le retrouver chez elle.
- Prévoir un support imprimé ou un QR code vers la version GitHub Pages pour prolonger la consultation.

**Version en ligne** : la même page est publiée sur GitHub Pages à l'adresse du dépôt (`https://<compte>.github.io/culturesup-salon/`).

## Limites et précautions

- Les données ParcourSup reflètent les campagnes passées : elles donnent des repères, pas une garantie d'admission.
- Certaines écoles recrutent aussi hors ParcourSup (concours, entrée en cours de cursus) : la fiche de l'établissement et son site font foi.
- Les liens externes (site des écoles, ParcourSup) ne fonctionnent évidemment qu'avec une connexion.

## Licence et crédits

- Données ParcourSup : open data du ministère de l'Enseignement supérieur et de la Recherche, sous Licence Ouverte / Open Licence Etalab.
- Projet conçu et développé dans le cadre de l'animation du réseau des écoles d'art territoriales.
