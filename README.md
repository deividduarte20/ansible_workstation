# Ferramentas para estação de trabalho Linux (Ubuntu e derivados)

Os scripts foram utilizados no ubuntu e funciona em distribuições derivadas
___

## Preparo da estação de trabalho

> Leia o arquivo antes de aplicar e tenha certeza que entendeu tudo que será feito

1. Instale Ansible e o Git
```bash
sudo apt update && sudo apt install ansible git -y
```
2. Clone o repositorio
```bash
git clone https://github.com/deividduarte20/ansible_workstation.git
```
3. Entre no diretório
```bash
cd ansible_workstation 
```
4. Aplique a configuração
```bash
ansible-playbook packages.yml --ask-become-pass
```

>Digite a senha do usuário root para executar a playbook
___

Pacotes que serão instalados:
- vim
- htop
- tree
- copyq
- snapd
- gdebi
- remmina
- flameshot
- vagrant
- vscode
- vscode extensions
- tilix
- anydesk
- virtualbox
- teamviewer
- awscli
- docker

Espero que tenha gostado, caso tenha alguma sugestão de melhoria favor entrar em contato, as informações para contato se encontram na página principal do github.

