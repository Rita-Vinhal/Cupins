# 🌍 Dados do Repositório / Repository Data

<p align="center">
  <a href="#-português">Português</a> •
  <a href="#-english">English</a>
</p>

---

## 🇧🇷 Português

O conjunto de dados, originalmente nomeado `mesocosm_processed.csv`, agora `Dados do Repositório.csv`, contém o conjunto de dados processados com as taxas de produção de $CO_2$ e $CH_4$ calculadas a partir das medições brutas do IRGA fornecidas no arquivo de dados `mesocosm_gas_data.csv`. 

Há **112 linhas** de dados e **20 colunas**, cada linha contendo dados para um único mesocosmo. As descrições dos dados para cada coluna são as seguintes:

### 🗂️ Dados

| Coluna | Descrição |
| :--- | :--- |
| **`local`** | Sequência única que identifica quando a medição de gás foi realizada. |
| **`etiqueta`** | Código único que identifica cada mesocosmo. |
| **`data`** | Data em que as medições foram feitas (dd/mm/aaaa). |
| **`Tcham`** | Temperatura da câmara (em °C). |
| **`wt_calculated_kg`** | Peso calculado do monte, estimado a partir do volume do monte e usando parâmetros de regressão de pesos e volumes conhecidos do monte (em kg). |
| **`volume_m3`** | Volume do monte calculado a partir das medições de diâmetro e altura, assumindo um paraboloide (em m³). |
| **`resp`** | Taxa de respiração (produção de $CO_2$) (em $\mu g\ CO_2\ g^{-1}\ s^{-1}$). |
| **`date_since_start`** | Número de dias desde o início do experimento no mesocosmo. |
| **`metano`** | Taxa de produção de metano (em $\mu g\ CH_4\ g^{-1}\ s^{-1}$). |
| **`avg_wt`** | Peso médio do monte durante a duração do experimento no mesocosmo (em kg). |
| **`species_code`** | Código de identificação único para o tipo de madeira (*veja a lista abaixo*). |
| **`peso_inicial`** | Peso inicial da madeira fornecida ao mesocosmo (em gramas). |
| **`peso_final`** | Peso final da madeira restante ao final do experimento mesoscópico (em gramas). |
| **`densidade_da_madeira`**| Densidade média da madeira (em g/cm³). |
| **`mean_C`** | Teor médio de carbono (em %). |
| **`mean_N`** | Teor médio de nitrogênio (em %). |
| **`média_S.G`** | Proporção de siringil : guaiacil. |
| **`pH_médio`** | pH médio. |
| **`C.N. médio`** | Relação entre o teor de carbono e o teor de nitrogênio. |
| **`Estação`** | Estação do ano em que as medições foram feitas (SECA ou CHUVOSA). |

### 🪵 Códigos das Espécies de Madeira (`species_code`)
* **ALSC** = *Alstonia scholaris*
* **ARPE** = *Argyrodendron peralatum*
* **CAAU** = *Castanospermum australe*
* **CASU** = *Cardwellia sublimis*
* **CLOB** = *Cleistanthus oblongifolius*
* **DYPA** = *Dysoxylum papuanum*
* **EUCU** = *Eucalyptus cullenii*
* **EULE** = *Eucalyptus chlorophylla*
* **MEST** = *Melaleuca stenostachya*
* **MEVI** = *Melaleuca viridiflora*
* **MYGL** = *Myristica globosa*
* **SYSA** = *Syzygium sayeri*

---

## 🇺🇸 English

The dataset, originally named `mesocosm_processed.csv`, now `Dados do Repositório.csv`, contains the processed dataset with the production rates of $CO_2$ and $CH_4$ calculated from the raw IRGA measurements provided in the `mesocosm_gas_data.csv` data file. 

There are **112 rows** of data and **20 columns**, each row containing data for a single mesocosm. The data descriptions for each column are as follows:

### 🗂️ Data

| Column | Description |
| :--- | :--- |
| **`local`** | Unique sequence identifying when the gas measurement was performed. |
| **`etiqueta`** | Unique code identifying each mesocosm. |
| **`data`** | Date when measurements were taken (dd/mm/yyyy). |
| **`Tcham`** | Chamber temperature (in °C). |
| **`wt_calculated_kg`** | Calculated mound weight, estimated from the mound volume and using regression parameters of known mound weights and volumes (in kg). |
| **`volume_m3`** | Mound volume calculated from diameter and height measurements, assuming a paraboloid (in m³). |
| **`resp`** | Respiration rate ($CO_2$ production) (in $\mu g\ CO_2\ g^{-1}\ s^{-1}$). |
| **`date_since_start`** | Number of days since the start of the mesocosm experiment. |
| **`metano`** | Methane production rate (in $\mu g\ CH_4\ g^{-1}\ s^{-1}$). |
| **`avg_wt`** | Average mound weight during the duration of the mesocosm experiment (in kg). |
| **`species_code`** | Unique identification code for the wood type (*see list below*). |
| **`peso_inicial`** | Initial weight of the wood provided to the mesocosm (in grams). |
| **`peso_final`** | Final weight of the wood remaining at the end of the mesocosm experiment (in grams). |
| **`densidade_da_madeira`**| Average wood density (in g/cm³). |
| **`mean_C`** | Mean carbon content (in %). |
| **`mean_N`** | Mean nitrogen content (in %). |
| **`média_S.G`** | Syringyl : guaiacyl ratio. |
| **`pH_médio`** | Mean pH. |
| **`C.N. médio`** | Ratio between carbon content and nitrogen content. |
| **`Estação`** | Season of the year when measurements were taken (SECA [DRY] or CHUVOSA [RAINY]). |

### 🪵 Wood Species Codes (`species_code`)
* **ALSC** = *Alstonia scholaris*
* **ARPE** = *Argyrodendron peralatum*
* **CAAU** = *Castanospermum australe*
* **CASU** = *Cardwellia sublimis*
* **CLOB** = *Cleistanthus oblongifolius*
* **DYPA** = *Dysoxylum papuanum*
* **EUCU** = *Eucalyptus cullenii*
* **EULE** = *Eucalyptus chlorophylla*
* **MEST** = *Melaleuca stenostachya*
* **MEVI** = *Melaleuca viridiflora*
* **MYGL** = *Myristica globosa*
* **SYSA** = *Syzygium sayeri*

## 🌲 Motor Preditivo Eco-Flux |  Eco-Flux Predictive Engine

🇧🇷 **Português:**
Este repositório contém uma análise biogeoquímica avançada para dados de decomposição de madeira e fluxo de gases de efeito estufa. O script principal utiliza a estrutura `tidymodels` para aplicar Machine Learning (Random Forest) e modelagem preditiva, descobrindo quais atributos físicos e ambientais (como densidade da madeira, temperatura e nitrogênio) impulsionam a respiração de carbono.

**Principais Funcionalidades:**
* **Data Wrangling Dinâmico:** Tratamento automático de decimais em padrão brasileiro (vírgulas) e padronização de cabeçalhos utilizando o pacote `janitor`.
* **Gráficos de Assinatura Biogeoquímica:** Visualização de fluxos de emissão (em escala logarítmica) utilizando *Ridge Plots* para comparar espécies arbóreas e a sazonalidade (seca vs. chuva).
* **Machine Learning:** Modelo preditivo Random Forest (via `ranger`) acompanhado de um Gráfico de Importância de Variáveis (VIP) para isolar os maiores catalisadores da decomposição.

---

🇺🇸 **English:**
This repository contains an advanced biogeochemical analysis pipeline for wood decomposition and greenhouse gas flux data. The core script utilizes the `tidymodels` framework to apply Machine Learning (Random Forest) and predictive modeling, uncovering which physical and environmental traits (such as wood density, temperature, and nitrogen) drive carbon respiration.

**Key Features:**
* **Dynamic Data Wrangling:** Automatic parsing of Brazilian-standard decimals (commas) and header standardization using the `janitor` package.
* **Biogeochemical Signature Plots:** Visualization of emission fluxes (on a logarithmic scale) using *Ridge Plots* to compare tree species and seasonality (dry vs. wet seasons).
* **Machine Learning:** Random Forest predictive model (via `ranger`) accompanied by a Variable Importance Plot (VIP) to isolate the primary drivers of decomposition.
