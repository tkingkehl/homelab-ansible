# homelab-ansible
Ansible configurations used for my homelab. Maybe 'homelab' is a stretch...

Characters:
- tkk-laptop 
    - ASUS VivoBook 
    - Ryzen 3 3250U - 4 @ 2.6GHz 
    - 6GB RAM
    - Rocky 9 w/ KDE
- tkk-office (desktop) 
    - Custom built desktop
    - Ryzen 5 1600x - 6 @ 3.6GHz
    - 16GB RAM
    - Fedora w/ KDE
- singed (server)
    - Lenovo M73 Tiny
    - Intel i5-4570T - 4 @ 3.6GHz
    - 16GB RAM
    - Rocky 9
- mortarion (server)
  - Dell Optiplex  9020
  - Intel i3-4160T - 4 @ 3.10GHz
  - 8GB RAM
  - Rocky 9
- tkk-pi-zero 
  - Raspberry Pi Zero 2 W
  - 1GHz
  - 512MB RAM
  - Debian 12 (Bookworm)

Most of these roles and playbooks are assumed to be ran from either tkk-laptop or tkk-office to configure singed and any containers or virtuals which live on singed.

FAQ
- Why singed? 
  - I have played League of Legends long enough to become the villain. https://www.leagueoflegends.com/en-pl/champions/singed/
- Why Mortarion?
  - I also like the Death Gaurd from Warhammer 40k. https://wahapedia.ru/wh40k10ed/factions/death-guard/Mortarion
