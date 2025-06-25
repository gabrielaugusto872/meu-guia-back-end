# DIO | Resumos Git e Github

Repositório para armazenar Comandos utéis para o Git e Github.

## 🧾 Menu
- [Lista de Comandos](#💻-lista-de-comandos)
- [Documentação](#📚-documentação)
- [Referências](#🔍-referências)

## 💻 Lista de Comandos

- [Comandos Gerais](#comandos-gerais)
- [Cadastro](#cadastro )
- [Configuração da Branch](#configuração-da-branch)
- [Criação e Clonagem de Repositórios](#criação-e-clonagem-de-repositórios)

---

### Comandos Gerais
- #### Listar
```
ls
```

### Cadastro 
- #### Modificar o nome de usuário
```ruby
git config --global user.name "SeuNome" 
```
- #### Modificar o email cadastrado
```ruby
git config --global user.email SeuEmail
```
- #### Visualizar o nome cadastrado
```ruby
git config --global user.name
```
- #### Visualizar o email cadastrado
```ruby
git config --global user.email
```
- #### Salva suas senhas pra sempre/temporariamente
```ruby
git config --global credential.helper store/cache
```
 
### Configuração da Branch
- #### Visualizar o nome da Branch padrão
```ruby
git config init.defaultBranch
```
- #### Modificar o nome da Branch padrão
```ruby
git config --global init.defaultBranch nomeNovo
```
- #### Renomear o nome da branch atual
```ruby
git branch -m nome
```
- #### Lista as configurações globais
```ruby
git config --global --list
```

### Criação e Clonagem de Repositórios
- #### Criar pasta
```ruby
mkdir nome-da-pasta
```
- #### Excluir pasta
```ruby
rmdir nome-da-pasta
```
- #### Entrar na pasta
```ruby
cd nome-da-pasta/
```
- #### Trasnformar pasta em diretório git
```ruby
git init
```
- #### Remove recursivamente o diretório git
```ruby
rm -rf .git
```
- #### Entrar no arquivo
```ruby
cd nome-do-arquivo
```
- #### Sair do arquivo ou pasta
```ruby
cd ..
```
- #### Clonar o repositório
```ruby
git clone URL
```
- #### Clonar o repositório com um novo nome
```ruby
git clone URL novoNome
```
- #### Mostrar os repositórios remotos vinculados
```ruby
git remote -v
```
- #### Conectar um rpositório local a um remoto
```ruby
git remote add nome URL
```
- #### Clona apenas a branch escolhida
```ruby
git clone URL --branch nome-da-branch --single-branch
```
- #### Adiciona novos arquivos a serem salvos
```ruby
git add nome-do-arquivo
```
- #### Restaura o arquivo da forma que está no diretório
```ruby
git restore nome-do-arquivo
```
- #### Salvar alterações (Commit)
```ruby
git commit -m"Sua Mensagem"
```
---
- #### Exibe histórico de commits
```ruby
git log
```
- #### Alterar mensagem do último commit (Commit)
```ruby
git commit --amend -m"Sua Mensagem"
```
---
- #### Mostrar o status da árvore de trabalho
```ruby
git status
```
---

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/pt)

## 🔍 Referências
oooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooi