# This is my config for NixOs using Gnome + Cosmic desktop environments
So I am using only configuration.nix

`` sudo su
`` nixos-generate-config
`` nix-env git --install
`` git clone github.com/kevin-hw/nixos-config

<h3 Here u need to delete generated configuration.nix>
`` cd /etc/nixos/
`` rm -f configuration.nix

<h3 Next, we need to move my config to the folder>

`` cd
`` cd nixos-config/etc/nixos
`` mw configuration.nix ~/etc/nixos

<h3 Build ur new DE>
`` nixos-rebuild switch

#Congrats
