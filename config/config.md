# Re-Install Sytem

## Activation de TRIM pour les SSD

La fonction TRIM pour les SSD est activée sur les macs équipés à l'origine d'un SSD. Si un changement de disque à été effectué :
* Dans le terminal : `sudo trimforce enable` ;
* L'ordinateur reboot.

## Personnalisation du terminal Mac

### Personnalisation du profil

* Charger le profil : `terminalMac.terminal`

### Personnalisation du prompt

Créer un symlink à partir de /tips/config/.bash_profile
* Dans le terminal : `ln -s /Volumes/data/Github/tips/config/.bash_profile .bash_profile` ;
* puis : `source .bash_profile`

### Modification du hostName

* Dans le terminal : `sudo scutil –-set HostName nouveauHostName`

## Logiciels

### Navigateurs
* [firefox](https://www.mozilla.org/fr/firefox/new/)
* [chrome](https://www.google.fr/chrome/browser/desktop/)

### Editeurs de texte

#### Atom.io

[télécharger Atom](https://atom.io/)

##### Packages

* [Sublime-Style-Column-Selection](https://atom.io/packages/Sublime-Style-Column-Selection)
* [atom-beautify](https://atom.io/packages/atom-beautify)
* [atom-wrap-in-tag](https://atom.io/packages/atom-wrap-in-tag)
* [autoclose-html](https://atom.io/packages/autoclose-html)
* [highlight-selected](https://atom.io/packages/highlight-selected)
* [lipsum](https://atom.io/packages/lipsum)
* [markdown-pdf](https://atom.io/packages/markdown-pdf)
* [minimap](https://atom.io/packages/minimap)
* [pigments](https://atom.io/packages/pigments)
* [todo-show](https://atom.io/packages/todo-show)

##### Interface

TODO

#### Oxygen XML editor
##### Interface
* Télécharger [Oxygen](https://www.oxygenxml.com/) ;
* dans le menu préférences/apparence : importer `oxygenTheme`
### Dev

#### Git

* Télécharger [git](https://git-scm.com/) ;
* dans le terminal : `git config --global user.name "Nom d'utilisateur"` ;
* puis : `git config --global user.email adresse@mail` ;
* pour configurer l'éditeur de texte par défaut : `git config --global core.editor atom` ;
* pour choisir l'outil de différence (en cas de conflit) : `git config --global merge.tool vimdiff`