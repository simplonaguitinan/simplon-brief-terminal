Brief

# Terminal Cheat Sheet

## Navigation dans le système de fichiers

- `pwd` : Affiche le répertoire de travail actuel.
- `ls` : Liste les fichiers et répertoires dans le répertoire courant.
- `cd` : Change de répertoire (par exemple, `cd /chemin/vers/repertoire`).
- `tail` : Affiche les -n dernières lignes d'un fichier texte.

## Manipulation de fichiers et de répertoires

- `touch fichier` : Crée un nouveau fichier vide.
- `mkdir dossier` : Crée un nouveau répertoire.
- `cp source destination` : Copie des fichiers ou des répertoires.
- `mv source destination` : Déplace ou renomme des fichiers ou des répertoires.
- `rm fichier` : Supprime un fichier (avec précaution).
- `rm -r dossier` : Supprime un répertoire et son contenu (avec précaution).

## Installation et paramétrage de ZSH

Zsh est un interpréteur de commandes (shell), tout comme bash. Il fournit une interface entre l'utilisateur et le système. Il est indispensable d'avoir un interpréteur de commandes pour utiliser un système GNU/Linux (et même tous les autres systèmes). Le shell par défaut dans Ubuntu est bash, c'est un shell qui a bien des avantages (notamment pour les scripts), mais il est assez limité dans certaines fonctionnalités comme l'autocomplétion. Zsh est plutôt orienté pour l'interactivité avec l'utilisateur.

### Installation (sous Ubuntu)

```
$ sudo apt install zsh
```

### Paramétrage

Pour définir zsh comme shell par défaut, exécuter la commande suivante :

```
$ chsh
```

Pour définir le shell à utiliser, répondre `/bin/zsh`. Fermer puis ouvrir à nouveau un terminal pour être directement sous zsh.
