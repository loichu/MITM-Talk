# Résumé

## Présentation

**timing**: 20 minutes

* Qu'est-ce que la Man In The Middle Attack
* Clé assymétriques: petite énigme
* Comment fonctionne le HTTPS
* L'outil mitm-proxy


## Sénario de la démo

**timing**: 10 minutes

**Acteurs**
* Un client
* Routeur wifi original
* Routeur wifi mocké (avec CA de mitm-proxy)
* Proxy (raspi avec mitm-proxy)
* Attacker (spy on proxy)
* Server tequila

**Procédure**
Le client (Loïc) se connecte au réseau wifi du router mocké. Le router mocké
dirige son trafique vers le proxy. L'attaquant (Yoël) espionne le traffique
via le proxy. Le client se logue sur tequila et ne se doute de rien. L'attaquant
récupère son mot de passe. Le client remarque que le réseau est lent et en
inspectant le réseau il se rend compte de l'attaque. Mais c'est trop tard...
