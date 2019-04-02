# Design System

Découvrez le design system du Département : https://departement-loire-atlantique.github.io/design-system-web/

## Contribution

1. Installer [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
2. Dans une console, installer Ruby bundler : `gem install bundler`
3. Dans une console, récupérer le code du projet : `git clone https://github.com/departement-loire-atlantique/design-system-web`
3. Dans une console, installer les dépendances : `bundle install` (ou `bundle update` pour une mise à jour)
4. Dans une console, lancer le mode développement : `bundle exec jekyll serve` 
5. Ouvrir le navigateur à l'addresse `http://localhost:4000/design-system-web/` pour voir le site (mise à jour automatique au fil et à mesure de l'édition des fichiers).

Attention, au Département de Loire Atlantique, l'installation est bloquée, il faut donc :

```bash
set http_proxy=http://MajMaven:Sv56jgc4@proxy-ng.cg44.fr:8080
set https_proxy=http://MajMaven:Sv56jgc4@proxy-ng.cg44.fr:8080
gem sources -r https://rubygems.org/
gem sources -a http://rubygems.org/
ridk install > Choisir 3 puis rien
http://repo.msys2.org/distrib/x86_64/msys2-x86_64-20180531.exe
A installer dans C:\msys64
```

## License

Ce projet est basé sur un [modèle de site design-system](https://github.com/lundegaard/design-system-template) et est rendu sous public en open source suivant les termes de la licence [MIT License](https://opensource.org/licenses/MIT).
