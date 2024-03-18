# homelab-ansible
Ansible configurations used for my homelab. Maybe 'homelab' is a stretch...

Characters:
- tkk-laptop 
    - ASUS VivoBook 
    - Ryzen 3 3250U - 4 @ 2.6GHz 
    - 6GB RAM
    - Fedora w/ KDE
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

Most of these roles and playbooks are assumed to be ran from either tkk-laptop or tkk-office to configure singed and any containers or virtuals which live on singed.

FAQ
- Why singed? 
  - I have played League of Legends long enough to become the villain. https://www.leagueoflegends.com/en-pl/champions/singed/
