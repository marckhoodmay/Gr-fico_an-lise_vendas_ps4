# 🎮 PS4 Games Sales Analysis — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![ETL](https://img.shields.io/badge/ETL-Power_Query-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 📌 Visão Geral do Projeto
Este projeto consiste em um dashboard analítico focado no desempenho comercial da biblioteca de jogos do **PlayStation 4**. 

O objetivo principal foi transformar uma base bruta com inconsistências de escala e duplicadas em um painel executivo dinâmico, fornecendo leitura imediata sobre volume total de vendas globais, mercado europeu, distribuição por gêneros e os títulos mais vendidos da plataforma.

---

## 📷 Dashboard

![Dashboard de Vendas PS4](https://github.com/user-attachments/assets/66c34723-f424-429f-885e-4671b2e3d0dc
 )



 *Nota: O layout foi desenvolvido em Dark Theme minimalista de alto contraste para otimizar a leitura rápida das métricas.*

---

##  Processo de ETL e Tratamento de Dados (Power Query)
Durante a fase de carga e exploração dos dados, identificou-se que nem o Excel nem a importação nativa do Power BI conseguiram extrair a escala numérica corretamente (exibindo valores de vendas na casa do milhar de forma distorcida). 

Para garantir a integridade analítica e a confiabilidade dos números, foram realizadas as seguintes etapas no **Power Query**:

1. **Desduplicação de Registros:** Limpeza e remoção de linhas duplicadas para eliminar contagens repetidas e garantir a unicidade de cada título.
2. **Transformação Matemática e Ajuste de Escala:** Correção dos valores numéricos para refletir a escala real em **Milhões de Unidades Vendidas** (ex: padronização do *FIFA 17* para `10,94 Mi` / `10.940.000` de cópias reais).
3. **Modelagem e Tipagem de Dados:** Reclassificação das colunas (Texto, Decimal, Inteiro) e criação das medidas necessárias para exibição nos cartões de KPIs.

---

## 📊 Principais Insights Mapeados

* **Volume Comercial Global:** O relatório consolida mais de **544,03 Milhões de cópias vendidas** em todo o mundo.
* **Fatia do Mercado Europeu:** A Europa representa **243,21 Milhões de unidades**, sendo um dos principais motores de receita da plataforma.
* **Gênero Dominante:** Os gêneros **Shooter** (37,08 Mi) e **Action** lideram isoladamente a preferência de consumo dos jogadores.
* **Líder Absoluto de Vendas:** **Grand Theft Auto V** é o título nº 1 em vendas no PS4, alcançando a marca de **19,39 Milhões de cópias**.
* **Escopo da Análise:** Cobertura total de um catálogo composto por **824 jogos distintos**.

---

## 🛠️ Tecnologias Utilizadas

* **Power BI Desktop:** Construção do layout, gráficos de barras horizontais ajustados para leitura em eixos e cartões de métricas superiores.
* **Power Query (M):** Limpeza, eliminação de duplicatas e transformação da escala de dados (ETL).
* **Dataset (Kaggle/VGChartz):** Dados brutos de vendas da indústria de games.

---

## ✒️ Autor
Desenvolvido por **Marco Antonio**.
