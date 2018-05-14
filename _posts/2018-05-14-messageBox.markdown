---
title: "MessageBox"
---
## Utilisation
MessageBox s'utilise pour demander à l'utilisateur de confirmer un choix, comme lorsqu'il veut supprimer quelque chose,

## La méthode MessageBox.Show()
Prend quatre paramètres, le premier est le message à affichier, le deuxièmes est le titre de la boite de dialogue, le troisième est les buttons,
le quatrième est l'icone.

{% highlight csharp %}
// MessageBox
DialogResult rep = MessageBox.Show("vous voulez quiter le programe?", "fermeture", MessageBoxButtons.YesNo, MessageBoxIcon.Question);
if (rep == DialogResult.Yes)
{
  // Quitter le programme
  Application.Exit();	
}
{% endhighlight %}

## Les valeurs disponnibles du MessageBoxButtons 
Nom du membre |	Description
--- | ---
AbortRetryIgnore | La boîte de message contient les boutons Abandonner, réessayer et ignorer.
OK | La boîte de message contient un bouton OK.
OKCancel | La boîte de message contient les boutons OK et Annuler.
RetryCancel | La boîte de message contient les boutons Réessayer et Annuler.
YesNo | La boîte de message ne contient les boutons Oui et.
YesNoCancel | La boîte de message contient Oui, non et Annuler boutons.

## Les valeurs disponibles du MessageBoxIcons
Nom du membre | Description
--- | ---
Asterisk | La boîte de message contient un symbole constitué d’une lettre minuscule « i » dans un cercle.
Error | La boîte de message contient un symbole constitué d’un X blanc dans un cercle sur fond rouge.
Exclamation | La boîte de message contient un symbole constitué d’un point d’exclamation dans un triangle sur fond jaune.
Hand | La boîte de message contient un symbole constitué d’un X blanc dans un cercle sur fond rouge.
Information | La boîte de message contient un symbole constitué d’une lettre minuscule « i » dans un cercle.
None | La boîte de message ne contient pas de symboles.
Question | La boîte de message contient un symbole constitué d’un point d’interrogation dans un cercle. 
Stop | La boîte de message contient un symbole constitué d’un X blanc dans un cercle sur fond rouge.
Warning | La boîte de message contient un symbole constitué d’un point d’exclamation dans un triangle sur fond jaune.