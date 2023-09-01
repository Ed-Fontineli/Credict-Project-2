# Projeto de Vizualização de Dados com bases de Crédito

Projeto de exploração de dados de base de Credito neste neste [link](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/develop/dataset/credito.csv), escrito na linguagem Python. Os dados estão no formato CSV e contém informações sobre clientes de uma instituição financeira. Em especial, estamos interessados em explicar a segunda coluna, chamada de **default**, que indica se um cliente é adimplente(`default = 0`), ou inadimplente (`default = 1`), ou seja, queremos entender o porque um cliente deixa de honrar com suas dívidas baseado no comportamento de outros atributos, como salário, escolaridade e movimentação financeira. Uma descrição completa dos atributos está abaixo.

O atributo de interesse (`default`) é a **variável resposta**, já os demais atributos que buscam explicá-la (`idade`, `salário`, etc.) são conhecidas como **variáveis explicatívas**.

# Utilização

### Dependencias

Bibliotecas necessárias:

seaborn==0.12.2

matplotlib== 3.7.1

pandas==1.3.5

# Storytelling

foram utilizados os dados Categóricos de **Escolaridade** e o **Valor de transaçoes** e **Quantidade de transações** para estruturar a exploração e vizualiação dos dados. Neste caso, avaliando os gráficos e levando em consideraçção apenas a inadimplência, pode-se perceber que:
- Pessoas com Mestrado apresentam um maior número de inadimplêcia;
- Pessoas com Doutorado tem o menor número de inadimplentes
- Pessoas com o salário abaixo de 40K por ano apresentam um maior número de inadimplência;

O que se torna estranho se levarmos em conta que maioria das pessoas com mestrado ganha acima de 40K por ano.
Outro fato é de que:
- Pessoas inadimplentes fazem menos tranzações;
- Pessoas inadimplentes fazem transações de menor valor;
Então apesar da maioria de inadimplentes ter mestrado e ganharem relativamente bem, a maioria inadimplente faz menos transações e de menor valor

Em contrapartida a maioria de Adimplentes: 
- Tem Mestrado;
- Ganham até 40K por ano;

Dito isto, a maioria dos clientes possui Mestrado, o que pode explicar do porquê eles estarem no topo tanto de inadimplência como Adimplência assim como maioria dos clientes ganham até 40K por ano, que também explicaria porquê estão no topo tanto da adimplência como iadimplência também.

## Autores

Eduardo Fontineli 

 [@EduardoFonteneli](https://www.linkedin.com/in/carlos-eduardo-fontineli-goncalves/)
