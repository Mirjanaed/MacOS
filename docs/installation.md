#  Installation Rapide (MacBook Air 2013)

Voici les commandes essentielles à copier-coller dans votre terminal pour configurer l'environnement.

##  1. Outils de base (Homebrew & Git)
```bash
/bin/bash -c "$(curl -fsSL 
[https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh](https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh))"
brew install git tree python

brew install miniforge
conda init zsh
# Fermer et rouvrir le terminal
conda create -n sig gdal python=3.12 -y
conda activate sig

git config --global user.email ""
git config --global user.name ""


