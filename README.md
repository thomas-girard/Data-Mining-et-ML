# Data-Mining-et-ML


## Question 1
Il y a 89418 instances et 41 features (41 features + 1 colonne de label, soit 42 au total). Le "N" signifie "numeric" (valeurs numériques continues) et le "C" "categorical" (valeurs discrètes). L'attribut "label" permet de dire 
si la ligne est issue d'une attaque ou bien si elle est normale. 

## Question 2

La classe "normale" est majoritaire. En ce qui concerne les attaques, DOS est largement majoritaire dans notre jeu de données et c'est également ce qui est le cas sur internet. 
Cependant ce dataset n'est pas représentatif des attaques sur internet en 2021 car il manque notamment des types d'attaques comme les injections SQL...

## Question 3

La valeur "SO" de attribut "flag" est majoritairement liée aux attaques DOS. 
La valeur 1 de "dst_host_srv_serror_rate" est lié aux attaques DOS. 
La valeur 500 de "srv_count" est liée aux attaques DOS. 

## Question 4
Les 5 attributs les plus corrélées d'après "Gini" sont : 
1. flag
2. servor_rate
3. dst_host_serror_rate
4. dst_host_srv_serror_rate
5. srv_serror_rate

## Question 5 

Par exemple, prenons l'attribut "flag". On avait déjà vu dans la question 3 que sa valeur "SO" était liée aux attaques DOS

## Question 6 

(Penser à décocher la case "induce binary tree" de Tree). 

## Question 7 

* Arbre : 

	- Avec les règles aprises :  on a probe à 97 % avec "dst_host_srv_rerror_rate >=01 AND service=other"
	- Avec l'arbre de décision : on a probe à 10% avec la valeur "OTH" du flag

* KNN : 

* Random Forest : 

* CN2 Rule Induction :








 
