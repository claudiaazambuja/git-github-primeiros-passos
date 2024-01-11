# O que é uma chave SSH?

**SSH (Secure Shell)**: É um protocolo de rede seguro que permite a comunicação segura entre dois sistemas, geralmente usado para acessar e controlar remotamente servidores.

**Chave SSH**: No contexto do GitHub, uma chave SSH é uma chave criptográfica que você gera localmente e associa à sua conta do GitHub. Essa chave é usada para autenticar sua máquina ao interagir com os servidores do GitHub.

# Gerar uma chave SSH

1. Instale o Git Bash (se ainda não tiver instalado).
2. Gere uma chave SSH:

```console
ssh-keygen -t rsa -b 4096 -C "seu-email@example.com"
```

3. Inicie o `ssh-agent`
- Execute os seguintes comandos no GitBash para iniciar e adicionar a sua chave privada

```console
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

4. Copie a chave SSH para o clipboard

```console
cat ~/.ssh/id_rsa.pub | clip
```

# Adicionar a chave SSH à sua conta do GitHub:

1. Acesse as configurações do SSH no GitHub (https://github.com/settings/keys).
2. Clique em "New SSH key" (Nova chave SSH).
3. Cole a chave que você copiou anteriormente no campo "Key".
4. Dê um nome descritivo para a chave (opcional).
5. Clique em "Add SSH key" (Adicionar chave SSH).

# Teste sua conexão 

No GitBash, teste sua conexão com o seguinte comando:

```console
ssh -T git@github.com
```

**Você deverá receber uma mensagem de sucesso**