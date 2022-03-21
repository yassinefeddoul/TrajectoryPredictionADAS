Le présent projet a pour objectif de tracker les objets mobiles afin de prédire leurs trajectoires.
Vous allez trouver dans le ci-joint un rapport résumant le travail effectué et ainsi notre réalisation pratique.
Dans le dossier Code_Prédiction vous trouverez tout les outils nécessaire pour tester le programme et le réalisé.
On s'est servi du transfert learning dans la première partie où vous allez trouvez 'weights' utilisé dans le dossier weights, si vous voulez refaire le travail, il faut transformer les weights en fichier .tf en extension par le code disponible dans le fichier convert weights to tf.ipynb sinon vous allez trouvé le fichier transformé dans le fichier weights.
Pour les fichiers disponible dans les dossiers deep_sort et tools sont des modules nécessaire à importer dans le code principal, ils doivent être dans le même dossier pour ne pas avoir des erreurs d'importation.
Dans le fichier code Prediction.ipynb vous allez trouver partie:
- Première Partie est consacré à la génération et la structuration des données pour entainer le modèle de prédiction où on a utiliser différents modèle SVR, MLP Regressor et la régression linéaire qu'on a enregisté.
- Deuxième Partie où on a implémenté la structuration des données pour prédire en temps réel les trajectoires des objets mobiles.
- Troisième Partie, on a connecté la caméra d'un téléphone à l'aide de son IP où on a assurer la possibilté de connecté n'importe quelle caméra avec notre algorithme pour soit réalisé le tracking en temps réel ou la prédiction en temps réél.

Réalisé Par:
FEDDOUL YASSINE
ECHCHERQAOUI OUSSAMA. 