#CRIAÇÃO DO DIAGRMA DE GANNT - DISCIPLINA DE PROJETO INTEGRADOR I - "Projeto de Desenvolvimento de Software no Aux. de Deficientes visuais"!

**Mermaid permite criar e visualizar diagramas.**

Este exemplo é um modelo de cronograma simples, documentação sobre o gráfico de está [disponível aqui](https://github.com/mermaid-js/mermaid/blob/develop/docs/gantt.md).

```mermaid
    gantt
    title Cronograma de atividades do projeto
    dateFormat  YYYY-MM-DD
    section Pesquisa
    Desenvolvimento com as tecnologias     :   a1, 2022-11-08, 21d
    Uso dos recursos    : a2, 2022-11-15, 28d
    Ferramentas   : a3, after a2, 16d
    section Documentação
    Pré-projeto     :a1, 2022-11-01, 15d
    Levantamento de literatura   :a2,after a1  , 20d
    Construção da documentação final  :a3, 2022-12-27, 21d
    Criação do Diagrama de Componentes:     c3, 2022-12-06, 14d
    section Desenvolvimento
    Criação do protótipo de telas  :  c2, after a2, 14d
    Aplicativo final   :     c3, after a3, 21d
    section Prototipação
    Criação de telas do sistema     :    c3, 2022-12-06, 21d
    Criação do protótipo      :c3,     after c2, 14d
    section Defesa
    Preparação dos slides :p1, after c3, 14d
    Ensaio da apresentação :p2, after c3, 18d
    Apresentação e entrega  :milestone, after p1, 1d
    
   ``` 
 O cronograma pode prever os seguintes tópicos sugeridos:
- Levantamento da literatura: quanto tempo você demora para ler e organizar as referências bibliográficas? 
- Escolha do instrumento e preparação para coleta de dados: quanto tempo será gasto para escolher os instrumentos que serão usados na pesquisa? (Questionários, entrevistas e escalas, por exemplo). 
- Levantamento de dados: quanto tempo é preciso para levantar os dados que serão usados no estudo? 
- Escrita da parte teórica: quanto tempo será gasto para escrever o relatório? 
- Análise dos dados: qual é o tempo necessário para organizar os dados coletados em planilhas e tabulá-los? 
- Discussão dos resultados: quanto tempo você vai gastar para articular os seus dados com os dados de outros autores que pesquisaram as mesmas variáveis? 
- Elaboração da conclusão e referências: quanto tempo é necessário para escrever as considerações finais e colocar a lista de referências bibliográficas nas normas da ABNT? 
- Ajustes finais: de quanto tempo você precisa para revisar a formatação? 
- Criação da apresentação: qual é o tempo necessário para elaborar os slides e ensaiar a apresentação? 
- Defesa: Quando o trabalho será apresentado para a banca? 



```mermaid
    
    
   
