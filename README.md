# Dashboard Controladoria

# ☕ Dashboard de Controladoria - DRE (XP Bucks Coffee Shop)

Este projeto consiste em um Dashboard Financeiro completo focado na **Demonstração do Resultado do Exercício (DRE)**. O objetivo é fornecer uma visão clara e hierárquica das finanças, permitindo análises comparativas entre **Realizado, Orçado (Meta) e Previsto (Forecast)**.

> **Nota:** O projeto está estruturado no formato **Power BI Project (.pbip)**, facilitando o versionamento e o trabalho colaborativo (CI/CD).

## ⚠️ Disclaimer
**Os dados apresentados neste dashboard são 100% fictícios.**
Este projeto foi desenvolvido para fins de demonstração de portfólio. Qualquer semelhança com valores reais de empresas existentes é mera coincidência.

## 📊 Visão Geral do Projeto

O painel simula a saúde financeira de uma rede de cafeterias (*XP Bucks*), aplicando conceitos avançados de modelagem financeira e Business Intelligence.

### Principais Funcionalidades:
* **DRE Gerencial Hierárquica:** Estrutura expansível (drill-down) desde a Receita Bruta até o Lucro Líquido.
* **Análise de Cenários:**
    * Realizado vs. Meta (Orçamento original).
    * Realizado vs. Previsto (Forecast ajustado).
* **Gráfico de Bridge (Waterfall):** Visualização clara de como as deduções e custos corroem a receita até chegar ao resultado final.
* **Storytelling Dinâmico:** Títulos e comentários que mudam automaticamente baseados na performance do mês selecionado.
* **Análises Temporais:** Visão Mensal e Acumulada (YTD) com indicadores visuais de variação.

## 📸 Screenshots

### 1. Visão Geral: Realizado vs Orçado
Comparativo detalhado com tabela hierárquica e indicadores de atingimento de meta.
<img width="1348" height="760" alt="image" src="https://github.com/user-attachments/assets/36f582b2-db10-466d-acd6-0d50201b5bc6" />

### 2. Análise de Cenários: Realizado vs Previsto
Foco no ajuste de forecast e tendências de curto prazo.

<img width="467" height="574" alt="image" src="https://github.com/user-attachments/assets/d3fb8f15-dc28-4f6b-97d9-64f1ee0a6b38" />

### 3. Gráfico de Bridge (Waterfall)
Explicação visual da composição do resultado.
<img width="826" height="459" alt="image" src="https://github.com/user-attachments/assets/637e6bf1-0b83-4443-a0ff-b0e451c9e4c5" />

---

## 🛠️ Estrutura do Repositório

O projeto utiliza a estrutura moderna de salvamento do Power BI (`.pbip`), separando definições de relatório e modelo semântico.

```text
/
├── .gitignore                          # Arquivos ignorados pelo Git
├── BaseDados.xlsx                      # Fonte de dados (Dados Fictícios)
├── Dashboard_controladoria_DRE.pbip    # Arquivo de inicialização do projeto
├── dashboard_controladoria_DRE.Report/ # Definições visuais e JSON do relatório
├── dashboard_controladoria_DRE.SemanticModel/ # Modelo de dados, medidas DAX e metadados
└── layout/                             # Recursos visuais externos
    ├── estilo/                         # Temas (JSON)
    ├── imagens/                        # Ícones e logos
    └── layouts/                        # Templates de fundo


