# <font color=b>Table des matières</font>

* <font color=b>Introduction</font>
    
    
* <font color=b>1. Phase d'émission</font>
    
    * <font color=b>1.1 Conversion du message en ascii puis en binare</font>    
    * <font color=b>1.2 Création du bit de parité</font>    
    * <font color=b>1.3 Création de la trame</font>    
    * <font color=b>1.4 Création du controle de redondance cyclique</font>  
    * <font color=b>1.5 Encodage de la trame avec le manchester</font>  
    * <font color=b>1.6 Modulation au choix ASK ou FSK</font>  

* <font color=b>2. Phase de réception</font>
    
    * <font color=b>2.1 Filtrage du signal recu par un filtre passe-bande</font>    
    * <font color=b>2.2 Démodulation ASK ou FSK</font>    
    * <font color=b>2.3 Décodage du signal en manchester</font>    
    * <font color=b>2.4 Récupération de la trame après décodage</font>  
    * <font color=b>2.5 Controle de redondance cyclique à la réception</font>  
    * <font color=b>2.6 Récupération du message de la trame</font> 
    * <font color=b>2.7 Vérification de l'intégriter du message avec le bit de parité</font> 
    * <font color=b>2.8 Conversion du message binaire en chaine de caractère</font> 

## <font color=b>**Introduction**</font>
    
### <font color=b>**Contexte**</font>   
Après avoir localisé __l'organisation de cyber pirate__ du web à l'aide de signaux réseaux, __l'agent K57__ infiltré est resté bloqué dans la salle d’audioconférence, n'ayant à sa disposition qu'un __microphone__ branché au système d'audioconférence uniquement connecté au réseau lors de l'utilisation de la salle. Nous devons à tout prix prendre contact avec lui à l'aide de son __pad miniature spécial espion__, afin qu'il puisse récupérer les données de l'organisation de cybercriminalité, qui seront directement captés par le micro et envoyés dans le réseau.  

Pour cela, l'agent K57 doit nous véhiculer un message en toute discrétion à l'aide d'un __signal non audible__. Le pad est capable d’émettre un signal à des __hautes fréquences__ contenant les informations à transmettre. Lorsque le message est reçu à l’agence, il doit être traité afin de __décrypter__ le message codé. Ainsi, nous devons donc réaliser le __filtrage d'un signal numériquement__.
    
### <font color=b>**Livrables attendus**</font> 
Il est attendu que nous créons le programme de toutes les manipulations du signal en Python pour simuler la communication et démontrer la faisabilité de notre solution, c’est-à-dire de comment évolue le signal émis par l’agent et comment il est véhiculé. 

    
---
