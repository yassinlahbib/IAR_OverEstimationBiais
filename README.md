# IAR_OverEstimationBiais

## Overestimation Bias

Dans ce projet, nous avons comparé la surestimation de la fonction de valeur Q(s, a) entre les algorithmes **DDPG** et **TD3**.  
Nous avons estimé cette valeur de manière empirique à l’aide de la **méthode de Monte Carlo**, ce qui permet d’obtenir une approximation plus précise de la valeur réelle attendue de Q(s, a). 
Ce qui nous permet de visualiser l'overstimation bias.

On évalue également les courbes d'apprentissage des 2 algorithmes afin de déterminé l'impact de l'overestimation.
