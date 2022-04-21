# Projet 08 - DEPLOYER UN MODELE DANS LE CLOUD


<u>__Contexte__</u><br>
Notre strat-up « **Fruits!** », évoluant dans le domaine de l'Agri-Tech, propose des solutions innovantes pour la récolte des fruits.

<u>__Enjeux__</u><br>
- Préserver la biodiversité des fruits signifie **appliquer des traitements spécifiques pour chaque espèce de fruit**. 
- Notre strat_up « Fruits! » souhaite alors développer des __*robots cueilleurs intelligents*__, capables de **reconnaître (après une analyse visuelle) chaque classe de fruits rencontrée**.

<u>__Objectifs__</u><br>
- Développer, dans un environnement Big Data (i.e. Cloud), une première chaîne de traitement des données (relative à l'analyse des images des fruits) qui comprendra le **preprocessing** et une étape de **réduction de dimension**.
- Mettre à disposition dans le Cloud (i.e. S3), les premières briques de traitement indispensables (features des images de fruits) pour passer à l’échelle en termes de volume de données à traiter.
- Le modèle de Classification Multiclasses des images de fruits est **hors-scope**.
                                                                                                          
<u>**Typologie du problème**</u>
- **Classification Multiclasses**
- **Chaîne de traitement des données : pré-processing + réduction de dimension**
- **Architecture Big Data** dans le Cloud (i.e. AWS) : **EC2 / SageMaker + IAM + S3**.

---
