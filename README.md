# Ferramentas para estação de trabalho Linux (Ubuntu e derivados)

Os scripts foram utilizados no ubuntu e funciona em distribuições derivadas
___

## Preparo da estação de trabalho

> Leia atentamente os passos a serem executados

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
4. Caso queira testar a playbook antes de executar
```bash
ansible-playbook packages.yml --ask-become-pass --syntax-check 
```

5. Aplique a configuração
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
- python3-pip
- flameshot
- curl
- vagrant
- vscode
- gzip
- tilix
- anydesk
- virtualbox
- Free download manager
- awscli
- docker
- helm
- terraform
- eksctl
- kubectl
- ssh

Espero que tenha gostado, caso tenha alguma sugestão de melhoria favor entrar em contato ou criar uma issue, as informações para contato se encontram na página principal do github.

