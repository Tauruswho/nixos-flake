# nixos-flake
Nixos with flake configuration files
My First go at getting flakes going on nixos, seems to work...
This is very basic just to get started..
20240203....
To update and upgrade the system you now first have to update the lock file "flake.lock" in /etc/nixos/
with:- "sudo nix flake update" then run "sudo nixos-rebuild switch" or 
(sudo nixos-rebuild switch --flake ./path to flake.nix)
