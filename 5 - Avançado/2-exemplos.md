# Criação de um cenário com os comandos Avançados.

## Cenário 1: Trabalhando com Branches
### Git branch
Listar branches existentes:

```console
git branch
```

Criar uma nova branch:

```console
git branch nova-feature
```

### Git checkout
Mudar para uma branch específica:

```console
git checkout nova-feature
```

## Cenário 2: Mesclar Alterações (Merge)
### Git merge
Mesclar alterações de uma branch para a branch atual:

```console
git checkout master
git merge nova-feature
```

## Cenário 3: Visualizar Histórico
### Git log
Visualizar histórico de commits:

```console
git log
```

## Cenário 4: Trabalhando com Repositórios Remotos
### Git remote
Adicionar um novo repositório remoto:

```console
git remote add origin https://github.com/usuario/novo-repositorio.git
```

### Git fetch
Atualizar informações sobre branches remotas:

```console
git fetch origin
```
## Cenário 5: Reorganizando Commits (Rebase)
### Git rebase
Reorganizar commits locais antes de enviar para o repositório remoto:

```console
git checkout minha-feature
git rebase master
```

## Cenário 6: Tags e Versões
### Git tag
Criar uma nova tag para um commit específico:

```console
git tag v1.0
```

## Cenário 7: Desfazer Alterações
### Git reset
Desfazer as últimas alterações commitadas localmente:

```console
git reset HEAD~1
```

### Git revert
Desfazer um commit específico criando um novo commit:

```console
git revert abcdef
```

## Cenário 8: Stash (Guardar Alterações Temporariamente)
### Git stash
Guardar alterações antes de mudar para outra branch:

```console
git stash
```

### Git stash apply
Recuperar alterações guardadas:

```console
git stash apply
```


**Estes são apenas alguns exemplos e a utilização exata pode variar dependendo do contexto do projeto. É sempre recomendável entender completamente o impacto de cada comando antes de usá-lo**.