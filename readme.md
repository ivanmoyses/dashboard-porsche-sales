# Porsche Sales Intelligence 

Dashboard interativa de inteligência comercial desenvolvida em HTML, CSS e JavaScript para explorar uma base de vendas de veículos Porsche, com indicadores executivos, gráficos dinâmicos e análise de preferência por mercado.

O projeto faz parte de um desafio prático de análise de dados da DIO e demonstra como transformar dados tabulares em informações visuais para apoiar decisões comerciais.

## Visão geral

A **Porsche Sales Intelligence** apresenta uma interface executiva inspirada no conceito All Black Piano: superfícies pretas, contrastes em grafite, tipografia clara e detalhes metálicos discretos.

A dashboard foi estruturada para facilitar a leitura de indicadores e a comparação entre diferentes dimensões de vendas.

## Objetivos do projeto

- Analisar o volume de vendas por modelo e ano-modelo.
- Comparar o faturamento entre cidades, estados e métodos de pagamento.
- Acompanhar a evolução mensal do faturamento.
- Identificar o modelo mais vendido em cada cidade.
- Explorar os dados por meio de filtros interativos.
- Transformar registros comerciais em indicadores e insights de fácil interpretação.

## Indicadores executivos

A dashboard apresenta quatro indicadores principais:

- **Faturamento total:** soma dos valores dos registros selecionados.
- **Veículos na seleção:** quantidade de registros correspondentes aos filtros.
- **Ticket médio:** faturamento total dividido pela quantidade de registros.
- **Modelo líder:** modelo com maior quantidade de registros no recorte selecionado.

Os indicadores são recalculados conforme os filtros aplicados.

## Filtros interativos

O usuário pode segmentar a análise por:

- Modelo Porsche;
- Ano-modelo;
- Cidade;
- Método de pagamento.

O botão de limpeza permite retornar à visualização sem filtros.

## Visualizações disponíveis

### Evolução das vendas

Gráfico temporal do faturamento mensal para os registros com datas válidas.

### Mix de modelos

Ranking dos modelos com maior volume de registros na seleção atual.

### Performance por cidade

Comparação das cidades com maior faturamento.

### Faturamento por método de pagamento

Análise da contribuição financeira de cada modalidade de pagamento.

### Distribuição por ano-modelo

Comparação do volume de registros entre os anos-modelo.

### Estados com maior faturamento

Ranking dos estados com maior contribuição para a receita registrada.

### Modelo campeão por cidade — Market Pulse

O painel de análise por cidade utiliza um seletor para consultar um mercado específico, em vez de apresentar uma tabela extensa com todas as cidades.

Ao selecionar uma cidade, a proposta é apresentar:

- Modelo líder em quantidade de vendas;
- Quantidade de registros do modelo líder;
- Participação do modelo nas vendas registradas da cidade;
- Faturamento total da cidade.

A análise deve acompanhar os filtros ativos da dashboard. Caso exista empate na liderança, ele deve ser tratado sem atribuir arbitrariamente a vitória a um único modelo.

### Leituras para decisão

Insights calculados a partir dos registros filtrados, incluindo mercado líder por faturamento, ano-modelo de maior volume, método de pagamento com maior receita e modelo mais frequente.

## Tecnologias utilizadas

- HTML5 — estrutura da aplicação;
- CSS3 — identidade visual, layout e responsividade;
- JavaScript — filtros, cálculos, indicadores e atualização dos gráficos;
- HTML Canvas — renderização do gráfico temporal;
- Git e GitHub — versionamento e publicação;
- GitHub Pages — hospedagem estática da dashboard.

## Dados e critérios de análise

A aplicação utiliza uma base incorporada ao arquivo HTML.

Os indicadores representam os registros disponíveis no conjunto de dados utilizado no projeto. A série temporal considera apenas registros com datas válidas; os demais indicadores seguem os critérios de filtragem implementados na aplicação.

Os resultados não devem ser interpretados como estatísticas oficiais de vendas da Porsche. Antes da publicação, devem ser conferidos os critérios da base original, incluindo eventuais registros cancelados, pendentes ou em trânsito.

## Como executar localmente

1. Baixe ou clone este repositório.
2. Localize o arquivo `index.html`.
3. Abra o arquivo em um navegador atualizado.
4. Experimente os filtros e compare os indicadores.
5. Utilize a opção de limpar filtros para restaurar a visualização.

A versão estática foi desenvolvida para funcionar diretamente no navegador, sem exigir instalação de dependências para sua execução básica.

## Estrutura do repositório

```text
porsche-sales-intelligence/
├── index.html
├── README.md
└── images/
    ├── dashboard-geral.png
    ├── dashboard-filtros.png
    ├── dashboard-evolucao.png
    └── dashboard-market-pulse.png
```

## Publicação

A dashboard pode ser publicada gratuitamente pelo GitHub Pages.

**Dashboard online:** inserir aqui o endereço publicado após a ativação do GitHub Pages.

**Repositório:** inserir aqui o endereço deste repositório.

## Contexto educacional

Projeto desenvolvido para fins educacionais durante a trilha de formação da DIO, com foco em análise de dados, visualização de indicadores e construção de dashboards interativas.

## Autor

**Ivan Moyses Ramos**

Projeto educacional — Porsche Sales Intelligence.
