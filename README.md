# Répertoire des chevaux de Star Stable Online.

Répertoire complet des races et des robes des chevaux de Star Stable Online. L'objectif est de pouvoir m'en servir sur le site pour faire un comparateur par « Particularité » qui couvre trois grands profils de joueurs et joueuses de SSO sans devenir un catalogue :
- Les compétitrices : tri par stats .
- Les collectionneuses de mécaniques : filtre par allures spéciales, mouvements et robes magiques.
- Les joueuses RP / Clubs : filtre par discipline (ex: « Quel cheval acheter pour mon club western ou dressage? »).


Pour les disciplines, garder les termes autour de 6 à 8 grandes catégories fixes :
- Dressage
- Saut d'obstacles (CSO)
- Western
- Loisir / Randonnée
- Trait / Travail (pour les chevaux lourds, attelage, ferme)
- Course / Endurance
- Polyvalent (quand la race excelle un peu partout)


## index.html

Ce fichier est conçu comme un tableau de bord de suivi personnel. Il va chercher dynamiquement les fichiers races.json et robes.json, fait le lien entre les deux, et affiche :
- Une vue globale de ma progression (combien de robes tu possèdes par rapport au total).
- Un tableau de suivi par race avec le détail des robes, des prix, des stats, et un indicateur visuel pour savoir si tu as acquis la robe ou non.

Il est pensé en HTML/CSS simple (avec un design moderne et épuré) et intègre un petit script JavaScript intégré pour que tu puisses l'ouvrir directement depuis ton navigateur ou l'héberger en local/GitHub Pages sans configuration lourde.