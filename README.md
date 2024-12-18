
# Resumo dos Comandos do Git

## Comandos Básicos

- `git init`: Inicializa um novo repositório Git.
- `git clone <url>`: Clona um repositório remoto para o seu computador.
- `git status`: Verifica o status dos arquivos no diretório de trabalho.
- `git add <arquivo>`: Adiciona um arquivo específico ao índice (staging area).
- `git commit -m "mensagem"`: Comita as mudanças adicionadas com uma mensagem descritiva.
- `git log`: Exibe o histórico de commits do repositório.

## Trabalhando com Branches

- `git branch`: Lista todas as branches no repositório.
- `git branch <nome-da-branch>`: Cria uma nova branch.
- `git checkout <nome-da-branch>`: Troca para a branch especificada.
- `git merge <nome-da-branch>`: Faz merge das mudanças da branch especificada na branch atual.

## Atualizando e Enviando Mudanças

### Pull

Para atualizar seu repositório local com as mudanças do repositório remoto, use o comando `git pull`:

```sh
git pull origin <nome-da-branch>
```

### Push

Para enviar suas mudanças locais para o repositório remoto, use o comando `git push`:

```sh
git push origin <nome-da-branch>
```

## Outros Comandos Úteis

- `git remote -v`: Lista os repositórios remotos configurados.
- `git fetch`: Baixa as mudanças do repositório remoto sem fazer merge.
- `git diff`: Mostra as diferenças entre os arquivos modificados e o último commit.
- `git reset --hard <commit>`: Reseta o repositório para um commit específico, descartando todas as mudanças posteriores.
## GitHub Copilot

GitHub Copilot é uma ferramenta de inteligência artificial desenvolvida pela GitHub em parceria com a OpenAI. Ele sugere linhas de código e funções inteiras diretamente no seu editor de código, ajudando a acelerar o desenvolvimento e melhorar a produtividade.

## GitHub Codespaces

GitHub Codespaces é um ambiente de desenvolvimento baseado na nuvem que permite configurar instantaneamente um ambiente de desenvolvimento completo e configurado com todas as dependências necessárias. Ele é acessível diretamente do GitHub e pode ser usado em qualquer lugar.

## github.dev

github.dev é uma versão baseada na web do Visual Studio Code que pode ser acessada diretamente do navegador. Ele permite editar e navegar pelo código em repositórios GitHub sem a necessidade de clonar o repositório localmente.

## Organizações no GitHub

Organizações no GitHub são uma maneira de gerenciar permissões e colaborar em projetos com várias pessoas. Elas permitem agrupar repositórios, gerenciar membros e definir níveis de acesso, facilitando a colaboração em equipe e a administração de projetos.



