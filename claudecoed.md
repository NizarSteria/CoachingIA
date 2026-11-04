# Installer Claude Code

Claude Code existe en trois versions qui partagent le même moteur : 
dans le terminal, dans VS Code (extension) et dans l'application de bureau Claude. 
Pour ce projet, je recommande VS Code : 
tu vois tes fichiers d'agents à gauche et tu parles à Claude à droite. Je te montre l'installation pas à pas 

La vidéo ne se charge pas ? Ouvre-la ici → loom.com/share/96785cd2…

La version terminal, en une commande :

curl -fsSL https://claude.ai/install.sh | bash

Tu préfères Homebrew sur Mac ? brew install --cask claude-code.
Attention : cette version ne se met pas à jour toute seule, il faudra lancer brew upgrade claude-code de temps en temps.
L'installeur officiel, lui, se met à jour automatiquement.

Il te faut un abonnement payant. Pro, Max, Team ou Enterprise, ou un compte Console (API). Le plan gratuit de Claude ne donne pas accès à Claude Code.
Système. macOS 13 ou plus récent, Windows 10 (1809) ou plus récent, Ubuntu 20.04+ / Debian 10+. 4 Go de RAM.
Premier lancement. Crée un dossier pour ton entreprise, ouvre un terminal dedans et tape claude. Il te demande de te connecter avec ton compte Claude dans le navigateur. C'est tout.
