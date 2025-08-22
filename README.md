# BusqueComerCimento

📄👽 | Repositório para organizar e compartilhar meus aprendizados.

## Rodando Localmente

Para visualizar e trabalhar com a documentação do projeto localmente, você precisa ter o **Node.js** e o **npm** instalados na sua máquina.

Este projeto utiliza o **Docsify**, um gerador de documentação que serve o conteúdo diretamente dos arquivos Markdown.

### 1\. Instalar o Docsify

Primeiro, instale a ferramenta de linha de comando do Docsify globalmente. Por ser uma instalação global, você precisará de permissões de superusuário, então use o `sudo`:

```bash
sudo npm i docsify-cli -g
```

Você será solicitado a digitar sua senha para completar a instalação.

### 2\. Executar o Servidor

Após a instalação, navegue até a raiz do projeto (onde o arquivo `index.html` e o diretório `docs` estão localizados) e use o comando `docsify serve` para iniciar o servidor local:

```bash
docsify serve docs
```

### 3\. Visualizar no Navegador

O servidor iniciará, e você poderá acessar a documentação no seu navegador. Abra a seguinte URL:

```
http://localhost:3000
```

Qualquer alteração que você fizer nos arquivos Markdown dentro da pasta `docs` será atualizada automaticamente no navegador, sem a necessidade de recarregar a página.