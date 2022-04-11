# Ferramentas Desktop Linux

Este repositório contem script para automatizar a preparação de um desktop Linux


> **_Disclaimer_** :  
> Este script é para o SO ubuntu version 20.04+, para outras distribuições você deve adaptar.
___

## Preparando Desktop

> Leia o  `update_install_apps.yml` o arquivo antes de aplicar.

1. Instalação do Ansible, Unzip e Git
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
2. Clone do repositorio
```bash
git clone git@github.com:dudures/ferramentas_ansible.git
```

3. Aplicando as configurações
```bash
ansible-playbook update_install_apps.yml --ask-become-pass
```
>Insira sua senha quando forsolicitada.
___

# License
GPLv3

# Informação sobre:
Adaptador por [Eduardo Brito](https://github.com/dudures)

Contribuições são bem vindas!
