# QPE-noe_MATHIEU

Bonjour, voici mon DM pour Noé MATHIEU

Etude théorique:

Pour réaliser l'étude théorique de l'estimation de phase, nous devons calculer la valeur théorique de l'erreur d'estimation |ϕ̂ - ϕ|.

Dans l'estimation de phase l'erreur de phase |ϕ̂ - ϕ| dépend du nombre de bits de précision n. L'erreur est proportionnelle à 1/(2^n). Donc quand n augmente l'erreur d'estimation diminue exponentiellement.
L'erreur théorique de l'estimation de phase peut être exprimée comme :
|ϕ̂ - ϕ| ≤ c/(2^n)
où c depent de la précision et du nombre de mesures.

Pour obtenir une précision de l'ordre de 1/N en classique il faudrait N échantillons. En quantique une précision de l'ordre de 1/(2^n) est obtenue avec n qubits c'est donc exponentiellement plus efficace.

Cela correspond bien aux résultats empiriques ou on peut voir que l'erreur diminue de manière exponentielle.
