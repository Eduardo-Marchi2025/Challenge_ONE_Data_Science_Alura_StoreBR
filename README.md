# Challenge_ONE_Data_Science_Alura_StoreBR
Challange do curso Aprendendo Python para Ciência de Dados - da Alura e Oracle Next Education

## 📌 Introdução

Esse projeto foi desenvolvido como parte do programa de ensino da Alura, em parceria com a Oracle Next Education (ONE), na formação em Data Science.

## 📋 Descrição do Projeto

O objetivo deste projeto é analisar dados de vendas, desempenho e avaliações de 4 lojas fictícias da Alura Store auxiliando o Sr. João no processo decisório de comercialização de uma de suas lojas, visando o fomento de capital para iniciar um novo empreendimento. A análise identifica a loja com menor eficiência com base em diversos indicadores de desempenho, já determinados definidos como Métricas. 

## 🔎 Métricas Analisadas

📈 Faturamento total das lojas <br>
🛍️ Categorias de produtos mais e menos vendidas <br>
⭐ Avaliação média dos clientes <br>
🎁 Produtos mais e menos vendidos <br>
🚚 Frete médio por loja <br>

## 🛠️ Tecnologias Utilizadas

- **Python 3**: Linguagem principal
- **Pandas**: Manipulação e análise de dados
- **Matplotlib/Seaborn**: Criação de gráficos/tabelas
- **plotly.express**: Criação de gráficos interativos
- **plotly.graph_objects/plotly.subplots/make_subplots**: Criação de gráficos interativos
- **Google Colab**: Ambiente de desenvolvimento

## 📊 Visualizações Gráficas Geradas

- Gráfico de barras comparativo do faturamento total
- Gráfico de linhas, interativo, comparativo do faturamento mensal de cada loja por ano
- Gráfico de barras, interativo, comparativo das 3 Categorias com maior e menor faturamento das loja ao longo dos anos
- Gráfico de colunas comparativo dos 3 Vendedores com maior Faturamento por loja em cada ano
- Gráfico de linhas, interativo, comparativo dos 3 Vendedores com maior Faturamento mensal de cada loja por ano
- Tabela com os 3 vendedores com maior faturamento por loja, com qual produto, e a avalição média de compra
- Tabela com as três categorias mais e menos vendidas por loja
- Gráfico de barras comparativo da média da avaliação de compra por loja
- Gráfico de linha comparativo da média da avaliação de compra por loja mensalmente ao longo dos anos
- Tabela com os Produtos Mais e Menos Vendidos
- Gráfico de barras comparativo do valor médio do frete por loja
- Gráfico de linhas, interativo, comparativo da média mensal do frete cada loja
- Tabela com a correlação da média do frete com a distância da entrega (km) - trimestral
- Gráfico de dispersão, interativo, da correlação da média do frete com a distância da entrega (km) - trimestral de cada loja
- Tabela da correlação dos 3 produtos de maior e menor faturamento entre o frete, e a % que o frete tem sobre o faturamento.
- Gráfico de linhas, interativo, correlação produto com maior e menor faturamento, e a % do frete sobre o faturamento. por loja e ano


## 📋 Estrutura do Projeto

├── AluraStore.ipynb # Notebook com análises, Gráficos e Relatório da análise dos dados disponíveis ├── README.md # Documentação do projeto └── dados/ # Dados utilizados nas análises ├── loja_1.csv ├── loja_2.csv ├── loja_3.csv └── loja_4.csv



## 🚀 Como Executar o Projeto

1. Clone este repositório:

   git clone https://github.com/Eduardo-Marchi2025/Challenge_ONE_Data_Science_Alura_StoreBR/

2. Acesse o Google Colab https://colab.research.google.com/ e faça upload do notebook AluraStoreBr.ipynb

3. Execute todas as células para visualizar a análise completa

---

## OUTRAS TÉCNICAS 🔬 E RECURSOS USADOS PARA AUXILIAR NA AVALIAÇÃO E CONCLUSÃO


### DA ENGENHARIA 📐


  - CATIA

  - MATLAB

  - ANSYS

  - Primavera P6

  - Zoho Analytics

  - Supermetrics

  - FMEAs, PPAP, Cartas de Controle; Diagrama de Ishikawa; Folha de Verificação


### DA ENG° CHINESA 🇨🇳👲 (Trabalhei por mais de 4 anos na CHINA e tive a oportunidade de aprender essas técnicas)


  - Zuàn Qǔ Kù - (bibliotecas de detalhamentos)

  - Sìwú Zhī Yùjìng - (Espelho de Jade dos Quatro Desconhecidos)

  - Ying Buzu - (Excesso e déficit)

  - Fang Cheng (Tabelas Retangulares)


### DA PSICOLOGIA 𝚿 🧠


  - Pesquisa Correlacional

  - O CUIDADO com o “hipotético-dedutivo”

  - Anchoring BIAS

  - Sentiment Analyses

  - Segmentação Comportamental

  - Factor Analysis and Principle Component Analysis

  - Elementos Psicológicos - A importância dos touch points - Abordagem Cold Calling

---
    
## 📝 Resultados e Recomendação

# Relatório de Análise Comparativa de Desempenho - Alura Store

Prezado(a) Sr. João,

Este relatório detalha a análise comparativa do desempenho das suas quatro lojas Alura Store, com o objetivo de fornecer uma recomendação baseada em dados sobre qual filial considerar para venda, visando o investimento em seu novo negócio. A análise foi conduzida utilizando as informações de vendas fornecidas, focando nas métricas solicitadas pelo Senhor.

As métricas analisadas incluem o **Faturamento Total**, as **Categorias Mais Populares**, a **Média de Avaliação dos Clientes**, os **Produtos Mais e Menos Vendidos**, e o **Custo Médio do Frete**.

---

## 1. Comparativo de Métricas Chave

A tabela a seguir apresenta uma comparação clara do desempenho das quatro lojas com base nos principais indicadores, formatada para melhor leitura:

<table style="border-collapse: collapse; width: 100%; border: 1px solid #dddddd;">
  <thead>
    <tr>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Métrica</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 1</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 2</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 3</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Faturamento Total</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 1.534.509,12</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 1.488.459,062</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 1.464.025,03</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 1.384.497,58</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Média Avaliação</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">3,98</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4,04</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4,05</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4,00</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Custo Médio Frete</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 34,69</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 33,62</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 33,07</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">R$ 31,28</td>
    </tr>
  </tbody>
</table>  


## Do faturamento💰 total das lojas.

<table style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #555; color: white;">
            <th style="text-align: center; padding: 10px;">LOJA</th>
            <th style="text-align: center; padding: 10px;">FATURAMENTO</th>
            <th style="text-align: center; padding: 10px;">% EM RELAÇÃO AO FATURAMENTO MAIOR</th>
        </tr>
    </thead>
    <tbody>
        <tr style="background-color: #f0f0f0;">
            <td style="text-align: center; padding: 10px;">1</td>
            <td style="text-align: left; padding: 10px;">R$ 1.534.509,12</td>
            <td style="text-align: right; margin-right: 20px;">0%</td>
        </tr>
        <tr style="background-color: #d9d9d9;">
            <td style="text-align: center; padding: 10px;">2</td>
            <td style="text-align: left; padding: 10px;">R$ 1.488.459,06</td>
            <td style="text-align: center; padding: 10px;">-3,00%</td>
        </tr>
        <tr style="background-color: #f0f0f0;">
            <td style="text-align: center; padding: 10px;">3</td>
            <td style="text-align: left; padding: 10px;">R$ 1.464.025,03</td>
            <td style="text-align: center; padding: 10px;">-4,80%</td>
        </tr>
        <tr style="background-color: #d9d9d9;">
            <td style="text-align: center; padding: 10px;">4</td>
            <td style="text-align: left; padding: 10px;">R$ 1.384.497,58</td>
            <td style="text-align: center; padding: 10px;">-10,80%</td>
        </tr>
    </tbody>
</table>


A VARIAÇÃO DO FATURAMENTO MENSAL POR LOJA

<table style="width: 100%;">
    <tr>        
        <td><img src="https://drive.google.com/uc?export=view&id=1e8VhjgHe8XErBkmsrUZoFDnuUXlmP5lO" width="100%" height="auto"></td>
        <td><img src="https://drive.google.com/uc?export=view&id=1z0wkAX9nDhv0NVoj1dXZ26oGPvgOruTU" width="100%" height="auto"></td>

<table style="width: 100%;">
    <tr>        
        <td><img src="https://drive.google.com/uc?export=view&id=1YfcJdjm7mRcolDD3njGc9f_j8xgA7G2S" width="100%" height="auto"></td>
        <td><img src="https://drive.google.com/uc?export=view&id=1qf2-_inuaQZNSuHTBBleRvx7IoQM6PsG" width="100%" height="auto"></td>
    </tr>
</table>  
  

Os Gráficos acima indicam uma grande ocilação no faturamento de todas as lojas em todos os meses. Nos dados fornecidos não foi possível encotrar nenhum indicador que justifique tais variações. 
  

## Vendedores 💁- A Influência no Faturamento por Loja
 

NEsta tabela abaixo, ela nos apresenta os 3 vendedores com maior faturamento por loja. Sendo que o Faturamento dos 3 representa por volta de 10% do faturamento total da loja. 

Mas, também nos apresenta uma dado que requer uma análise mais aprofundada. Os nomes de "Larissa Alves"; "Thiago Silva"; Felipe Santos"; aparecem em mais de uma loja, e em alguns casos no mesmo periodo de tempo. 
###Se não forem nomes homônimos, esses dados podem ter uma grande influência no Faturamento total das lojas.

<table style="width: 100%;">
    <tr>        
        <td><img src="https://drive.google.com/uc?export=view&id=1EpXxX9E94PDj_EBJ3-9pRk55KV0v8tvh" width="100%" height="auto"></td>
</table>



---

## 2. Detalhes de Desempenho por Loja  


Esta tabela compara lado a lado os detalhes de desempenho de cada filial, usando como referência as categorias mais populares e os produtos mais e menos vendidos: 
Esta informação pode ser muito útil, quando sabemos o Markup de cada produto, o plano estratégico da segmentação e abordagem ao Cliente da Loja.  
  
    
  


<table style="border-collapse: collapse; width: 100%; border: 1px solid #dddddd;">
  <thead>
    <tr>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Detalhe</th>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Loja 1</th>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Loja 2</th>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Loja 3</th>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Loja 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Top 3 Categorias Mais Populares</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">
        <ul>
          <li>Eletrônicos</li>
          <li>Eletrodomésticos</li>
           <li>Móveis</li>
        </ul>
      </td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">
         <ul>
          <li>Livros</li>
          <li>Eletrodomésticos</li>
           <li>Instrumento musical</li>
        </ul>
      </td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">
        <ul>
          <li>Eletrônicos</li>
          <li>Eletrodomésticos</li>
           <li>Móveis</li>
        </ul>
      </td>
       <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">
         <ul>
          <li>Moveis</li>
          <li>Utilidade Domestica</li>
           <li>Eletrônicos</li>
        </ul>
      </td>
    </tr>
     <tr>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Produto Mais Vendido</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">TV Led UHD 4K</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Livro</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Kit Banquetas</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Cama Boxi</td>
    </tr>
     <tr>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Produto Menos Vendido</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Headset</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Jogo de Tabuleiro</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Blocos de Montar</td>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px; vertical-align: top;">Guitarra</td>
    </tr>
  </tbody>
</table>  


---  


## 3. Análise Preliminar e Recomendação Baseada em Dados Atuais  
  


<table style="border-collapse: collapse; width: 100%; border: 1px solid #dddddd;">
  <thead>
    <tr>
      <th style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Métrica</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 1</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 2</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 3</th>
      <th style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Loja 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: left; padding: 8px;">Faturamento Total</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">1°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">2°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">3°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4°</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Média Avaliação</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">2°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">1°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">3°</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">Custo Médio Frete</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">4°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">3°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">2°</td>
      <td style="border: 1px solid #dddddd; text-align: right; padding: 8px;">1°</td>
    </tr>
  </tbody>
</table>  
  




Com base na comparação das métricas de **Faturamento Total**, **Média de Avaliação de Clientes** e **Custo Médio de Frete**, apresentadas nas tabelas, a **Loja 1** demonstra consistentemente o desempenho mais baixo entre as quatro filiais:

* Apresentou o menores indices na Avaliação do Cliente e o maior Custo médio do Frete.

* Registra o maior faturamento total (R$ 1.534.509,12), 10,8% maior que a loja 4, que registra o menor faturamento.

* A loja 4 Apesar de ter o menor custo médio de frete (R$ 31,28), ela teve a maior variação do valor do frete em relação ao preço do produto. 
Variações percentual foi de  0,29% à 20,91%. Isso indica que pode impactar negativamente a rentabilidade das operações.


* Os dados de todas as métricas avaliadas, são inconclusivos. Se faz necessário mais informações e dados.

* Portanto, eu estaria sendo leviano se fizer alguma recomendação de venda de qualquer loja. Certamente o Sr. João possui outras informações , que somadas a esse dados analisados ele consiga tomar uma decisão acertada.

* Caso ele não as tenha, eu sugiro alguns passos a seguir.


---  
  


## 4. Considerações Adicionais e Próximos Passos Necessários para uma Decisão Segura

Sr. João, é fundamental destacar que a análise apresentada, embora objetiva com os dados fornecidos, baseia-se principalmente em métricas de receita bruta e custos de frete, juntamente com avaliação do cliente. **Uma decisão estratégica tão importante quanto a venda de uma filial idealmente requer uma análise financeira e operacional mais completa.**

**Dados Críticos Ausentes na Análise Atual:**

* Ter os documentos financeiros completos de cada loja, DRE, DFC, BP, DMPL.

* **Margem de Lucro por Loja:** O faturamento total não reflete a rentabilidade. Uma loja com alto faturamento pode ter baixa margem de lucro e ser menos rentável que uma loja com faturamento menor, mas com custos controlados e margens altas.
* **Custos Fixos e Variáveis por Loja:** Aluguel, salários da equipe, contas de consumo, marketing local, custos de estoque detalhados, etc., são essenciais para determinar a real lucratividade de cada filial.
* **Estrutura da Equipe e Custos de Pessoal:** O tamanho da equipe de vendas e seus custos operacionais impactam diretamente a eficiência e a rentabilidade.
* **Técnicas e Estratégias de Vendas Locais:** Diferenças na abordagem de vendas, marketing ou mix de produtos podem influenciar o desempenho e o potencial futuro.
* **Potencial de Crescimento Futuro:** Fatores externos ou planos de investimento específicos para cada local que podem não estar refletidos nos dados históricos.

**Por que estes dados são Cruciais?**

Uma loja com faturamento mais baixo (como a Loja 4) pode ser a mais rentável se seus custos forem proporcionalmente muito menores. Inversamente, uma loja de alto faturamento (como a Loja 1) pode ter custos tão elevados que sua margem de lucro seja inferior. A decisão de venda deve idealmente ser baseada na **rentabilidade e no potencial de retorno sobre o investimento**, não apenas na receita bruta.

**Recomendação para Próximos Passos:**

Para garantir que a decisão de qual loja vender seja a mais segura e alinhada com seus objetivos financeiros para o novo negócio, sugiro **organizarmos uma reunião para discutir e levantar os dados financeiros e operacionais detalhados** mencionados acima para cada loja. Com essas informações adicionais, poderemos realizar uma análise de lucratividade e custo-benefício que fornecerá uma base muito mais sólida para sua decisão final.

---

## 5. Conclusão

A análise preliminar baseada nos dados de vendas e avaliação aponta a Loja 1 como a candidata mais aparente para venda. No entanto, **reiteramos que esta análise possui limitações importantes** devido à ausência de dados completos de custo e lucratividade.

Para uma decisão verdadeiramente informada e segura, é indispensável integrar as informações financeiras e operacionais. Estou à disposição para auxiliar no levantamento e análise desses dados adicionais em uma próxima etapa.

Esperamos que este relatório, com suas ressalvas, seja um ponto de partida útil para a sua decisão, Sr. João.

Atenciosamente,

Eduardo Marchi

---


## Executado por 💻🧠:

Eduardo Marchi, Aluno do projeto ONE - Alura e Oracle Next Education.
https://www.linkedin.com/in/eduardo-marchi-42b371348/


## Agradecimentos🙏 

  - Alura e Oracle Next Education pela oportunidade de aprendizado.<br>
  - Comunidade Alura pelos recursos e suporte.
  - Aos meus Amigos e Amigos meus: Kun Guo; Payne Pan; Guo Xiao Kun; Xie Qing Long (Pesquisadores e Facilitadores do intercânbio Comercial, Técnico e Acadênico China - Brasil)

## Licença 🔑

Eduardo Marchi
  
   


