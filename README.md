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
- #### Mostrar o status da árvore de trabalho
```ruby
git status
```
---
- #### Listar

```
ls
```
---

### Criação e Navegação Entre Pastas e Arquivos
- #### Criar pasta
```ruby
mkdir nome-da-pasta
```
---
- #### Excluir pasta
```ruby
rmdir nome-da-pasta
```
---
- #### Entrar na pasta
```ruby
cd nome-da-pasta/
```
---
- #### Criar arquivo
```ruby
touch nome-do-arquivo 
```
---
- #### Entrar no arquivo
```ruby
cd nome-do-arquivo
```
---
- #### Sair do arquivo ou pasta
```ruby
cd ..
```
---
- #### Cria um arquivo com contéudo ou sobreescreve um ja criado
```ruby
echo "Primeira linha do arquivo" > nome-arquivo.txt
```
---
- #### Adiciona contéudo no final de um arquivo já criado
```ruby
echo "Nova linha" >> nome-arquivo.txt
```
---

### Cadastro 
- #### Modificar o nome de usuário
```ruby
git config --global user.name "SeuNome" 
```
---
- #### Modificar o email cadastrado
```ruby
git config --global user.email SeuEmail
```
---
- #### Visualizar o nome cadastrado
```ruby
git config --global user.name
```
---
- #### Visualizar o email cadastrado
```ruby
git config --global user.email
```
---
- #### Salva suas senhas pra sempre/temporariamente
```ruby
git config --global credential.helper store/cache
```
---
- #### Lista as configurações globais
```ruby
git config --global --list
```
---
 
### Configuração e Manipulação de Branchs
- #### Visualizar o nome da Branch padrão
```ruby
git config init.defaultBranch
```
---
- #### Modificar o nome da Branch padrão
```ruby
git config --global init.defaultBranch nomeNovo
```
---
- #### Renomear o nome da branch atual
```ruby
git branch -m nome
```
---
- #### Criar e mudar para uma nova branch
```ruby
git switch -c nome-da-branch
```
---
- #### Apenas mudar para uma nova branch
```ruby
git switch nome-da-branch
```
---
- #### Lista o último commit de cada branch
```ruby
git branch -v
```
---
- ### Lista as branchs do repositório
```ruby
git branch
```
---
- #### Mescla um branch a branch atual
```ruby
git merge nome-da-branch-a-ser-mesclada
```
---
- #### Deleta a branch escolhida
```ruby
git branch -d nome-da-branch
```
---
- #### Clona apenas a branch escolhida
```ruby
git clone URL --branch nome-da-branch --single-branch
```
---
- #### Mostra as diferenças entre as branchs
```ruby
git diff nome-da-branch-1 nome-da-branch-2
```
---

### Criação e Clonagem de Repositórios
- #### Trasnformar pasta em diretório git
```ruby
git init
```
---
- #### Remove recursivamente o diretório git
```ruby
rm -rf .git
```
---
- #### Clonar o repositório
```ruby
git clone URL
```
---
- #### Clonar o repositório com um novo nome
```ruby
git clone URL novoNome
```
---
- #### Mostrar os repositórios remotos vinculados
```ruby
git remote -v
```
---

### Commits
- #### Adiciona novos arquivos a serem salvos
```ruby
git add nome-do-arquivo
```
---
- #### Restaura o arquivo da forma que está no diretório
```ruby
git restore nome-do-arquivo
```
---
- #### Salvar alterações (Commit)
```ruby
git commit -m"Sua Mensagem"
```
---
- #### Exibe histórico de commits
```ruby
git log
```
---
- #### Exibe histórico de commits mais completo
```ruby
git reflog
```
---
- #### Alterar mensagem do último commit (Commit)
```ruby
git commit --amend -m"Sua Mensagem"
```
---
- #### Head volta para o commit apontado, as alteraçoes do commit apagado ficam prontas para serem commitadas denovo mas o código não é modificado
```ruby
git reset --soft codigoDoCommit
```
---
- #### Head volta para o commit apontado, as alteraçoes do commit apagado ficam somem mas o código não é modificado
```ruby
git reset --mixed codigoDoCommit
```
---
- #### Head volta para o commit apontado, as alteraçoes do commit apagado somem e o código é resetado
```ruby
git reset --hard codigoDoCommit
```
---
- #### Remover arquivos da árvore de trabalho
```ruby
git reset nome-do-arquivo 
```
ou
```ruby
git restore --staged nome-do-arquivo

```
---
- #### Arquiva as modificações
```ruby
git stash
```
---
- #### Lista as modificações arquivadas
```ruby
git stash list
```
---
- #### Recupera a modificação arquivada mais recente e remove ela da lista
```ruby
git stash pop 
```
---
- #### Recupera a modificação arquivada mais recente e mantém ela na lista
```ruby
git stash apply 
```
---

### Github
- #### Conectar um repositório local a um remoto
```ruby
git remote add nome-local URL
```
---
- #### Envia as alterações do repositório local paro o remoto
```ruby
git push -u origin main
```
---
- #### Baixa e mescla as alterações do repositório remoto paro o local
```ruby
git pull
```
---
- #### Baixa mas não mescla as alterações do repositório remoto paro o local
```ruby
git fetch origin nome-da-branch
```
---

## Links Úteis

|Link| Descrição|
|----|-----|
[Como escrever no Github](https://docs.github.com/pt/get-started/writing-on-github)| Guia completo sobre como escrever e formatar conteúdo no GitHub.
[GitFluence](https://www.gitfluence.com)|Uma ferramenta online que sugere o comando Git ideal com base na ação que o usuário deseja realizar.

## Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/pt)

## Referências
