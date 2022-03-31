# MetaUnivers



Il s’agit de développer une application web permettant à une communauté de cryptophiles
d'échanger sur les cryptomonnaies du métavers (https://cryptoast.fr/metaverse-comprendre-mondesvirtuels-blockchains-nfts/). Les membres de la communauté inscrits dans l'application peuvent créer
des annonces pour promouvoir des cryptomonnaies. Ils peuvent aussi émettre un avis sur les
différentes cryptomonnaies disponibles dans l'application

## Informations 

Les instructions ci-dessous vous permettront de déployer et utiliser facilement notre application sur une machine ne disposant pas  de Symfony et 
Composer.

### Prerequis 

une version Symfony 4.4 et  une version version 7.4.*

Installation sur Windows
```
 Pour une installation facile de PHP, de MySQL sur Windows installez Xampp  sur https://www.apachefriends.org/fr/download.html.
(a) Installation de Composer :
Télécharger et installer composer à partir de https://getcomposer.org/Composer-Setup.exe

(b) Installation de l'utilitaire Symfony :
Télécharger et installer l'utilitaire Symfony à partir de https://get.symfony.com/cli/setup.exe


```
Installation sur Mac OS 
```
Pour une installation facile de PHP, de MySQL  sur Mac OS installez Mamp sur https://www.mamp.info/en/downloads/. 
(a) Installation de Composer :
Exécuter les commandes suivantes dans un terminal :

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') ===
'756890a4488ce9024fc62c56153228907f1545c228516cbf63f885e036d37e9a59d27d63f46af1d4
d07ee0f76181c7d3') { echo 'Installer verified'; } else { echo 'Installer corrupt';
unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php --install-dir=/usr/local/bin --filename=composer
php -r "unlink('composer-setup.php');"

(b) Installation de Composer :
Exécuter les commandes suivantes dans un terminal :



curl -sS https://get.symfony.com/cli/installer | bash


```
### Installation sur  Mac OS :

Pour une installation facile de PHP, de MySQL installez Mamp sur https://www.mamp.info/en/downloads/. 


Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
