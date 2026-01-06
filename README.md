# This is my config for NixOs using Gnome + Cosmic desktop environments
So I am using only configuration.nix

```sh
sudo su

```sh
 nixos-generate-config
``` nix-env git --install
``` git clone github.com/kevin-hw/nixos-config

- Here u need to delete generated configuration.nix
```sh cd /etc/nixos/
```sh rm -f configuration.nix

- Next, we need to move my config to the folder

```sh cd
```sh cd nixos-config/etc/nixos
```sh mw configuration.nix ~/etc/nixos

<h3 Build ur new DE>
```sh nixos-rebuild switch

#Congrats
