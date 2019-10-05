# Answers

Nom : Drogou
Prénom : Benoit

# 1.
**Citez deux avantages du PaaS sur le IaaS ?**
> Ne pas s'occuper de la maintenance des serveurs
> Ne pas gérer l'installation des applications et de leurs paramétrages.

# 2.
**Quelle est la différence entre le PaaS et le Serverless ?**
> Les 2 principales sont au niveau du l'autoscaling et du pricing. Le PaaS l'application doit être bine configurée pour autoscaler, aucune manipluation n'est requise en serverless. Le Scalling se fait automatiquement.
Pour ce qui est du pricing, en Serverless on ne paye que ce qui a été consommé. En PaaS on va payer le nombre de server qui va être utilisés. 

# 3.
**Que veut dire Serverless ?**
> Le Serverless est un model d'architecture cloud dans lequel le provider (awz, Microsoft Azure, Google cloud platform, Alibaba cloud ...) fait tournerle server et gère dynamiquement les ressources des machines virtuelles. 

# 4.
**Citez les trois propriétés désirable du Serverless ?**
> 1. Ephémère: La plaforme n'instancie que les fonctions à la demande, ces dernières ne "vivent" que le temps de délivrer leur résultat.
> 2. Scalabilité dynamique: L'auto-scaling permet de scaler automatiquement le nombre de serveurs, ressources affin de supporter la charge. Ceci sont que les développeurs n'aient eux à paramétrer quoi que ce soit.
> 3. gestion fine du paiement: On ne paie que ce que l'on consomme 

# 5.
**Comment s'appelle la plus petite unité de compute déployable en Serverless ?**
> Le Function a sa Service

> Les fonctions sont les plus petites unitées. Comme les 3 propriétés sitées ci dessus, une fonction est éphémère (son life cycle ne dure qu ele temps de la requête), Scalable (la plateforme pourra supporter la charge si elle augmente) et la facturation est faire au nombre d'appel à la fonction
