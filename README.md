# 🧭 Guia Definitivo de Desenvolvimento Back-end

> Repositório de comandos, anotações e recursos úteis para desenvolvedores back-end.

---

## ✍️ Introdução

Bem-vindo ao meu guia pessoal de desenvolvimento back-end!  

Aqui você encontrará:

- 📌 Comandos Git e GitHub comentados
- 🐍 Scripts e comandos úteis em Python
- 🔗 Links de referência e boas práticas
- ⚙️ Ferramentas e recursos para produtividade
- 📚 Anotações sobre conceitos importantes

> Este repositório evolui com o tempo, acompanhando meu aprendizado e experiência como programador.

---
## 🧾 Menu
- [Lista de Comandos](#lista-de-comandos)
- [Documentação](#documentação)
- [Referências](#referências)
- [Links Úteis](#links-úteis)

## Lista de Comandos

- [Comandos Gerais](#comandos-gerais)
- [Criação e Navegação Entre Pastas e Arquivos](#criação-e-navegação-entre-pastas-e-arquivos)
- [Cadastro](#cadastro )
- [Configuração e Manipulação de Branchs](#configuração-e-manipulação-de-branchs)
- [Criação e Clonagem de Repositórios](#criação-e-clonagem-de-repositórios)
- [Commits](#commits)
- [Github](#github)

---

### Comandos Gerais
- `git status` (Mostrar o status da árvore de trabalho)
- `ls` (Listar)
---

### CRIAÇÃO E NAVEGAÇÃO ENTRE PASTAS E ARQUIVOS
- `mkdir nome-da-pasta` (Criar pasta)  
- `rmdir nome-da-pasta` (Excluir pasta)  
- `cd nome-da-pasta/` (Entrar na pasta)  
- `touch nome-do-arquivo` (Criar arquivo)  
- `cd nome-do-arquivo` (Entrar no arquivo)  
- `cd ..` (Sair do arquivo ou pasta)  
- `echo "Primeira linha do arquivo" > nome-arquivo.txt` (Cria um arquivo com conteúdo ou sobrescreve um já criado)  
- `echo "Nova linha" >> nome-arquivo.txt` (Adiciona conteúdo no final de um arquivo já criado)

---

### CADASTRO
- `git config --global user.name "SeuNome"` (Modificar o nome de usuário)  
- `git config --global user.email SeuEmail` (Modificar o email cadastrado)  
- `git config --global user.name` (Visualizar o nome cadastrado)  
- `git config --global user.email` (Visualizar o email cadastrado)  
- `git config --global credential.helper store/cache` (Salva suas senhas pra sempre/temporariamente)  
- `git config --global --list` (Lista as configurações globais)

---

### CONFIGURAÇÃO E MANIPULAÇÃO DE BRANCHS
- `git config init.defaultBranch` (Visualizar o nome da Branch padrão)  
- `git config --global init.defaultBranch nomeNovo` (Modificar o nome da Branch padrão)  
- `git branch -m nome` (Renomear o nome da branch atual)  
- `git switch -c nome-da-branch` (Criar e mudar para uma nova branch)  
- `git switch nome-da-branch` (Apenas mudar para uma nova branch)  
- `git branch -v` (Lista o último commit de cada branch)  
- `git branch` (Lista as branchs do repositório)  
- `git merge nome-da-branch-a-ser-mesclada` (Mescla um branch à branch atual)  
- `git branch -d nome-da-branch` (Deleta a branch escolhida)  
- `git clone URL --branch nome-da-branch --single-branch` (Clona apenas a branch escolhida)  
- `git diff nome-da-branch-1 nome-da-branch-2` (Mostra as diferenças entre as branchs)

---

### CRIAÇÃO E CLONAGEM DE REPOSITÓRIOS
- `git init` (Transformar pasta em diretório git)  
- `rm -rf .git` (Remove recursivamente o diretório git)  
- `git clone URL` (Clonar o repositório)  
- `git clone URL novoNome` (Clonar o repositório com um novo nome)  
- `git remote -v` (Mostrar os repositórios remotos vinculados)

---

### COMMITS
- `git add nome-do-arquivo` (Adiciona novos arquivos a serem salvos)  
- `git restore nome-do-arquivo` (Restaura o arquivo da forma que está no diretório)  
- `git commit -m"Sua Mensagem"` (Salvar alterações – Commit)  
- `git log` (Exibe histórico de commits)  
- `git reflog` (Exibe histórico de commits mais completo)  
- `git commit --amend -m"Sua Mensagem"` (Alterar mensagem do último commit)  
- `git reset --soft codigoDoCommit` (Head volta para o commit e mantém alterações preparadas para commit)  
- `git reset --mixed codigoDoCommit` (Head volta para o commit e descarta alterações preparadas)  
- `git reset --hard codigoDoCommit` (Head volta para o commit e reseta o código)  
- `git reset nome-do-arquivo` ou `git restore --staged nome-do-arquivo` (Remover arquivos da árvore de trabalho)  
- `git stash` (Arquiva as modificações)  
- `git stash list` (Lista as modificações arquivadas)  
- `git stash pop` (Recupera a modificação arquivada mais recente e a remove da lista)  
- `git stash apply` (Recupera a modificação arquivada mais recente e a mantém na lista)

---

### GITHUB
- `git remote add nome-local URL` (Conectar um repositório local a um remoto)  
- `git push -u origin main` (Envia as alterações do repositório local para o remoto)  
- `git pull` (Baixa e mescla as alterações do repositório remoto para o local)  
- `git fetch origin nome-da-branch` (Baixa mas não mescla as alterações do repositório remoto)

## Links Úteis

|Link| Descrição|
|----|-----|
[Como escrever no Github](https://docs.github.com/pt/get-started/writing-on-github)| Guia completo sobre como escrever e formatar conteúdo no GitHub.
[GitFluence](https://www.gitfluence.com)|Uma ferramenta online que sugere o comando Git ideal com base na ação que o usuário deseja realizar.
[Conventional Commits](https://github.com/conventional-commits/conventionalcommits.org)|Repositório sobre commits convencionais.
[GitHub Etiquetas](https://docs.github.com/pt/issues/using-labels-and-milestones-to-track-work/managing-labels)|Página do GitHub que explica como gerenciar labels para organizar e acompanhar issues e pull requests

## Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/pt)

## Referências
