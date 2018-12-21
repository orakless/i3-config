<div align="center"><img src="https://github.com/orakless/i3-config/raw/master/logo.png"/></div><br>

## Installation des paquets

Divers paquets sont nécessaires, dont voici une liste de paquets à installer au préalable
* [Nitrogen](https://github.com/l3ib/nitrogen) : *Pour les fonds d'écrans.*
* [i3-gaps](https://github.com/Airblader/i3) : *Le WM (Windows Manager)*
* [Compton](https://github.com/chjj/compton) : *Le compositeur d'écran*
* [Polybar](https://github.com/jaagr/polybar) : *La barre d'état*
* [rofi](https://github.com/DaveDavenport/rofi) : *Pour lancer les applications*
* [URxvt](http://software.schmorp.de/pkg/rxvt-unicode.html) : *L'émulateur de terminal*
* [gnome-screenshot](https://github.com/GNOME/gnome-screenshot) : *Pour les screenshots*

Des polices d'écritures sont elles aussi nécessaires :
* [Font Awesome](https://fontawesome.com/) : *Pour les icônes diverses sur la barre d'état*
* [Ubuntu Font Family](https://design.ubuntu.com/font/) : *Pour la barre d'état et l'émulateur de terminal*
* [Font Logos](https://github.com/lukas-w/font-logos) : *Pour le logo Tux sur la barre d'état*
## Ajouter les configurations
Après avoir au préalable installé les paquets demandés, vous pouvez copier les configurations dans les endroits pour :

- Le contenu de [`/config/i3`](https://github.com/orakless/i3-config/tree/master/configs/i3) va dans `~/.config/i3/`
- Le contenu de [`/config/polybar`](https://github.com/orakless/i3-config/tree/master/configs/polybar) va dans `~/.config/polybar/`
- Le dossier [`/scripts`](https://github.com/orakless/i3-config/tree/master/scripts) et le fichier [`Xdefaults`](https://github.com/orakless/i3-config/blob/master/Xdefaults) vont dans votre home (`~/.scripts`et `~/.Xdefaults` au lieu de `/scripts`/`Xdefaults`)
- N'oubliez pas d'ajouter le point devant le fichier `Xdefaults` et le dossier `scripts` ! Sinon, ça ne fonctionnera pas.
## Conseil
- Ajoutez un fond d'écran le plus rapidement possible, sinon URxvt affichera un fond blanc, ce qui rendra le texte peu lisible

## Rendu de la configuration
![Rendu](https://github.com/orakless/i3-config/raw/master/rendu.png)
