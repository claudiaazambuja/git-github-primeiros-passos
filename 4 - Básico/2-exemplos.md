# Criação de um cenário com os comandos básicos.

## Cenário 1: Iniciar um novo projeto

### Git init
Antes de iniciar um novo projeto, você pode criar um diretório para o projeto e inicializar um repositório Git nele.

```console
mkdir meu_projeto
cd meu_projeto
git init
```

### Git status

Verifique o status para ver se há arquivos não rastreados no diretório.

```console
git status
```

## Cenário 2: Clonar um repositório existente

### Git clone
Clone um repositório remoto para obter uma cópia local.

```console
git clone https://github.com/usuario/repositorio.git
cd repositorio
```

### Git status
Verifique o status para ver se há alterações locais não commitadas.

```console
git status
```

## Cenário 3: Fazer alterações locais

### Git add
Adicione arquivos ao próximo commit.

```console
git add arquivo_modificado.txt
```
### Git status
Verifique o status para confirmar que as alterações foram preparadas.

```console
git status
```

### Git commit
Faça um commit das alterações com uma mensagem descritiva.

```console
git commit -m "Adicionando arquivo_modificado.txt"
```

## Cenário 4: Enviar alterações para o repositório remoto
### Git push
Envie as alterações para o repositório remoto.

```console
git push origin master
```

## Cenário 5: Atualizar o repositório local
### Git pull
Atualize seu repositório local com as alterações do remoto.

```console
git pull origin master
```


**Esses são exemplos básicos, e no mundo real, você pode usar esses comandos de maneira mais complexa, dependendo do fluxo de trabalho e das necessidades do projeto**.