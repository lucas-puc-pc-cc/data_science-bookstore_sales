# 📚 Projeto de Previsão de Vendas de Livros

## 📌 Visão Geral

Este projeto tem como objetivo desenvolver um **modelo de previsão de vendas de livros**, utilizando dados históricos relacionados a autores, livros, editoras e livrarias. A proposta é estimar a quantidade potencial de vendas de um **novo livro**, considerando diferentes características e o desempenho histórico de vendas por autor e por livraria.

O foco principal está em compreender padrões de vendas e utilizar essas informações para apoiar decisões estratégicas, como distribuição de livros, parcerias com livrarias e planejamento editorial.

<hr>

## 🗂️ Conjunto de Dados

O projeto utiliza três tabelas principais, cada uma com um papel específico na construção da base analítica.

### 1. Tabela de Livros (`df`)

Contém informações detalhadas sobre os livros produzidos por autor.

**Colunas:**
- `livro`: Nome ou identificador do livro  
- `tema`: Gênero ou tema principal do livro  
- `autor`: Nome do autor  
- `editora`: Editora responsável pela publicação  
- `likes`: Quantidade de curtidas ou interações  
- `comentarios`: Quantidade de comentários ou feedbacks  

<hr>

### 2. Tabela de Vendas Totais por Autor (`df_vendas_totais`)

Apresenta o volume total de vendas agregadas por autor, sem detalhamento por livro ou livraria.

**Colunas:**
- `autor`: Nome do autor  
- `vendas`: Total de vendas realizadas  

<hr>

### 3. Tabela de Vendas por Livraria (`df_vendas_por_livraria`)

Registra as vendas totais de livros por autor em cada livraria.

**Colunas:**
- `autor`: Nome do autor  
- `livraria`: Identificação da livraria  
- `vendas`: Total de vendas do autor naquela livraria  

<hr>

## 🎯 Problema a Ser Resolvido

O desafio central do projeto é **prever as vendas de um novo livro**, mesmo sem histórico de vendas específico desse livro.

### Entrada Esperada do Modelo
- Autor  
- Livraria  
- Editora  
- Tema  

### Saída Esperada
- Quantidade estimada de livros vendidos por livraria  

<hr>

## 🔍 Objetivos do Projeto

- Integrar os dados de vendas totais por autor com os dados de vendas por livraria  
- Analisar o comportamento de vendas dos autores em diferentes livrarias  
- Avaliar a influência de variáveis como tema, editora e autor nas vendas  
- Criar uma base estruturada para possibilitar modelagem preditiva  
- Desenvolver um modelo capaz de estimar vendas por livraria para novos livros  

<hr>

## 🧠 Escopo Analítico

O projeto envolve as seguintes etapas:

- Preparação e integração dos dados  
- Análise exploratória  
- Engenharia de atributos  
- Modelagem preditiva  
- Avaliação de desempenho  

Um dos principais desafios é lidar com a **ausência de vendas específicas por livro**, trabalhando apenas com dados agregados por autor.

<hr>

## 📈 Aplicações Potenciais

- Planejamento de lançamentos editoriais  
- Otimização da distribuição de livros por livraria  
- Apoio à tomada de decisão para editoras  
- Análise de performance de autores e gêneros  

<hr>

## 🚧 Observações Importantes

- Assume-se que o histórico de vendas do autor pode servir como proxy para novos livros  
- As previsões são estimativas e dependem da qualidade dos dados disponíveis  
- Este repositório descreve o escopo e o problema do projeto, não necessariamente a implementação final  

<hr>

## 📄 Licença

Este projeto é de uso educacional e analítico. Ajuste a licença conforme a necessidade do repositório.