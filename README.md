# AtlasPay Fintech Web

Tela estática da atividade FIAP para o projeto Fintech AtlasPay, recriando somente a **Tela 02 - Dashboard financeiro** com base no protótipo `atlaspay.pen`.

## Descrição

O projeto apresenta um dashboard financeiro responsivo com sidebar, cards de saldo, recebimentos, gastos, investimentos, último gasto, progresso de objetivo financeiro e gráfico visual de evolução dos investimentos.

## Protótipo de referência

O desenvolvimento da tela foi baseado na **Tela 02 - Dashboard financeiro** do protótipo AtlasPay.

Arquivo de referência:

[Visualizar PDF da Tela 02 - Dashboard financeiro](./docs/tela-02-dashboard-atlaspay.pdf)

Esse PDF contém a tela usada como base visual para a recriação em HTML, CSS e Tailwind CSS.

## Estrutura do projeto

```text
atlaspay-fintech-web/
├── index.html
├── css/
│   └── styles.css
├── src/
│   └── input.css
├── docs/
│   └── tela-02-dashboard-atlaspay.pdf
├── package.json
├── package-lock.json
├── README.md
└── .gitignore
```

## Tecnologias Usadas

- HTML5
- CSS3 separado
- Tailwind CSS compilado via npm
- Sem JavaScript
- Sem backend

## Como abrir o projeto após clonar o repositório

Após clonar o repositório, acesse a pasta do projeto:

```bash
git clone https://github.com/MarceloCG-bot/atlaspay-fintech-web.git
cd atlaspay-fintech-web
```

Para visualizar a tela, abra o arquivo `index.html` diretamente no navegador.

### Opção 1: abrir pelo gerenciador de arquivos

1. Abra a pasta do projeto no computador.
2. Localize o arquivo `index.html`.
3. Dê dois cliques sobre o arquivo.
4. O navegador padrão será aberto exibindo a tela do AtlasPay.

### Opção 2: abrir pelo VS Code com Live Server

1. Abra a pasta do projeto no VS Code.
2. Clique com o botão direito no arquivo `index.html`.
3. Escolha a opção **Open with Live Server**.
4. A página será aberta no navegador.

### Opção 3: abrir pelo terminal no Linux

Dentro da pasta do projeto, execute:

```bash
xdg-open index.html
```

### Opção 4: abrir pelo terminal no Windows

Dentro da pasta do projeto, execute:

```bash
start index.html
```

O projeto já possui o CSS final compilado em `css/styles.css`, então não é necessário executar `npm install` apenas para visualizar a página.

## Como executar em modo de desenvolvimento

O `npm install` só é necessário caso você queira editar o projeto e gerar novamente o CSS do Tailwind.

Instale as dependências:

```bash
npm install
```

Gere novamente o CSS:

```bash
npm run build
```

O comando acima recria o arquivo:

```text
css/styles.css
```

## Observação

Este projeto não usa JavaScript. A tela foi construída com HTML e CSS, usando Tailwind CSS para o layout e os estilos.
