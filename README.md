# Analyse des ventes — Librairie Lapage

Analyse des indicateurs de vente et du comportement client pour la librairie
en ligne Lapage, avec restitution stratégique en comité de direction.

---

## Contexte / besoin métier

Lapage est une librairie physique multi-points de vente qui a ouvert son site
e-commerce il y a 2 ans. Le responsable commercial souhaite faire
le point global sur les indicateurs clés de l'activité pour orienter ses
décisions : créer de nouvelles offres, adapter les prix, cibler certains
segments de clientèle.

La mission se découpe en deux volets :
- **Indicateurs de vente** : chiffres clés de l'activité en ligne
- **Comportement client** : analyse du profil et des habitudes d'achat en ligne,
  à comparer avec la connaissance issue des magasins physiques


## Données

- **Source** : base de données transactionnelle fournie par Lapage
  (produits, clients, ventes en ligne)
- **Période** : depuis l'ouverture du site, il y a 2 ans
- **Qualité** : nettoyage nécessaire (doublons, valeurs aberrantes, types à corriger)
- **Limites** : données limitées au canal en ligne, pas d'historique détaillé
  des ventes en magasin physique pour comparaison directe

## Démarche

1. **Nettoyage et fusion** des tables (transactions, produits, clients)
2. **Indicateurs de vente** : chiffre d'affaires, évolution temporelle,
   répartition par catégorie, top produits
3. **Analyse clients** : profil démographique, comportement d'achat,
   corrélations (âge, genre, montant, catégorie)
4. **Tests statistiques** : vérification des liens entre variables
   (corrélation, chi², ANOVA selon les cas)
5. **Synthèse stratégique** : mise en forme des résultats pour une restitution
   de 15 minutes à un public non technique

## Résultats

- Vue d'ensemble des indicateurs de vente en ligne depuis le lancement du site
- Identification des produits et catégories les plus performants
- Profil type du client en ligne, avec comportements d'achat distinctifs
- Recommandations concrètes sur les offres, prix et ciblage

## Limites & pistes

- Pas de comparaison directe possible avec les données des magasins physiques
  (non fournies dans le même niveau de détail)
- Recul limité à 2 ans d'activité en ligne
- **Pistes** : croiser avec les données de vente en magasin, mettre en place
  un suivi périodique des mêmes indicateurs, approfondir la segmentation
  client avec une méthode RFM
