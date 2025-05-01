# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Além disso, vamos trabalhar com **GitFlow** e **Visual Studio Code**.

## Fluxo de Trabalho Git Local

1. `git checkout -b <nova-branch>`
2. Cria ou atualiza arquivos
3. `git status`
4. `git add <arquivos>`
5. `git status`
6. `git commit -m "<minha mensagem>"`
7. `git checkout main`
8. `git merge nova_branch`

## Fluxo de Trabalho GitHub <> Local (Projeto Próprio ou da Sua Empresa)

1. `git clone <endereco-do-projeto>`
2. `git checkout -b <nova_branch>`
3. Alterações de arquivos
4. `git status`
5. `git add <arquivos>`
6. `git status`
7. `git commit -m "<nova mensagem>"`
8. `git push origin <nova_branch>`
9. Abrir Pull Request no GitHub para `main`
10. Excluir `<nova_branch>` do remoto (`origin`)
11. `git checkout main`
12. `git branch -D <nova_branch>`

## Fluxo de Trabalho GitHub <> Local (Projetos Open-Source)

1. **Fork** do projeto para seu próprio GitHub
2. `git clone <endereco-do-projeto-fork>`
3. `git checkout -b <nova_branch>`
4. Alterações de arquivos
5. `git status`
6. `git add <arquivos>`
7. `git status`
8. `git commit -m "<nova mensagem>"`
9. `git push origin <nova_branch>`
10. Abrir Pull Request no GitHub da branch fork para a `main` do projeto original
11. Excluir `<nova_branch>` do remoto (`origin`)
12. `git checkout main`
13. `git branch -D <nova_branch>`
