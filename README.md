
# 📌 Guia Completo de Comandos Git

> Um guia prático e visual para aprender os comandos essenciais do Git 🚀

---

## 🔹 Configuração Inicial

```bash
 git config --global user.name "Seu Nome"
 git config --global user.email "seuemail@example.com"
```
> Configura seu nome e e-mail no Git.

```bash
 git config --list
```
> Exibe todas as configurações do Git.

---

## 🔹 Criando e Inicializando um Repositório

```bash
 git init
```
> Inicializa um novo repositório Git no diretório atual.

```bash
 git clone <URL>
```
> Clona um repositório remoto para o seu computador.

---

## 🔹 Trabalhando com Arquivos

```bash
 git status
```
> Mostra o estado atual dos arquivos no repositório.

```bash
 git add <arquivo>
 git add .
```
> Adiciona arquivos específicos (ou todos) à área de stage.

```bash
 git commit -m "Mensagem do commit"
```
> Salva as mudanças adicionadas com uma mensagem descritiva.

```bash
 git rm <arquivo>
```
> Remove um arquivo do repositório e do sistema de arquivos.

---

## 🔹 Histórico e Logs

```bash
 git log
```
> Exibe o histórico de commits.

```bash
 git log --oneline --graph
```
> Exibe um histórico mais visual e resumido dos commits.

```bash
 git diff
```
> Mostra as diferenças entre as versões dos arquivos.

---

## 🔹 Trabalhando com Branches

```bash
 git branch
```
> Lista todas as branches do repositório.

```bash
 git branch <nome-da-branch>
```
> Cria uma nova branch.

```bash
 git checkout <nome-da-branch>
 git switch <nome-da-branch>
```
> Muda para a branch especificada.

```bash
 git merge <nome-da-branch>
```
> Mescla uma branch à branch atual.

```bash
 git branch -d <nome-da-branch>
```
> Deleta uma branch local.

---

## 🔹 Trabalhando com Repositórios Remotos

```bash
 git remote add origin <URL>
```
> Adiciona um repositório remoto.

```bash
 git push origin <nome-da-branch>
```
> Envia os commits para um repositório remoto.

```bash
 git pull origin <nome-da-branch>
```
> Puxa as atualizações do repositório remoto.

```bash
 git fetch
```
> Baixa alterações do repositório remoto sem mesclar automaticamente.

---

## 🔹 Revertendo Alterações

```bash
 git reset --hard <commit>
```
> Volta para um commit específico e descarta alterações posteriores.

```bash
 git revert <commit>
```
> Reverte um commit específico sem perder o histórico.

```bash
 git stash
```
> Salva temporariamente mudanças sem commit.

```bash
 git stash pop
```
> Aplica as mudanças salvas no stash.

---

## 🔹 Outros Comandos Úteis

```bash
 git tag <nome-da-tag>
```
> Cria uma tag para um commit específico.

```bash
 git blame <arquivo>
```
> Mostra quem modificou cada linha de um arquivo.

```bash
 git show <commit>
```
> Exibe detalhes de um commit específico.

---
