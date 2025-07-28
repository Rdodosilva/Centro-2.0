# 🚛 Dashboard Coleta Centro - Versão Melhorada

Dashboard interativo para gestão de coleta de resíduos e segurança no centro da cidade, desenvolvido com Streamlit.

## ✨ Principais Melhorias

### 🎨 Visual e Design
- **Tema Dark Futurista**: Interface escura com cores vibrantes (#00D4FF, #FF6B35)
- **Gráficos Translúcidos**: Fundos transparentes para efeito de flutuação
- **Layout Responsivo**: Organização otimizada em colunas e seções
- **Ícones e Emojis**: Interface mais intuitiva e atraente

### 📊 Novos Insights e Funcionalidades
- **Métricas com Variação**: Cartões que mostram tendências e comparações
- **Gráfico de Tendência**: Evolução diária da coleta ao longo do tempo
- **Análise Mensal Completa**: Visão geral de todos os meses
- **Filtros Avançados**: Seleção de períodos e datas flexíveis

### 🔄 Automação
- **Upload de Arquivo**: Interface para atualizar dados via upload
- **Cache Inteligente**: Atualização automática dos dados a cada 5 minutos
- **Validação de Dados**: Verificação automática da integridade dos dados

## 🚀 Como Usar

### Instalação
```bash
pip install -r requirements.txt
```

### Execução
```bash
streamlit run streamlit_app_melhorado.py
```

### Atualização de Dados
1. **Via Upload**: Use a barra lateral para fazer upload de uma nova planilha
2. **Via Arquivo**: Substitua o arquivo `coleta_centro_dados.xlsx` na pasta do projeto

## 📁 Estrutura de Arquivos

```
dashboard-coleta-centro/
├── streamlit_app_melhorado.py    # Aplicação principal
├── coleta_centro_dados.xlsx      # Dados de exemplo
├── requirements.txt              # Dependências
├── .streamlit/
│   └── config.toml              # Configurações de tema
└── README.md                    # Esta documentação
```

## 📊 Estrutura dos Dados

A planilha deve conter as seguintes colunas:
- **Mês**: Nome do mês (Janeiro, Fevereiro, etc.)
- **Coleta AM**: Quantidade de sacos coletados pela manhã
- **Coleta PM**: Quantidade de sacos coletados à tarde
- **Total de Sacos**: Soma de AM + PM

## 🎯 Funcionalidades Principais

### 📈 Métricas em Tempo Real
- Total de sacos coletados
- Peso total estimado
- Distribuição AM/PM
- Variações percentuais

### 📊 Visualizações Interativas
- Gráfico de barras por período
- Gráfico de pizza para distribuição
- Linha de tendência temporal
- Análise mensal comparativa

### 🔧 Filtros e Controles
- Seleção de mês específico
- Filtro de período para tendências
- Upload de novos dados
- Atualização automática

## 🎨 Personalização

### Cores do Tema
- **Primária**: #00D4FF (Azul ciano)
- **Secundária**: #FF6B35 (Laranja vibrante)
- **Fundo**: #0E1117 (Preto azulado)
- **Texto**: #FAFAFA (Branco suave)

### Modificações
Para personalizar o dashboard, edite:
- `streamlit_app_melhorado.py`: Lógica e visualizações
- `.streamlit/config.toml`: Cores e tema
- `coleta_centro_dados.xlsx`: Dados de exemplo

## 🔮 Próximas Funcionalidades

- [ ] Integração com Google Sheets
- [ ] Dados de segurança
- [ ] Alertas automáticos
- [ ] Relatórios em PDF
- [ ] API para integração externa

## 📞 Suporte

Para dúvidas ou sugestões sobre o dashboard, consulte a documentação ou entre em contato com a equipe de desenvolvimento.

---

**Desenvolvido para otimizar a gestão de coleta de resíduos no centro da cidade** 🏙️

