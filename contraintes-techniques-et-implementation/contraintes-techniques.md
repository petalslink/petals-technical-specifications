# Contraintes Techniques

* L'application doit s'appuyer sur le guide [Material Design](https://material.io/design/) et respecter la charte graphique établie.
* L'application doit produire des pages HTML valides \(vérification W3C\).
* L'application doit intégrer une extension du CSS \(Sass\) pour simplifier et optimiser dans le mesure du possible un CSS complexe ou répétitif.
* L'application doit tourner sous Firefox et Chrome.
* Les interactions entre Petals et l'application se feront au travers de JMX.
* L'application doit être codée en Java pour le backend, en typescript pour le frontend.
* L'application ne nécessite pas de base de données pour l'environnement de développement ou de tests.
* L'application doit pouvoir être ajoutée à un serveur d'intégration continue \(Jenkins\).
* L'application doit pouvoir être testée de manière automatique \(Selenium ou équivalent\).

{% hint style="warning" %}
Ajouter contraintes de poids : application frontend servie + application installée \(back+front\) ? contraintes de performance ?
{% endhint %}

* La notion de session d'utilisation doit être supportée.
* Le support de la haute disponibilité n'a pas à être garanti.

Il n'est pas attendu que l'application puisse tourner sur un cluster de serveurs d'applications.  
En revanche, on tentera d'utiliser les solutions les plus simples et les plus courantes possibles pour réduire les développements à mettre en œuvre si ce besoin venait à venir.



#### Système cible :

* OS: Linux \(base Debian\)
* Packaging: archive zip, docker
* CPU: deux coeurs
* Mémoire: 2Go
* Estimation DB: ?

