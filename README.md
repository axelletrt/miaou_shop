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
7. Coller le code dans initializer/stripe.rb que je t'enverrai aussi sur slack 
8. rails db:create, rails db:migrate, rails db:seed 
9. Rails server 

Features disponibles en local : 
-Front 

-Devise

-Création de compte 

- ActionMailer (Inscription et confirmation de commande après paiement)

-Création de panier, récapitulatif de panier, total de panier 

-Stripe



En production, "views" disponibles : 

https://meow-shop.herokuapp.com/
https://meow-shop.herokuapp.com/items/1
https://meow-shop.herokuapp.com/users/sign_up

Toutes les pages qui appellent devise ne fonctionnent pas :rage1:
