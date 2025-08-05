# **BR Income Inequality Mapping**  
**Mapeamento espacial e temporal da desigualdade de renda no Brasil**  

---

## 📌 **Visão Geral**  
Este projeto visa analisar e visualizar a desigualdade de renda no Brasil em diferentes escalas (nacional, estadual e municipal) ao longo do tempo. Utilizando dados socioeconômicos, o mapeamento permite:  

- **Identificar regiões com maior concentração de renda**  
- **Comparar desigualdades entre estados e municípios**  
- **Analisar tendências temporais (2000-2023)**  
- **Correlacionar desigualdade com indicadores sociais (educação, saúde, emprego)**  
- **Gerar mapas interativos e relatórios automatizados**  

---

## 📊 **Fontes de Dados**  
- **[IBGE (Censo, PNAD Contínua)](https://www.ibge.gov.br/)**  
- **[Atlas do Desenvolvimento Humano (PNUD)](http://www.atlasbrasil.org.br/)**  
- **[RAIS/CAGED (Ministério do Trabalho)](https://www.gov.br/trabalho/pt-br)**  
- **[IPEA Data](https://www.ipeadata.gov.br/)**  
- **[World Inequality Database](https://wid.world/)**  

---

## 🛠️ **Tecnologias Utilizadas**  
- **Python** (Pandas, GeoPandas, NumPy)  
- **R** (Análises estatísticas avançadas, se necessário)  
- **SQL/PostgreSQL** (Armazenamento de dados)  
- **Plotly/Dash** (Visualização interativa)  
- **Leaflet/Kepler.gl** (Mapas dinâmicos)  
- **Scikit-learn/Statsmodels** (Modelos de desigualdade)  

---

## 📂 **Estrutura do Projeto**  

```
br-income-inequality-mapping/  
├── data/  
│   ├── raw/                 # Dados brutos (microdados, shapefiles)  
│   ├── processed/           # Dados tratados (CSV, GeoJSON)  
│   └── outputs/             # Mapas, relatórios e análises consolidadas  
├── notebooks/               # Análises exploratórias (Jupyter/RMarkdown)  
├── scripts/  
│   ├── data_processing/     # ETL e limpeza de dados  
│   ├── modeling/            # Cálculo de índices (Gini, Theil, Palma)  
│   └── visualization/       # Geração de mapas e gráficos  
├── app/                     # Dashboard interativo (Dash/Shiny)  
│   ├── assets/              # Estilos e recursos visuais  
│   ├── layouts/             # Componentes do painel  
│   └── callbacks/           # Lógica de interação  
├── docs/                    # Documentação técnica e metodológica  
└── README.md                # Este arquivo  
```

---

## 🚀 **Como Executar**  

### **Pré-requisitos**  
- Python 3.10+  
- R (opcional para análises estatísticas)  
- PostgreSQL (opcional para grandes datasets)  

### **Instalação**  
1. Clone o repositório:  
   ```bash  
   git clone https://github.com/seu-usuario/br-income-inequality-mapping.git  
   cd br-income-inequality-mapping  
   ```  

2. Configure o ambiente virtual:  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # Linux/Mac  
   .\venv\Scripts\activate   # Windows  
   ```  

3. Instale as dependências:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Processe os dados:  
   ```bash  
   python scripts/data_processing/main_etl.py  
   ```  

5. Execute o dashboard:  
   ```bash  
   python app/app.py  
   ```  
   Acesse **http://localhost:8050** para interagir com os mapas.  

---

## 📈 **Principais Métricas Analisadas**  
✔ **Coeficiente de Gini** (desigualdade de renda)  
✔ **Razão 10%/40% (Índice Palma)**  
✔ **Renda média dos 1% mais ricos vs. 50% mais pobres**  
✔ **Mobilidade intergeracional de renda**  
✔ **Desigualdade racial e de gênero**  

---

## 🌍 **Visualizações Disponíveis**  
✅ **Mapas temáticos** (desigualdade por município)  
✅ **Séries temporais** (evolução da desigualdade)  
✅ **Gráficos de dispersão** (renda vs. IDH, educação, etc.)  
✅ **Rankings comparativos** (estados/municípios)  
✅ **Exportação de relatórios** (PDF, Excel, GeoJSON)  

---

## 🤝 **Como Contribuir**  
1. **Sugira melhorias** (abrir uma *issue*)  
2. **Adicione novas fontes de dados** (envie um *PR*)  
3. **Melhore a documentação ou visualizações**  

---

## 📜 **Licença**  
**MIT License** - Consulte [LICENSE](LICENSE) para detalhes.  

---

## ✉️ **Contato**  
**Equipe de Economia Aplicada** - desigualdade.br@exemplo.com  

🔗 **Link do Projeto**: [github.com/seu-usuario/br-income-inequality-mapping](https://github.com/seu-usuario/br-income-inequality-mapping)  

---  

**Dados para um Brasil mais justo e igualitário!** 📊🌱