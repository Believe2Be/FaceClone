= Faceclone =

== Features ==

* Publier des messages en public
* Inscription
* Devenir ami avec quelqu'un
* Envoyer un MP à un ami

== MCD ==

===Table Membre===

* __ID/nom user unique__
* Nom
* Prenom
* Mail
* Date de Naissance
* MDP
* Date d'inscription
* Date de dernière connexion

=== Table message/Post ===

* __ID message__
* ID membre
* Contenu message (markdown pour le formattage)
* Date message


=== Commentaires ===

* __ID Commentaire__
* ID Membre
* Contenu commentaire
* Date commentaire

=== Messages privés ===

* __ID message__
* ID conversation
* Contenu message (markdown pour le formattage)
* Date message

=== Conversation ===

* __ID conversation__
* ID membre origine
* ID membre destinataire