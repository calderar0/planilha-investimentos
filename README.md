# Planilha de Controle de Investimentos

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg?style=for-the-badge)

Uma planilha completa e automatizada para o controle e acompanhamento de seus investimentos pessoais. Desenvolvida para facilitar a visualização da rentabilidade, alocação de ativos e o histórico de operações de forma simples e eficiente.

## 🎯 Objetivo do Projeto

O objetivo desta planilha é oferecer uma ferramenta gratuita e poderosa para investidores que desejam ter um controle mais apurado sobre sua carteira de investimentos, sem a necessidade de assinar plataformas pagas. Ela centraliza as informações e automatiza cálculos importantes como preço médio, rentabilidade e evolução patrimonial.

## ✨ Funcionalidades Principais

* **Dashboard Intuitivo:** Uma tela principal (`APP`) com um resumo completo da carteira, incluindo patrimônio total, rentabilidade e gráficos visuais.
* **Controle de Múltiplos Ativos:** Gerencie diferentes classes de ativos, como Ações, Fundos Imobiliários (FIIs), BDRs, Criptomoedas, etc.
* **Lançamento de Operações:** Uma base de dados (`BaseDados`) dedicada para registrar todas as suas operações de compra e venda.
* **Cálculo de Preço Médio:** O preço médio de cada ativo é calculado automaticamente com base nos seus lançamentos.
* **Análise de Rentabilidade:** Acompanhe a performance geral da sua carteira e também o resultado individual de cada ativo.
* **Visualização Gráfica:**
    * Gráfico de Alocação de Ativos (Pizza): Veja como seu patrimônio está distribuído.
    * Gráfico de Evolução Patrimonial (Linhas): Monitore o crescimento do seu patrimônio ao longo do tempo.

## 📂 Estrutura da Planilha

A planilha é dividida em duas abas principais, cada uma com uma função específica:

### 📄 `BaseDados`
O coração da planilha. É nesta aba que você deve **registrar todas as suas operações financeiras** (compras e vendas de ativos). A precisão das informações inseridas aqui é fundamental para que os cálculos no Dashboard funcionem corretamente.

As colunas geralmente incluem:
* **Data:** Data em que a operação foi realizada.
* **Ativo:** O código de negociação do ativo (ex: `PETR4`, `MXRF11`).
* **Tipo:** O tipo de operação (`Compra` ou `Venda`).
* **Quantidade:** Número de cotas/ações negociadas.
* **Preço Unitário:** O valor pago ou recebido por cada unidade do ativo.
* **Custos:** Taxas de corretagem e impostos, se houver.
* **Valor Total:** O montante total da operação (calculado automaticamente).

### 📊 `APP`
O seu painel de controle (Dashboard). Esta aba é **totalmente automatizada** e serve para a visualização dos dados. Ela lê as informações da `BaseDados` e as transforma em gráficos e resumos fáceis de entender. Você não precisa editar nada aqui.

## 🚀 Como Utilizar

1.  **Download:** Faça o download do arquivo `.xlsx` deste repositório clicando em `Code` -> `Download ZIP`.
2.  **Software:** Abra a planilha no Microsoft Excel (recomendado para total compatibilidade de fórmulas) ou no Google Sheets.
3.  **Registre suas Operações:**
    * Vá para a aba `BaseDados`.
    * Preencha uma nova linha para cada operação de compra ou venda que você realizar, seguindo as colunas existentes.
4.  **Acompanhe os Resultados:**
    * Volte para a aba `APP`.
    * Pronto! Todos os gráficos e informações serão atualizados automaticamente com base nos novos dados que você inseriu.

## 🛠️ Detalhes Técnicos

Esta planilha utiliza fórmulas intermediárias e avançadas do Excel/Google Sheets (como `SOMASES`, `PROCV`, `SE`, e possivelmente tabelas dinâmicas) para agregar e calcular os dados. **Não são utilizadas macros (VBA)**, o que torna o arquivo mais seguro, leve e compatível entre diferentes sistemas operacionais e softwares de planilha.

## 🤝 Como Contribuir

Este é um projeto aberto e contribuições são muito bem-vindas! Se você tiver ideias para novas funcionalidades, melhorias de fórmulas ou encontrar algum bug, sinta-se à vontade para:

* Abrir uma **Issue** para discutir o que você gostaria de mudar.
* Enviar um **Pull Request** com as suas melhorias.

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
