# 📊 Dashboard de Vendas em Excel

## 📌 Sobre o Projeto
Este projeto apresenta um **dashboard interativo de vendas** desenvolvido no **Microsoft Excel**.  
Os dados são **100% fictícios** e foram criados apenas para fins de estudo e portfólio.  

O objetivo é demonstrar como estruturar uma base de dados, enriquecer informações (como DDD → Estado/Região), aplicar **tabelas dinâmicas** e consolidar tudo em um **dashboard moderno, dinâmico e visualmente atraente**.

---

## 🛠️ Ferramentas e Técnicas Utilizadas
- **Microsoft Excel**  
- **Tabelas Dinâmicas**  
- **Segmentações de Dados** (Ano e Produto)  
- **Relacionamento entre tabelas (base de vendas + DDD)**  
- **Gráficos personalizados** (colunas, linha, área, mapa do Brasil)  
- **Design em tema Dark Mode**  

---

## 📂 Estrutura do Repositório
- `Dashboard de Vendas em Excel.xlsx` → Arquivo principal do dashboard  
- `README.md` → Documentação do projeto  

---

## 📑 Preparação da Base de Dados

### 1. Base de Vendas
Planilha contendo as seguintes colunas:
- Produto (A, B, C)  
- Preço da venda  
- Forma de pagamento (Cartão de Crédito / Boleto Bancário)  
- Nº de parcelas  
- Tipo de parcelamento (à vista ou parcelado)  
- Data da compra  
- Dados do cliente (nome, e-mail, telefone, servidor de e-mail)  
- DDD, Estado e Região  

### 2. Base de DDD
Planilha auxiliar com os prefixos telefônicos (DDD) e sua relação com:
- Estado  
- Região (Norte, Nordeste, Sudeste, Sul, Centro-Oeste)  

Essa tabela foi usada para **enriquecer os dados de vendas**, permitindo criar análises regionais.

---

## 📊 Tabelas Dinâmicas Criadas

### 1. Vendas Trimestrais por Produto
- **Linhas**: Trimestres  
- **Colunas**: Produtos  
- **Valores**: Soma de Preço  

➡️ Usada para mostrar os **totais por trimestre** e base para os gráficos de colunas por produto.  

---

### 2. Análise Regional e Forma de Pagamento
- **Total de vendas por Região** (quantidade de registros por região do Brasil)  
- **% de vendas por meio de pagamento** (Cartão de Crédito x Boleto Bancário)  

➡️ Serviram de base para o **mapa do Brasil** e para os cartões de indicadores (% de pagamentos).  

---

### 3. Faturamento Mensal e Percentual
- **Linhas**: Meses  
- **Valores**: Faturamento total e % sobre o ano  

➡️ Usada para identificar sazonalidade e transformada no **gráfico de linha + área azul**.  

---

### 4. Faturamento Mensal por Produto
- **Linhas**: Produtos  
- **Colunas**: Meses  
- **Valores**: Soma de Preço  

➡️ Usada para comparar os produtos ao longo dos meses.  

---

## 📊 Análises no Dashboard

O dashboard consolidou as tabelas dinâmicas em **gráficos interativos**, com destaque para:

1. **Resumo Superior**  
   - Total de vendas por produto (A, B, C).  
   - Faturamento total consolidado.  

2. **Gráfico de Linha + Área**  
   - Faturamento mensal.  
   - Percentual de impacto (% de cada mês sobre o total do ano).  

3. **Análise Regional**  
   - Mapa do Brasil mostrando quantidade de vendas por região.  
   - Indicadores laterais com % de forma de pagamento.  

4. **Gráficos Trimestrais por Produto**  
   - Colunas separadas para Produto A, Produto B e Produto C.  
   - Comparativo de faturamento por trimestre.  

---

## 🎮 Interatividade
Foram adicionadas **segmentações de dados** que permitem ao usuário:  
- Selecionar o **Ano** (2018, 2019 ou 2020).  
- Selecionar o **Produto** (A, B ou C).  

Ao mudar qualquer filtro, todos os gráficos e análises do dashboard são atualizados automaticamente.  

---

## 🚀 Como Usar
1. Baixe o arquivo `Dashboard de Vendas em Excel.xlsx`.  
2. Abra no Excel.  
3. Use os botões de **segmentação de dados** para interagir com o dashboard.  

---

## 📌 Observações
- Todos os dados são **fictícios**.  
- Projeto desenvolvido apenas para **estudo, prática e portfólio**.  

---

## 📄 Licença
Este dashboard foi desenvolvido como exercício a partir de uma aula gratuita da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).  
Todos os dados são fictícios e foram utilizados apenas para fins de estudo.
