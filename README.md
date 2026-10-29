# classe1-symfony-7.4-LTS

Installation de Symfony dans l'environnement de développement sous Windows

## Installation Symfony 7.4 LTS

Version LTS (Long Term Support) de Symfony 7.4 en date du 29/10/2026

Avec 2 ans de support et 3 ans de support de sécurité :

https://endoflife.date/symfony

## Ressources

### Dernier version de PHP

Via :

https://wampserver.aviatechno.net/

- on prend la version updatable 

https://getcomposer.org/


https://symfony.com/

### Installation

#### Sous Windows:

Installez composer :
- https://getcomposer.org/download/

installer scoop
- https://scoop.sh/

puis installez symfony
- https://symfony.com/download


### Vous devez obtenir :
        php -v
        composer self-update
        symfony

### Vérification
        symfony check:requirements
        symfony.exe server:ca:install

### Création du premier projet LTS webapp

        symfony new FirstLTS --version=lts --webapp

        symfony serve -d

        symfony check:security
    

### Création d'un contrôleur

        php bin/console make:controller
