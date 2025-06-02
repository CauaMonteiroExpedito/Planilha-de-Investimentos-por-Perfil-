## 🧾 1. Objetivo

A planilha tem como objetivo apresentar **sugestões de alocação percentual em Fundos Imobiliários (FIIs)** conforme o perfil de investidor (Conservador, Moderado ou Agressivo). Essa estrutura permite definir estratégias coerentes com o apetite de risco de cada investidor.

---

## 🗂️ 2. Estrutura da Planilha

### **Aba Principal: “Investimentos”**

| Coluna        | Descrição                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------- |
| `CHAVE`       | Identificador único, composto por `Perfil-Tipo de FII`. Ex: `Moderado-TIJOLO`.               |
| `Perfil`      | Tipo de investidor: `Conservador`, `Moderado` ou `Agressivo`.                                |
| `TIPO DE FII` | Categoria de fundo: `PAPEL`, `TIJOLO`, `HIBRIDOS`, `FOF'S`, `DESENVOLVIMENTO`, `HOTELARIAS`. |
| `%`           | Percentual de alocação sugerido para aquele tipo de fundo no perfil correspondente.          |

---

## 📊 3. Tipos de Fundos (FII)

| Tipo                | Descrição técnica                                                              |
| ------------------- | ------------------------------------------------------------------------------ |
| **PAPEL**           | Fundos que investem majoritariamente em títulos de crédito imobiliário (CRIs). |
| **TIJOLO**          | Fundos que investem em imóveis físicos (ex: shoppings, galpões logísticos).    |
| **HIBRIDOS**        | Fundos que mesclam ativos físicos e de papel.                                  |
| **FOF’S**           | Fundos que investem em cotas de outros FIIs (Fundos de Fundos).                |
| **DESENVOLVIMENTO** | Fundos voltados à construção ou incorporação imobiliária. Maior risco.         |
| **HOTELARIAS**      | Fundos focados em empreendimentos hoteleiros. Alta volatilidade.               |

---

## 🧠 4. Estratégia por Perfil

### 🔹 **Conservador**

* Foco em **ativos previsíveis e seguros**.
* Maior peso em **TIJOLO (50%)** e **PAPEL (30%)**.
* Zero exposição a setores de maior risco como Desenvolvimento e Hotelarias.

### 🔹 **Moderado**

* Combinação equilibrada entre **segurança e crescimento**.
* Forte presença de TIJOLO e PAPEL (72%), com 28% distribuídos entre ativos mais voláteis.

### 🔹 **Agressivo** *(atualizado)*

* Portfólio mais ousado, voltado ao **potencial de valorização** com risco maior.
* Distribuição diversificada com maior alocação em Híbridos, FOF’s e Desenvolvimento (60%).

| Tipo de FII     | % Agressivo Atualizado |
| --------------- | ---------------------- |
| PAPEL           | 20%                    |
| TIJOLO          | 10%                    |
| HÍBRIDOS        | 20%                    |
| FOF'S           | 20%                    |
| DESENVOLVIMENTO | 20%                    |
| HOTELARIAS      | 10%                    |

---

## 🧮 5. Validações

* **Total por perfil**: Deve somar **100%**.
* **CHAVE única**: Combinação entre Perfil + Tipo de FII, sem duplicidades.
* **Tipos de FII padronizados**: Evitar variações ou erros de digitação.

---

## ⚙️ 6. Aplicações Técnicas

Esta planilha pode ser usada para:

* Geração de **relatórios de perfil de investidor**.
* **Cruzamento com carteira real** para sugerir rebalanceamentos.
* **Integração com sistemas de recomendação** em plataformas de investimentos.
* Visualização de **dashboards** com gráficos de pizza por perfil.
