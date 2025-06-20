# Advanced DSO Finder - Manuel de l'utilisateur

Bienvenue dans le manuel de l'utilisateur officiel de l'Advanced DSO Finder ! Ce document vous guidera à travers toutes les fonctionnalités de l'application, de la configuration de votre emplacement à l'analyse des objets astronomiques.

**Langues :** [Deutsch](MANUAL.de.md) | [English](MANUAL.en.md) | [Español](MANUAL.es.md) | [**Français**](MANUAL.fr.md) | [日本語](MANUAL.ja.md)

---

## Sommaire

1.  [Premiers Pas : L'interface Utilisateur](#1-premiers-pas-linterface-utilisateur)
2.  [Configurer l'Emplacement et l'Heure](#2-configurer-lemplacement-et-lheure)
    *   [Saisie Manuelle](#saisie-manuelle)
    *   [Recherche de Lieu & Auto-détection](#recherche-de-lieu--auto-détection)
    *   [Réglages de l'Heure](#réglages-de-lheure)
3.  [Filtrer les Objets](#3-filtrer-les-objets)
    *   [Échelle de Bortle & Magnitude Limite](#échelle-de-bortle--magnitude-limite)
    *   [Altitude et Taille de l'Objet](#altitude-et-taille-de-lobjet)
    *   [Illumination de la Lune](#illumination-de-la-lune)
    *   [Types d'Objets](#types-dobjets)
    *   [Direction Cardinale](#direction-cardinale)
4.  [Comprendre et Utiliser les Résultats](#4-comprendre-et-utiliser-les-résultats)
    *   [Liste des Résultats](#liste-des-résultats)
    *   [Détails de l'Objet](#détails-de-lobjet)
    *   [Analyse Graphique (Graphiques)](#analyse-graphique-graphiques)
5.  [Les Onglets Outils](#5-les-onglets-outils)
    *   [Saisie Manuelle de Cible](#saisie-manuelle-de-cible)
    *   [Calculateur de Décalage vers le Rouge](#calculateur-de-décalage-vers-le-rouge)
    *   [Calculateur d'Heures de Soleil](#calculateur-dheures-de-soleil)
6.  [Dépannage (FAQ)](#6-dépannage-faq)

---

### 1. Premiers Pas : L'interface Utilisateur

L'interface est divisée en deux zones principales :
*   **Barre latérale gauche :** Vous y trouverez tous les champs de saisie et les filtres pour définir votre recherche.
*   **Zone principale droite :** Cette zone affiche les résultats de la recherche et les outils supplémentaires dans des onglets.

![Interface de l'application](screenshots/Franzosisch_1.png)

---

### 2. Configurer l'Emplacement et l'Heure

La précision de tous les calculs dépend d'un emplacement et d'une date exacts.

#### Saisie Manuelle
Entrez votre **Latitude** et votre **Longitude** directement dans les champs correspondants.
*   Les latitudes Nord et les longitudes Est sont positives (par ex., `47.05`).
*   Les latitudes Sud et les longitudes Ouest sont négatives (par ex., `-33.92`).
L'**Élévation** au-dessus du niveau de la mer en mètres améliore la précision des calculs, en particulier près de l'horizon.

#### Recherche de Lieu & Auto-détection
*   **Rechercher :** Entrez le nom d'un lieu ou d'une ville dans le champ de recherche et cliquez sur "Rechercher". L'application remplira automatiquement les coordonnées.
*   **Auto-détection :** Cliquez sur "Auto-détection" pour déterminer votre emplacement approximatif via votre adresse IP. C'est rapide et pratique, mais peut être moins précis qu'une recherche manuelle.

#### Réglages de l'Heure
*   **Maintenant (cette nuit) :** Utilise la nuit actuelle (du coucher au lever du soleil) pour le calcul.
*   **Nuit spécifique :** Cliquez ici pour afficher un champ de saisie de date. Un clic sur le champ ouvre un calendrier pour une sélection facile de n'importe quelle date.

---

### 3. Filtrer les Objets

Utilisez les filtres pour affiner la recherche aux objets célestes qui vous intéressent.

#### Échelle de Bortle & Magnitude Limite
L'**Échelle de Bortle** mesure la pollution lumineuse de votre emplacement (1 = excellent ciel noir, 9 = centre-ville). L'application calcule automatiquement une **magnitude limite** réaliste pour la visibilité avec un télescope. Seuls les objets plus lumineux que cette valeur seront affichés.

#### Altitude et Taille de l'Objet
*   **Alt Min :** Définit l'altitude minimale qu'un objet doit avoir au-dessus de l'horizon pour apparaître dans les résultats. Une valeur de `20°` ou `30°` est recommandée pour éviter la brume et les obstacles proches de l'horizon.
*   **Alt Max :** L'altitude maximale qu'un objet peut atteindre. Généralement laissée à `90°` (zénith).
*   **Taille Min/Max :** Filtre les objets par leur taille apparente dans le ciel en minutes d'arc. Utile pour trouver soit uniquement de grands objets étendus, soit de petites nébuleuses planétaires.

#### Illumination de la Lune
*   **Illum. max. lune (%) :** Un filtre crucial. Si l'illumination de la lune pendant la nuit sélectionnée dépasse cette valeur, aucun résultat ne sera affiché, car la lune éclipserait les objets peu lumineux. Réglez la valeur sur `10%` pour observer des galaxies peu lumineuses ou sur `100%` si vous ne recherchez que des objets brillants.

#### Types d'Objets
Sélectionnez les catégories d'objets célestes qui vous intéressent (par ex., Galaxies, Nébuleuses, Amas). Utilisez les boutons "Tout sélectionner" et "Ne rien sélectionner" pour effectuer des ajustements rapides.

#### Direction Cardinale
Restreint la recherche aux objets qui atteignent leur point le plus haut dans une direction cardinale spécifique (par ex., "Sud"). Idéal si votre lieu d'observation est obstrué dans une direction.

---

### 4. Comprendre et Utiliser les Résultats

Après avoir cliqué sur "Rechercher", les résultats apparaîtront dans la zone principale droite.

#### Liste des Résultats
Par défaut, les objets sont triés par une combinaison de durée de visibilité et d'altitude maximale. Vous pouvez changer le tri pour "Luminosité".
Chaque entrée affiche le nom, le type et la magnitude de l'objet. Cliquez sur une entrée pour la développer.

#### Détails de l'Objet
Dans la vue développée, vous verrez des informations détaillées :
*   **Alt. max. :** La position la plus haute que l'objet atteint pendant la nuit.
*   **Meilleure heure (locale) :** L'heure à laquelle l'objet atteint cette altitude maximale. C'est le moment optimal pour l'observation.
*   **Durée visible :** Le nombre d'heures pendant lesquelles l'objet est visible au-dessus de l'horizon.
*   **Constellation, Taille, AD/Déc :** Données astronomiques supplémentaires.

#### Analyse Graphique (Graphiques)
*   **Profil d'altitude :** Affiche un graphique de l'altitude de l'objet tout au long de la nuit. Idéal pour visualiser la meilleure fenêtre d'observation.
*   **Trajectoire céleste :** Affiche la trajectoire de l'objet à travers le ciel, de son lever à son coucher.

---

### 5. Les Onglets Outils

#### Saisie Manuelle de Cible
Recherchez un objet spécifique (par ex., "NGC 224") ou entrez directement des coordonnées AD/Déc pour calculer la visibilité de n'importe quelle cible. Vous pouvez également enregistrer et charger des cibles fréquemment utilisées ici.

#### Calculateur de Décalage vers le Rouge
Un outil pour les passionnés de cosmologie. Entrez un décalage vers le rouge (z) pour calculer les distances cosmologiques et le temps de regard en arrière. Les descriptions contextuelles indiquent de quelle ère de l'univers provient la lumière.

#### Calculateur d'Heures de Soleil
Calcule les heures exactes du lever du soleil, du coucher du soleil, du midi solaire et la durée du jour pour votre emplacement et la date sélectionnés.

---

### 6. Dépannage (FAQ)

*   **Q : Pourquoi n'obtiens-je aucun résultat ?**
    *   **R :** Vérifiez vos filtres. Les raisons les plus courantes sont :
        1.  La Lune est trop brillante (`Illum. max. lune` est réglé trop bas).
        2.  Le filtre `Alt Min` est réglé trop haut.
        3.  Aucun type d'objet n'est sélectionné.
        4.  La nuit sélectionnée est en été dans une région proche des pôles où il ne fait pas nuit.

*   **Q : L'auto-détection de mon emplacement est imprécise.**
    *   **R :** La géolocalisation par IP peut être imprécise. Pour des résultats précis, utilisez la recherche manuelle de votre lieu ou entrez directement vos coordonnées.

---
Vous avez trouvé un bug ou avez une suggestion d'amélioration ? Veuillez créer un [Issue sur GitHub](https://github.com/Champion-22/ADSOFinder/issues).
