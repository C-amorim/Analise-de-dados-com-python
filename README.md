# 📊 Análise de Dados de Cancelamentos - Empresa de Streaming

## 📝 Descrição do Projeto

Este projeto realiza uma análise completa sobre as causas de cancelamento em uma empresa de streaming. Através de técnicas de análise exploratória de dados, identificamos padrões, tendências e os principais fatores que levam clientes a cancelarem seus serviços.

O objetivo é fornecer insights acionáveis que possam ajudar a empresa a reduzir a taxa de cancelamento e melhorar a retenção de clientes.

## 🎯 Objetivos

- 📈 Identificar as principais causas de cancelamento de serviços
- 🔍 Analisar padrões demográficos e comportamentais dos clientes que cancelam
- 💡 Descobrir correlações entre variáveis e cancelamentos
- 📊 Gerar visualizações claras e insights acionáveis
- 🎓 Demonstrar habilidades em análise de dados com Python

## 📂 Estrutura do Projeto

```
Analise-de-dados-com-python/
│
├── Analise_de_Dados/
│   ├── cancelamentos.csv          # Dataset com dados de cancelamentos
│   └── inicial.ipynb              # Notebook Jupyter com análise completa
│
└── README.md                       # Este arquivo
```

## 📊 Dataset

O arquivo `cancelamentos.csv` contém dados sobre clientes de uma empresa de streaming, incluindo:

- **Informações pessoais**: ID do cliente, idade, gênero
- **Contato**: email, telefone
- **Assinatura**: duração do serviço, tipo de plano
- **Comportamento**: meses como cliente, últimas interações
- **Status**: indicador de cancelamento (sim/não)

**Tamanho**: ~3.5 MB com centenas de milhares de registros

## 🛠️ Tecnologias Utilizadas

- **Python 3** - Linguagem de programação
- **Jupyter Notebook** - Ambiente interativo para análise
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Computação numérica
- **Plotly** - Visualização de gráficos
- **ipykernel** - Executa o código Python dentro do Jupyter Notebook.
- **nbformat** - ferramenta de infraestrutura do Jupyter.

## 🚀 Como Executar

### Pré-requisitos

Você precisa ter instalado:
- Python 3.7 ou superior
- Pip (gerenciador de pacotes do Python)

### Instalação

1. **Clone o repositório**:
```bash
git clone https://github.com/C-amorim/Analise-de-dados-com-python.git
cd Analise-de-dados-com-python
```

2. **Crie um ambiente virtual** (recomendado):
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

3. **Instale as dependências**:
```bash
pip install pandas numpy openpyxl nbformat ipykernel plotly
```

4. **Inicie o Jupyter Notebook**:
```bash
jupyter notebook
```

5. **Abra o arquivo** `Analise_de_Dados/inicial.ipynb` e execute as células

## 📈 Principais Descobertas

Nesta análise, descobrimos insights valiosos sobre:

- ✅ Quais características dos clientes estão mais associadas a cancelamentos
- ✅ Padrões temporais de cancelamento
- ✅ Fatores de risco que indicam probabilidade de churn
- ✅ Recomendações para melhorar a retenção de clientes

*Consulte o notebook para visualizações e análises detalhadas*

## 📚 Metodologia

1. **Carregamento e Limpeza de Dados**
   - Importação do CSV
   - Verificação de valores faltantes
   - Tratamento de dados inconsistentes

2. **Exploração e Análise**
   - Estatísticas descritivas
   - Análise univariada de variáveis
   - Correlações entre variáveis

3. **Visualizações**
   - Histogramas e boxplots
   - Gráficos de distribuição
   - Correlações em heatmaps

4. **Insights e Conclusões**
   - Resumo dos principais achados
   - Recomendações baseadas em dados

## 💻 Usando o Notebook

O arquivo `inicial.ipynb` contém:

- Código comentado e explicado
- Células executáveis passo a passo
- Gráficos e visualizações interativas
- Conclusões e insights destacados

Você pode executar as células individualmente para entender cada etapa da análise.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tem ideias para melhorar a análise:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaAnalise`)
3. Commit suas mudanças (`git commit -m 'Adicionei análise de ...'`)
4. Push para a branch (`git push origin feature/MinhaAnalise`)
5. Abra um Pull Request

## 📧 Contato

Para dúvidas ou sugestões sobre este projeto, entre em contato:

- **GitHub**: [@C-amorim](https://github.com/C-amorim)

## 📄 Licença

Este projeto é de código aberto e disponível sob a licença MIT.

---

**Criado em**: 2026  
**Última atualização**: Março de 2026

*Obrigado por visitar este projeto! Esperamos que os insights aqui encontrados sejam valiosos para você.* 🎉
