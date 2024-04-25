# Curso Git e Github FGV Online

Repositório para executar as tarefas do curso de Git e Github do curso da FGV Online.

## Comandos

### Criar uma nova branch (ramificação) para um projeto:

- Criar branch

  ```shell
  git branch nome-nova-branch
  ```

- Acessar branch

  ```shell
  git checkout nome-nova-branch
  ```

ou

- Criar e acessar a branch

  ```shell
  git checkout -b nome-nova-branch
  ```

### Excluir uma branch

```shell
git branch -D nome-nova-branch
```

### Criar repositório remoto

Primeiro certifique-se de que existe um reposiório remoto criado, para depois fazer a conexão abaixo:

```shell
git git remote add origin https://github.com/NOME-USUARIO-GITHUB/NOME-REPOSITORIO.git
```

Agora envie os arquivos do repositório local para o remoto:

- Caso o repositório local esteja com o nome Master da branch principal, altere para main, pois o Github usa esse padrão:

```shell
git git branch -M main
```

- Em seguida faça o push:

```shell
git git push -u origin main
```