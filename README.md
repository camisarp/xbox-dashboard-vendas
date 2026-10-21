# Xbox Sales Intelligence | Dashboard Interativo de Vendas 🎮

<p align="center">
  <img src="images/visao-geral.png" alt="Visão geral do Xbox Sales Intelligence" width="950">
</p>

**Uma solução de análise de vendas em Microsoft Excel com quatro dashboards interativos, indicadores dinâmicos, gráficos e navegação integrada.**

O **Xbox Sales Intelligence** transforma uma base de assinaturas Xbox em uma experiência visual de acompanhamento comercial. O projeto reúne análises de faturamento, planos, modalidades de assinatura, renovação automática, complementos **EA Play** e **Minecraft**, além do acompanhamento de metas.

Desenvolvido como projeto prático de aprendizado no **Santander Bootcamp Excel com Inteligência Artificial, da DIO**, com ampliação e personalização do dashboard de referência utilizado nas aulas.

📊 **[Baixar a planilha Excel](Dashboard%20Xbox.xlsx)** · [Ver os dashboards](#demonstração-visual)

> **Importante:** os valores apresentados são de uma base demonstrativa do desafio e não representam dados de vendas oficiais da Xbox. Para utilizar os filtros, gráficos e botões de navegação, abra o arquivo preferencialmente no **Microsoft Excel para desktop**.

## Objetivo

Construir um painel de acompanhamento comercial que permita responder, de maneira rápida, a perguntas como:

- Qual é o faturamento total das assinaturas?
- Quantas assinaturas foram registradas e qual é o ticket médio?
- Quais planos e modalidades geram mais receita?
- Qual é a participação das assinaturas com renovação automática?
- Quanto EA Play e Minecraft representam nas receitas dos complementos?
- Quais metas de faturamento e renovação já foram atingidas? Quanto ainda falta?

## Destaques do projeto

- **Quatro dashboards especializados** com a mesma identidade visual.
- **Segmentação de dados interativa** por modalidade: Monthly, Quarterly e Annual.
- **Cards de KPIs vinculados aos cálculos**, atualizados conforme a seleção.
- **Gráficos comparativos** para análise de faturamento, assinaturas, renovação e metas.
- **Tabelas dinâmicas e fórmulas** organizadas em uma aba de apoio.
- **Menu lateral navegável** com hiperlinks internos, sem necessidade de VBA.
- **Identidade visual personalizada**, com ícones SVG, avatar, paleta inspirada no Xbox e layout consistente.

## Indicadores principais

Os números abaixo ilustram a **visão consolidada, sem filtros**:

| Indicador | Resultado |
|---|---:|
| Faturamento total | **R$ 7.633,00** |
| Total de assinaturas | **295** |
| Ticket médio | **R$ 25,87** |
| Renovação automática | **50,17%** |
| Receita EA Play | **R$ 2.940,00** |
| Receita Minecraft | **R$ 3.880,00** |
| Atingimento da meta de faturamento | **89,80%** |
| Atingimento da meta de renovação | **83,62%** |

*Os resultados dos dashboards mudam quando a segmentação de modalidades é utilizada. As metas permanecem como referências de comparação.*

## Estrutura da pasta de trabalho

| Aba | Finalidade |
|---|---|
| **BASES** | Dados de origem das assinaturas Xbox, planos, modalidades e complementos. |
| **CÁLCULOS** | Tabelas dinâmicas, fórmulas, consolidações e indicadores usados pelos dashboards. |
| **VISÃO GERAL** | Faturamento total, assinaturas, ticket médio, renovação e desempenho por plano. |
| **VENDAS** | Receitas por plano e modalidade, renovação automática e identificação dos líderes. |
| **COMPLEMENTOS** | Receitas, participação e quantidades relacionadas a EA Play e Minecraft. |
| **METAS E OKRs** | Acompanhamento da receita e da renovação frente às metas estabelecidas. |

## Demonstração visual

### 1. Visão Geral — panorama executivo

Indicadores principais e comparação de faturamento e volume de assinaturas por plano.

![Dashboard Visão Geral](images/visao-geral.png)

### 2. Vendas — desempenho comercial

Análise de receita por plano, modalidade e renovação automática, com destaque para os líderes de faturamento.

![Dashboard Vendas](images/vendas.png)

### 3. Complementos — EA Play e Minecraft

Receitas individuais, participação de cada complemento, quantidades de assinaturas e identificação do complemento líder.

![Dashboard Complementos](images/complementos.png)

### 4. Metas e OKRs — resultados e objetivos

Comparação entre faturamento realizado e meta, percentuais de atingimento e distância para alcançar os objetivos.

![Dashboard Metas e OKRs](images/metas-e-okrs.png)

<details>
<summary><strong>Ver a estrutura de apoio: BASES e CÁLCULOS</strong></summary>

#### Base de dados

![Aba BASES](images/base-de-dados.png)

#### Tabelas dinâmicas e indicadores

![Aba CÁLCULOS](images/calculos.png)

</details>

## Recursos do Excel utilizados

- **Tabelas dinâmicas** para consolidar vendas por plano, modalidade e renovação;
- **Segmentação de dados** conectada às análises;
- **Fórmulas e referências entre planilhas**, incluindo busca de valores em tabelas dinâmicas e tratamento de erros;
- **Gráficos de barras e colunas**, com rótulos de dados e escalas ajustadas;
- **Indicadores e comparações percentuais** para acompanhamento de metas;
- **Formatação personalizada, ícones SVG e elementos visuais**;
- **Hiperlinks entre abas** para navegação.

## Como utilizar

1. **[Baixe o arquivo Excel](Dashboard%20Xbox.xlsx)** disponível neste repositório.
2. Abra-o no **Microsoft Excel para desktop**.
3. Comece pela aba **VISÃO GERAL**.
4. Use **FILTRAR MODALIDADE** para selecionar Annual, Monthly, Quarterly ou combinar modalidades.
5. Navegue entre **VENDAS**, **COMPLEMENTOS** e **METAS E OKRs** pelo menu lateral.
6. Consulte a aba **CÁLCULOS** caso queira estudar as tabelas e as fórmulas usadas.
7. Se alterar a base de dados, utilize **Dados → Atualizar Tudo** e valide o intervalo de origem das tabelas dinâmicas.

> **Observação:** os indicadores de complementos são apurados separadamente por produto. A mesma assinatura pode incluir EA Play e Minecraft; portanto, suas quantidades não representam grupos necessariamente exclusivos.

## Decisões de desenvolvimento

O arquivo foi dividido em uma **camada de dados** (BASES), uma **camada de processamento** (CÁLCULOS) e uma **camada de apresentação** (quatro dashboards). Essa separação facilita a conferência dos resultados e a evolução da solução.

A interface visual foi desenvolvida para manter consistência entre páginas: menu lateral, filtros, cartões de indicadores, dois gráficos por área analítica e destaques adicionais. A navegação funciona com recursos nativos do Excel, sem macros.

O dashboard didático inicial serviu como **referência de aprendizagem**. A organização das quatro páginas, os indicadores adicionais, a navegação e a personalização visual integram a evolução desenvolvida para este portfólio.

## Aprendizados

O projeto reforçou a construção de **dashboards orientados a perguntas de negócio**, a ligação entre tabelas dinâmicas e indicadores, o uso responsável das escalas dos gráficos e a importância de testar filtros, fórmulas e navegação antes de publicar uma solução.

## Autoria e créditos

**Desenvolvimento e personalização:** [@camisarp](https://github.com/camisarp) · [LinkedIn](https://www.linkedin.com/in/camila-ribeiro-pinto/)

**Contexto educacional:** Santander Bootcamp Excel com Inteligência Artificial — [DIO](https://www.dio.me/).

*Projeto desenvolvido para fins de estudo e portfólio, a partir de uma base demonstrativa e de material didático do curso.*
