GYM MINI — VERSION 5

Une interface épurée pour suivre tes quatre séances, une série à la fois.

UTILISATION
1. Choisis Upper 1, Lower 1, Upper 2 ou Lower 2.
2. Ajuste le poids et les répétitions, puis touche « Valider la série ».
3. Le repos de deux minutes démarre. Tu peux le passer.
4. Déplie « Le programme » pour changer d’exercice. Les pastilles permettent
   de revenir sur une série enregistrée. « Annuler » retire la dernière saisie.
5. Termine la séance pour l’ajouter à l’historique et à la progression.
   Une séance partielle demande confirmation. Une séance vide ne compte pas.

ACCUEIL
La tuile verte suggère la prochaine séance dans le cycle existant.
Tu restes libre de choisir une autre séance. L’objectif reste 4 par semaine.
La séance en cours se conserve quand tu quittes l’application.

DONNÉES ET MIGRATION
Les données restent dans le navigateur, sans compte ni envoi externe.
Réglages > Sauvegarder mes données crée un fichier JSON.
Réglages > Importer une sauvegarde accepte les anciens backups V4.
L’import est validé puis demande confirmation avant remplacement ; une
sauvegarde des données actuelles est proposée par téléchargement automatique.
Vérifie que ce fichier est bien téléchargé si tu veux conserver les deux versions.
L’export CSV utilise un séparateur point-virgule et l’encodage UTF-8 pour Excel.
Le changement kg/lb convertit aussi les poids déjà enregistrés.

Pour mettre à jour une installation existante, sauvegarde d’abord depuis la V4.
La V5 conserve la même clé de stockage : sur la même origine et dans le même
navigateur, l’historique est repris. Sur une nouvelle adresse ou un autre
navigateur, importe ton JSON. Un ZIP seul ne contient pas ton historique.
La suppression des données du navigateur peut effacer le suivi local.

APERÇU SUR ORDINATEUR
Ouvre index.html pour consulter et utiliser l’application localement.
Le mode hors ligne installable nécessite un serveur HTTP local ou HTTPS.

INSTALLATION IPHONE
Le dossier doit être servi sur une adresse HTTPS. Ouvre cette adresse dans
Safari, puis utilise Partager > Ajouter à l’écran d’accueil.
Après un premier chargement complet, les fichiers sont mis en cache pour
l’utilisation hors ligne. Après une mise à jour, ferme tous les onglets et
l’application, puis rouvre-la pour activer la nouvelle version.
Aucun hébergement ni publication n’a été effectué avec cette livraison.

OPTION MINUTEUR IPHONE / MUSIQUE
L’option existante est conservée et désactivée par défaut.
Elle demande un raccourci nommé exactement « Gym Rest 2m », qui démarre un
minuteur de 2 minutes, et la fin de minuteur « Arrêter la lecture » dans Horloge.
L’application demande l’exécution de ce raccourci ; elle ne contrôle pas
directement Apple Music ou Spotify et ne confirme pas l’arrêt de la musique.
Passer le repos dans l’application n’annule pas un minuteur système déjà lancé.
Le chrono local recalcule le temps au retour au premier plan. Il ne garantit
pas une alerte sonore lorsque l’écran est verrouillé.

PROGRESSION
Le score des exercices chargés est un indice estimé : poids × (1 + reps / 30).
Pour les exercices au poids du corps, il suit les répétitions uniquement.
La moyenne des variations est indicative ; elle ne mesure pas un gain global
de force. Les périodes 1 / 3 / 6 mois correspondent à 28 / 84 / 182 jours.

VÉRIFICATIONS
Parcours testés automatiquement dans Chromium : petits écrans de 320 à 430 px,
ordinateur, saisie et contrôle des valeurs, séries non consécutives, annulation,
reprise après rechargement, fin de séance, historique détaillé, progression,
conversion kg/lb, exports CSV et JSON, validation des sauvegardes et hors ligne.
L’intégration Raccourcis, l’installation Safari et les téléchargements sur
iPhone nécessitent une vérification sur un appareil iOS réel.

FICHIERS
index.html : application et logique existante améliorée.
refined.css : nouvelle interface.
sw.js et manifest.webmanifest : installation et cache hors ligne.
icon-192.png et icon-512.png : icônes d’origine conservées.
