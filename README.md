# Jeu-d-aventure

Contrat sur celo : 0xe9eE09C90D751Dd58afBbf21a8DdA09824d0830E

Comment jouer :
1. Démarrer :
soliditycommencerPartie("VotreNom")
2. Actions disponibles :

explorer() - Voir la description de la salle actuelle
deplacer("nord/sud/est/ouest") - Se déplacer
chercher() - Trouver des objets cachés
combattre() - Affronter des ennemis
utiliserPotion() - Se soigner (+50 PV)
ouvrirCoffre() - Gagner le jeu !

3. Consulter l'état :

obtenirStats() - Vos PV, force, score, position
obtenirInventaire() - Vos objets
afficherCarte() - Plan du donjon (si trouvée)

Structure du jeu :
7 salles à explorer :

Entrée - Point de départ
Couloir sombre - Dangereux sans torche !
Armurerie - Trouvez l'épée (+15 force)
Salle du gardien - Boss à combattre pour la clé
Bibliothèque - Carte du donjon
Laboratoire - Potion de soin
Salle du trésor - Victoire !

Objets à collecter :

🗡️ Épée (Armurerie) - Nécessaire pour vaincre le gardien
🔑 Clé (Gardien) - Ouvre la salle du trésor
🧪 Potion (Laboratoire) - Restaure 50 PV
🔦 Torche (Couloir) - Éclaire les zones sombres
🗺️ Carte (Bibliothèque) - Affiche le plan

Stratégie pour gagner :

Allez à l'Armurerie (est) → Cherchez l'épée
Allez à la Bibliothèque (nord, nord) → Cherchez la carte
Allez au Laboratoire (est) → Cherchez la potion
Retournez au Couloir (ouest, sud, ouest, nord) → Cherchez la torche
Avancez vers le Gardien (nord) → Combattez-le
Entrez dans la Salle du trésor (est) → Ouvrez le coffre !

Système de score :

Déplacement : +10 points
Objets trouvés : +20 à +50 points
Victoire contre le gardien : +100 points
Trésor : +200 points
Bonus PV restants : PV × 2

Le jeu est court (10-15 minutes), amusant, et complètement gratuit ! 🎮RetryClaude does not have the ability to run the code it generates yet.Claude can make mistakes. Please double-check responses.
