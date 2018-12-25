# i3-config

## Installation des paquets

Divers paquets sont nécessaires, dont voici une liste de paquets à installer au préalable
* [Nitrogen](https://github.com/l3ib/nitrogen) : *Pour les fonds d'écrans.*
* [i3-gaps](https://github.com/Airblader/i3) : *Le WM (Windows Manager)*
* [Polybar](https://github.com/jaagr/polybar) : *La barre d'état*
* [rofi](https://github.com/DaveDavenport/rofi) : *Pour lancer les applications*
* [URxvt](http://software.schmorp.de/pkg/rxvt-unicode.html) : *L'émulateur de terminal*
* [scrot](https://github.com/dreamer/scrot) : *Pour les screenshots*
* [xclip](https://github.com/astrand/xclip) : *Pour copier les screenshot dans le presse-papier*
* [dunst](https://github.com/dunst-project/dunst) : *Pour afficher les notifications*

Des polices d'écritures sont elles aussi nécessaires :
* [Fira Code](https://www.archlinux.org/packages/community/any/ttf-fira-code/) : *Pour les icônes diverses sur la barre d'état*
* [Material Design Icons (git)](https://aur.archlinux.org/packages/ttf-material-design-icons-git/) : *Pour la barre d'état et l'émulateur de terminal*

## Ajouter les configurations
Après avoir au préalable installé les paquets demandés, vous pouvez copier les configurations dans les endroits pour :

- Le contenu de [`/config/i3`](https://github.com/orakless/i3-config/tree/low-config/configs/i3) va dans `~/.config/i3/`
- Le contenu de [`/config/polybar`](https://github.com/orakless/i3-config/tree/low-config/configs/polybar) va dans `~/.config/polybar/`
- Le contenu de [`/config/dunst`](https://github.com/orakless/i3-config/tree/low-config/configs/dunst) va dans `~/.config/dunst/`
- Le dossier [`/scripts`](https://github.com/orakless/i3-config/tree/low-config/scripts) et le fichier [`Xdefaults`](https://github.com/orakless/i3-config/blob/low-config/Xdefaults) vont dans votre home (`~/.scripts`et `~/.Xdefaults` au lieu de `/scripts`/`Xdefaults`)
- N'oubliez pas d'ajouter le point devant le fichier `Xdefaults` et le dossier `scripts` ! Sinon, ça ne fonctionnera pas.

## Rendu de la configuration (pas à jour!!)
![Rendu](https://github.com/orakless/i3-config/raw/low-config/rendu.png)
