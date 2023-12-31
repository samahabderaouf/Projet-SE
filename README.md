# Projet-SE
On veut effectuer en parallèle(En utilisant le modèle producteurs/consommateur) le produit de deux matrices: B (n1* m1) et C (n2 * m2) ⇒ la matrice résultante A=B*C ;

Les matrices sont remplis par des valeurs aléatoires

Les résultats intermédiaires seront placés dans un tampon de taille “T[N]”.

Chaque threads producteurs calcule une ligne de la matrice résultante A et range les résultat dans le tampon T

Les threads consommateurs consomment l'élément T[y] le place dans la matrice résultante A au bon emplacement!

q1: Quelles sont les structures de données à utiliser ?
Utilisez des tableaux pour stocker les matrices B, C et le tampon T.
q2: Comment allez-vous protéger l'accès à ces données?
Protégez l'accès aux données en utilisant des verrous (locks) ou des sémaphores pour synchroniser l'accès aux structures de données partagées.
q3- quels sont les risques?
Les risques incluent la perte de données, les erreurs de calcul, les problèmes de synchronisation et les violations de la vie privée. Pour les minimiser, mettez en place des mesures de sécurité, vérifiez les calculs et respectez les réglementations sur la protection des données.
