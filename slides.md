# MITM Attack
* Le principe

---

# Clés asymétriques

Au moyen âge, un espion est en mission dans un royaume éloigné à plusieurs jours de marche. Il doit envoyer à son roi des information confidentielles. Si quelqu'un intercepte le message, il se fait décapiter.

Comment procède-t-il ?

---

# HTTPS

Le protocole HTTPS est composé de deux parties :

  - Le protocole HTTP
  - Les certificats SSL

---

# Le protocole HTTP

## Introduction

Le protocole HTTP (HypetText Transfert Protocole) est un protocole de couche 7 qui permet transfert de fichiers (principalement des fichiers html, sous format de texte brut) accessibles par une chaine de caractères (URL).

---

# Le protocole HTTP

## Fonctionnement

Le fonctionnement du protocole est très simple, le client fait une **requête** au serveur et le serveur envoie une réponse au client.

---

# La requête http

Une **requête** http est composée de trois éléments :

  1. Une ligne requête (méthode + URL + version du protocole)
  1. Plusieurs lignes d'entête (le navigateur, le système d'exploitation, etc...)
  1. Un corps de requête (par exemple : données POST)

---

# La réponse http

Une **réponse** http est composée également de 3 éléments principaux :

  1. Une ligne de status (version du protocole + code + explication littérale du code)
  1. Plusieurs lignes d'entête (serveur, langue du document)
  1. le corps de la réponse contenant le document demandé

C'est bien joli tout ça, mais ça se passe comment lorsque l'on veut transférer des données sensibles ?

---

# Les certificats SSL



---

# mitm-proxy

* Open Source
* Customizable
