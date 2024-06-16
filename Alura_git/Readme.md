Claro, aqui está um arquivo em Markdown com os principais comandos do Git e suas explicações:

```markdown
# Principais Comandos do Git

## Configuração Inicial

- **git config --global user.name "Seu Nome"**  
  Configura o nome do usuário que será associado aos commits feitos no seu sistema.

- **git config --global user.email "seuemail@example.com"**  
  Configura o e-mail do usuário que será associado aos commits feitos no seu sistema.

## Comandos Básicos

- **git init**  
  Inicializa um novo repositório Git no diretório atual.

- **git clone <url-do-repositorio>**  
  Clona um repositório existente a partir de uma URL.

- **git status**  
  Mostra o status das mudanças no repositório, indicando arquivos modificados, não rastreados e mudanças que estão no staging.

- **git add <arquivo>**  
  Adiciona um arquivo específico à área de staging.

- **git add .**  
  Adiciona todas as mudanças no diretório atual à área de staging.

- **git commit -m "mensagem do commit"**  
  Faz um commit das mudanças na área de staging com uma mensagem descritiva.

- **git push**  
  Envia os commits para o repositório remoto.

- **git pull**  
  Atualiza o repositório local com as mudanças do repositório remoto.

## Branching e Merging

- **git branch**  
  Lista todas as branches no repositório.

- **git branch <nome-da-branch>**  
  Cria uma nova branch.

- **git checkout <nome-da-branch>**  
  Troca para a branch especificada.

- **git checkout -b <nome-da-branch>**  
  Cria e troca para uma nova branch.

- **git merge <nome-da-branch>**  
  Mescla a branch especificada na branch atual.

- **git branch -d <nome-da-branch>**  
  Deleta a branch especificada.

## Desfazendo Mudanças

- **git reset <arquivo>**  
  Remove o arquivo da área de staging, mas mantém as mudanças no diretório de trabalho.

- **git reset --hard**  
  Reseta o diretório de trabalho e a área de staging para o último commit.

- **git restore <arquivo>**  
  Desfaz as mudanças no arquivo especificado no diretório de trabalho.

- **git revert <id-do-commit>**  
  Cria um novo commit que reverte as mudanças de um commit específico.

## Repositórios Remotos

- **git remote**  
  Lista repositórios remotos configurados.

- **git remote add <nome> <url-do-repositorio>**  
  Adiciona um novo repositório remoto.

- **git remote remove <nome>**  
  Remove um repositório remoto.

## Visualização de Histórico

- **git log**  
  Exibe o histórico de commits.

- **git log --oneline**  
  Exibe o histórico de commits em uma linha por commit.

- **git diff**  
  Mostra as diferenças entre as mudanças não comitadas e o último commit.

- **git diff <branch1> <branch2>**  
  Mostra as diferenças entre duas branches.

## Submódulos

- **git submodule add <url> <caminho>**  
  Adiciona um repositório como submódulo.

- **git submodule update --init --recursive**  
  Inicializa, atualiza e clona todos os submódulos.

## Outras Operações Úteis

- **git stash**  
  Salva mudanças não comitadas para um stash temporário.

- **git stash apply**  
  Aplica as mudanças do stash no diretório de trabalho.

- **git tag <versao>**  
  Cria uma tag para um commit específico.

- **git show <tag>**  
  Mostra detalhes de uma tag específica.

## Ajuda

- **git help <comando>**  
  Mostra a documentação de ajuda para um comando específico.
