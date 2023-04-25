# Log linear Model 

Il s'agit d'un projet de 2ème année de l'ENSAE Paris dans le cadre du cours de $\textbf{Simulations and Monte Carlo}$

Les Log-linear models s'appliquent à un vecteur prenant ses valeurs dans $\{0,1\}^d$.
La probabilité d'observer un certian x est telle que (pour un modèle restraint à un ordre 2 d'intéractions) :

> $ log P(X=x) = \alpha + \sum_{i=1}^n \beta_i x_i + \sum_{i<j}^n \gamma_{ij} x_i x_j $ 


- La question 1. s'intéresse à générer des données à partir des paramètres $\beta$ et $\gamma$ fixés. 
- Les questions suivantes, quant à elles, s'intéressent au fait de remonter aux paramètres étant donnée une distribution. 

$\textit{Charles Rollet, Alexandre Partensky et Corentin Pernot } $ 

Sources: 
> $\textit{ Cours de Monte Carlo, N.Chopin}$

> $\textit{ MCMC for doubly-intractable distributions, I.Murray Z.Ghahramani D.J.C.MacKay}$ 
https://mlg.eng.cam.ac.uk/zoubin/papers/doubly_intractable.pdf

> $\textit{Computational Statistics, T. Donœux} $   
 https://www.hds.utc.fr/~tdenoeux/dokuwiki/_media/en/mcmc_slides.pdf  
