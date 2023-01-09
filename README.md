# cours_nouvelle_techno
Apprendre Symfony 5.1 avec les vidéos YouTube de Nouvelle_techno

Si vous utilisez Linux et MampPro, un htaccess sera nécessaire dans votre dossier public

Télécharger MailerHog / MailDev pour simuler les envois d'email : 
https://nouvelle-techno.fr/articles/installer-et-utiliser-mailhog-et-maildev

Pour utiliser MailDev :
il y a la possibilité d'installer Encore pour avoir npm : 
composer require symfony/webpack-encore-bundle
npm install
sudo npm install -g maildev
maildev

En cas d'erreur lors des tests d'envoi, essayez :
maildev --hide-extensions STARTTLS

La vérification d'email :
composer require symfonycasts/verify-email-bundle 


