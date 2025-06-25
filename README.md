# Comandos Git e Github

Repositório para armazenar Comandos utéis para o Git e Github.

## 🧾 Menu
- [Lista de Comandos](##lista-de-comandos)
- [Documentação](#📚-documentação)
- [Referências](#🔍-referências)

## 💻 Lista de Comandos

- [Comandos Gerais](#comandos-gerais)
- [Criação e Navegação entre pastas e arquivos](#criação-e-navegação-entre-pastas-e-arquivos)
- [Cadastro](#cadastro )
- [Configuração da Branch](#configuração-da-branch)
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

### Criação e Navegação entre pastas e arquivos
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
 
### Configuração da Branch
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
- #### Lista as configurações globais
```ruby
git config --global --list
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
- #### Clona apenas a branch escolhida
```ruby
git clone URL --branch nome-da-branch --single-branch
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

### Github
- #### Conectar um repositório local a um remoto
```ruby
git remote add nome URL
```
---
- #### Envia as alterações do repositório local paro o remoto
```ruby
git push -u origin main
```
---
- #### Baixa as alterações do repositório remoto paro o local
```ruby
git pull
```
---


## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/pt)

## 🔍 Referências
