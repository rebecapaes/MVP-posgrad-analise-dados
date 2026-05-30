# Evolução das melhorias do impacto ambiental na indústria têxtil.

 Este projeto foi desenvolvido como MVP (*Minimum Viable Product*), concluindo a sprint "Análise de dados e boas práticas" da pós-graduação em ciência de dados e analytics da PUC-Rio.

### **SOBRE**
A partir de dois datasets, busquei entender o relacionamento entre preço, impacto ambiental e características físicas de tecidos selecionados ao longo dos últimos anos. 

### **HIPÓTESES DETERMINADAS**
Foram enumeradas 4 hipóteses para direcionar as análises:

1. Alguns países tendem a produzir tecidos mais sustentáveis a um preço mais acessível do que outros?

2. Existem tipos de tecido com índices de sustentabilidade consistentemente inferiores aos demais, independentemente do país e do ano?

3. Tecidos mais leves tendem a ser mais sustentáveis do que tecidos mais pesados?

4. Existem linhas de produto com métricas de sustentabilidade significativamente inferiores às demais?

### **DATASETS**

[Fabric Properties and Suitability Dataset](https://www.kaggle.com/datasets/nadeeshaniekanayaka/fabric-properties-and-suitability-dataset) \
Dados técnicos da estrutura dos tecidos 

[Sustainable Fashion: Eco-Friendly Trends](https://www.kaggle.com/datasets/waqi786/sustainable-fashion-eco-friendly-trends) \
Dados relacionados ao impacto ambiental de cada material em cada país ao longo do tempo.

Ambos os datasets estão localizados no Kaggle, porém sem informações de origem. 
Como o presente projeto tem apenas fins acadêmicos, a origem de pesquisa desses dados foi irrelevante. 

### **TÉCNICA**

Análises Descritiva e Exploratória através da linguagem Python.

Foram desenvolvidos os seguintes gráficos: 
- Scatterplot
- Line Chart 
- Stacked Bar Chart associado a um Scatterplot
- Stacked Bar Chart associado a um Line Chart


### **CONCLUSÃO**

A partir dos dados coletados, o resultado é que os tecidos com custos mais acessíveis e menor impacto ambiental são produzidos pela Alemanha, enquanto o Brasil é o pior país nesses parâmetros.
Não há tecidos que têm uma evolução estagnada em relação ambiental, todos estão em constante evolução. Não existe uma correlação direta do peso dos tecidos com seus impactos ambientais, a gramatura de cada um não é uma justificativa para maior impacto.
Acessórios como bolsas e chapéus precisam de mais atenção em relação ao impacto ambiental, pois são os que tem maiores indices das métricas de sustentabilidade.

Apesar dessas conclusões, há necessidade de mais dados para obter respostas mais realistas. 

