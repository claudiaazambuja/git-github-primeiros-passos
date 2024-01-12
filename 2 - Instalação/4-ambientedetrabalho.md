# Verificando se está tudo ok

## Verificar a instalação do Git

```console
git --version
```

## Verificar conexão do GitHUb

```console
ssh -T git@github.com
```


## Configurações do VSCode

1. Abra o VSCode.
2. Abra um projeto ou crie um novo.

## Conexão do SCM no VsCode com o GitHub:

### O que é SCM

- O Visual Studio Code integrou o gerenciamento de controle de origem (SCM) e inclui suporte Git pronto para uso. Muitos outros provedores de controle de origem estão disponíveis por meio de extensões no VS Code Marketplace.

### No que ajuda

O ícone de controle de origem na barra de atividades à esquerda sempre indicará uma visão geral de quantas alterações você tem atualmente em seu repositório. Selecionar o ícone mostrará os detalhes das alterações atuais do repositório: **CHANGES** , **STAGED CHANGES** e **MERGE CHANGES**.

Clicar em cada item mostrará detalhadamente as alterações textuais em cada arquivo. 

Você também pode encontrar indicadores do status do seu repositório no canto inferior esquerdo do VS Code: o branch atual , indicadores sujos e o número de commits de entrada e saída do branch atual. Você pode fazer check-out de qualquer branch em seu repositório clicando no indicador de status e selecionando a referência do Git na lista.

**Fazer Login no GitHub**:

Configurar Informações do Git (se ainda não tiver configurado):

Execute os seguintes comandos, substituindo "Seu Nome" e "seu@email.com" pelos seus dados.

```console
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

```

Você pode verificar se a autenticação foi bem-sucedida usando o comando:

```console
git config user.name
```

Isso retornará seu usuário logado GitHub.


Para saber mais leia a [documentação](https://code.visualstudio.com/docs/sourcecontrol/overview)