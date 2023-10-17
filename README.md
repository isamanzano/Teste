# Git Comandos - Documentação README  
  
Este README fornece uma breve documentação dos comandos mais comuns do Git. O Git é uma ferramenta para rastrear e gerenciar o histórico de um projeto de software, apresentando uma visão geral dos comandos essenciais.  
  
## Instalação do Git  
  
Primeiro, você precisa instalar o Git em seu sistema, podendo baixá-lo em [[git-scm.com](http://git-scm.com)]([https://git-scm.com/downloads](https://git-scm.com/downloads)) e seguir as instruções de instalação para o seu sistema.  
  
## Configuração Inicial  
  
Antes de iniciar o Git, configure-o com suas informações pessoais, como seu nome de usuário e endereço de e-mail, que serão registrados nos commits.  
  
>git config --global [user.name](http://user.name) "Seu Nome"  
git config --global user.email "seu@email.com"`  
  
## Iniciando um Repositório  
  
Para criar um novo repositório Git ou iniciar o controle de versão em um projeto existente, use o comando git init.  
  
  
>git init  
  
## Clonando um Repositório  
  
Para clonar um repositório Git existente, use o comando git clone e forneça a URL do repositório.  
  
  
>git clone URL_do_Repositório  
  
## Adicionando e Confirmar Mudanças  
  
O Git trabalha com um sistema de confirmações (commits) para rastrear mudanças no código, siga estas etapas para confirmar suas mudanças:  
  
1. Adicione as mudanças ao índice (staging area) com git add.  
  
  
> git add arquivo1 arquivo2  
  
2. Confirme as mudanças com um comentário descritivo.  
  
  
>git commit -m "Sua mensagem de commit aqui"  
  
  
## Verificando o Status  
  
Para verificar o status atual do seu repositório e ver as mudanças pendentes, use o comando git status.  
  
  
>git status  
  
## Ramificações (Branches)  
  
O Git permite que você trabalhe em diferentes ramos para desenvolver recursos separadamente. Aqui estão alguns comandos:  
  
- Criar um novo ramo:  
  
  
>git branch nome-do-ramo  
  
- Mudar para um ramo existente:  
  
> git checkout nome-do-ramo  
  
- Criar e mudar para um novo ramo:  
  
> git checkout -b nome-do-ramo  
  
- Listar todos os ramos:  
  
  
>git branch  
  
- Mesclar (merge) um ramo no ramo atual:  
  
  
> git merge nome-do-ramo  
  
  
## Sincronização com Repositórios Remotos  
  
Para trabalhar com repositórios remotos, use os seguintes comandos:  
  
- Adicionar um repositório remoto:  
  
  
> git remote add nome-do-remoto URL_do_Remoto  
  
- Obter as últimas alterações do repositório remoto:  
  
  
> git pull nome-do-remoto nome-do-ramo  
  
- Enviar (push) suas alterações para um repositório remoto:  
  
  
> git push nome-do-remoto nome-do-ramo  
  
  
## Conclusão  
  
Este README forneceu uma introdução aos comandos mais comuns do Git. O Git é uma ferramenta poderosa que oferece uma variedade de recursos avançados para controle de versão. 
  
Para obter mais informações sobre o Git e suas funcionalidades avançadas, você pode visitar o site oficial do Git [[git-scm.com](http://git-scm.com)]([https://git-scm.com/](https://git-scm.com/)).