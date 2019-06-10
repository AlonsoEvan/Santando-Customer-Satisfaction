# Santando-Customer-Satisfaction
Kaggle Project

Which customers are happy customers?

From frontline support teams to C-suites, customer satisfaction is a key measure of success. Unhappy customers don't stick around. What's more, unhappy customers rarely voice their dissatisfaction before leaving. Santander Bank is asking Kagglers to help them identify dissatisfied customers early in their relationship. Doing so would allow Santander to take proactive steps to improve a customer's happiness before it's too late. In this competition, you'll work with hundreds of anonymized features to predict if a customer is satisfied or dissatisfied with their banking experience.

Link: https://www.kaggle.com/c/santander-customer-satisfaction/overview

Le but étant réaliser un score sur une population de la Bancassurance Santander permettant d'identifier les personnes susceptibles d'exprimer leur insatisfaction et donc être susceptible de quitter la banque.

Beaucoup de travail sur le fichier avec notamment la suppression des variables identiques, Creation d'une cross validation pour le Light GBM, Feature engineering (nombre de 0 par lignes etc...).

Meilleurs résultats obtenus: Public : 0.82892 Private : 0.81089
