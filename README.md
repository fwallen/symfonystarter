#Symfony Starter
##A base Symfony 5 project with Docker
###Installing:
1. Clone from git@github.com:fwallen/symfonystarter.git
1. Execute `docker-compose build`
1. Execute `docker-compose up -d`
1. Execute `docker-compose exec php composer install` to install dependencies.

To see the installed bundles:
`docker-compose php bin\console debug:config`

To see the autowired service:
`docker-compose php bin\console debug:autowiring --all`


This Repo: [https://github.com/fwallen/symfonystarter](https://github.com/fwallen/symfonystarter)

Symfony Documentation: [https://symfony.com/doc/current/index.html](https://symfony.com/doc/current/index.html)