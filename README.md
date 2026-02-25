My one-repo OS/apps config

Run

```sh
sudo cp -r * /etc/nixos/ && \
sudo nixos-rebuild switch && \
home-manager switch -f /etc/nixos/home.nix --flake /etc/nixos/
``
```
