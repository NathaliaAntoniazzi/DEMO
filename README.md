
# Curso Git e GitHub

Repositório criado para armazenar resumos e materiais do curso Versionamento de código com Git e GitHub e do GitHub for Women

## 📚Documentação

- [Documentação GitHub](https://docs.github.com/pt)
- [GitHub MarkDown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Principais Comandos

| Comando         | Descrição |
|----------------|-----------|
| `git init`     | Inicializa um novo repositório Git no diretório atual. |
| `git clone <URL>` | Faz o download de um repositório remoto para o seu computador. |
| `git status`   | Mostra o status dos arquivos no repositório (modificados, não rastreados, etc.). |
| `git add <arquivo>` | Adiciona um arquivo específico para a área de preparação (staging area). |
| `git add .`    | Adiciona todos os arquivos modificados para a área de preparação. |
| `git commit -m "mensagem"` | Cria um commit com os arquivos adicionados e uma mensagem descritiva. |
| `git push origin <branch>` | Envia os commits locais para o repositório remoto na branch especificada. |
| `git pull origin <branch>` | Atualiza seu repositório local com as mudanças do repositório remoto. |
| `git fetch`    | Baixa as alterações do repositório remoto, mas sem mesclá-las automaticamente. |
| `git merge <branch>` | Mescla uma branch especificada à branch atual. |
| `git branch`   | Lista todas as branches do repositório. |
| `git branch <nome>` | Cria uma nova branch. |
| `git checkout <branch>` | Muda para a branch especificada. |
| `git checkout -b <branch>` | Cria e muda para uma nova branch ao mesmo tempo. |
| `git rebase <branch>` | Move ou reaplica commits de uma branch sobre outra. |
| `git log`      | Exibe o histórico de commits do repositório. |
| `git reset --hard <commit>` | Retorna o repositório a um estado específico, descartando mudanças. |
| `git stash`    | Salva temporariamente mudanças não commitadas. |
| `git stash pop` | Restaura as mudanças salvas com `git stash`. |
| `git remote -v` | Lista os repositórios remotos vinculados ao local. |
| `git remote add origin <URL>` | Associa um repositório remoto ao repositório local. |
| `git diff`     | Exibe as diferenças entre arquivos no repositório. |
| `git tag <versão>` | Cria uma nova tag para marcar um ponto específico na linha do tempo do projeto. |

### Extras:
- Para desfazer um commit antes de enviar:  
  ```bash
  git reset --soft HEAD~1
