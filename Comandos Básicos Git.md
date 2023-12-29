# README sobre Git e GitHub

Contém um resumo com os principais comandos do Git e Markdown.

## 📖 Documentação
- [Documentação Git](https://git-scm.com/doc).
- [Documentação GitHub](https://docs.github.com/).

## 🖥️ Resumo de alguns comandos 
| Comando | Descrição |
|---------|-----------|

```
git init | Cria um repositório Git vazio ou reinicializa um repositório existente
```
```
git status | Mostra o status da pasta de trabalho
```
```
git add . ou * ou -A ou [nomedoarquivo] | Adiciona arquivos modificados para a área staging
```
```
git commit -m "texto com a mensagem aqui" | Pega os arquivos modificados no diretório e coloca em área de staging
```
```
git push -u origin main(ou master) | Transfere os arquivos commitados para o servidor
```
```
git clone [endereço dos arquivos no GitHub](Pode ser por HTTPS ou SSH ou CLI) | Faz uma cópia dos arquivos do servidor para do diretório atual
```
```
git rm nomedoarquivo (Para mais opções consultar --help) | Remover arquivos rastreados pelo índice Git, e da área staging e diretório de trabalho.
```
```
git branch | Listar, criar ou excluir ramificações(branches)
```
```
git clean | Remover arquivos não rastreados da árvore de trabalho
```
```
git diff | Mostra as diferenças entre os commits
```
```
git switch [nomedabranch] | Troca de branch
```
```
git commit --amend -m"mensagemaseralterada" | Altera a mensagem de commit criada anteriormente 
```
```
git restore [nomedoarquivoarestaurar] | Remove as modificações do arquivo
```
```
git reset [--soft] [--mixed] [--hard] hashaserresetada | Reseta o commit para o commit anterior
```
```
git pull | Sicroniza os arquivos com o repositório remoto
```
```
git checkout -b [nomedanovabranch] | Sai da branch main e vai pra nova branch criada [nomedanovabranch]
```
```
git branch -v | Mostra as braches existentes
```
```
git merge [nomedabranch] | Mescla a branch main com a branch criada
```
```
git branch -d [nomedabranch] | Remove a branch 
```



## 🔍 Referências

- [Sintaxe básica para Markdown](https://www.markdownguide.org/basic-syntax/).
- [Documentação de introdução ao GitHub](https://docs.github.com/pt/get-started).
