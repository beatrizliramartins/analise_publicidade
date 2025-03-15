# 📊 Analisando Produtos  

## 🚀 Visão Geral  
Este código analisa dados de produtos e interações dos usuários para identificar padrões de compra.  

## 🛠️ Bibliotecas Utilizadas  
- `pandas` → Manipulação de dados  
- `matplotlib.pyplot` e `seaborn` → Visualizações  
- `numpy` → Operações matemáticas  
- `sklearn` → Preparação de dados  

## 📥 Importação e Prévia dos Dados  
- Lê o CSV (`Analise_Produtos.csv`) e transforma em um DataFrame.  
- Exibe as primeiras linhas com `head()`.  

## 📊 Visualizações  
- Histograma de "Itens vistos".  
- Gráficos de dispersão entre "Itens vistos", "Adicionados ao carrinho" e "Comprados".  
- `pairplot()` para visualizar correlações.  

## 🧹 Preparação dos Dados  
- Remove a coluna "Nome do item".  
- Separa variáveis (`X` e `Y`) e divide os dados em treino e teste.  
- Converte "Receita do item" para número.  

🔥 **Pronto para insights ou até um modelo preditivo!**  
 
