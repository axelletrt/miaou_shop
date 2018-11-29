Hello :heart:


Membres du groupe : 

@Charlotte Houivet
@Shayane Yakataly
@Cyril Avronsart
@Olivier Rohellec 
@axelle trt 


Installation en Local: :sparkles:

1. Git clone 
2. sudo bundle install 
3. Supprimer credentials.ymlc 
4. Lancer la commande EDITOR=vim rails credentials:edit
5. Copier/coller les credentials que je te t'envoie en message sur slack 
6. Sauvegarder le fichier credentials 
7. Dé-commenter le code qui est dans initializer/stripe.rb et enregistrer. 
8. rails db:create, rails db:migrate, rails db:seed 
9. Rails server 

Features disponibles en local : 

- Front 

- Devise

- Création de compte 

- ActionMailer (Inscription et confirmation de commande après paiement)

- Création de panier, récapitulatif de panier, total de panier 

- Stripe


Projet en production : https://miaoumiaou.herokuapp.com/


Attention, le Action Mailer et Stripe fonctionnent uniquement en Developpement et non en production:rage1:
