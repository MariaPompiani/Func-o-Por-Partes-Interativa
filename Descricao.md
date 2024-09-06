Função Por Partes
O trabalho final desenvolvido na disciplina de Cálculo 1 Prática do curso de Ciência de Dados e Inteligência Artificial tem como objetivo demonstrar interativamente o conceito de funções por partes e suas aplicações práticas. Utilizando Python no Google Colab, o projeto explora como diferentes tipos de funções—duas funções quadráticas e uma função linear—podem ser combinadas para formar uma função por partes, e como os parâmetros dessas funções influenciam o gráfico resultante.

Descrição do Código:

1.	Função funcao_por_partes: Calcula os valores das funções quadráticas e linear com base nos parâmetros fornecidos. Recebe entradas para os coeficientes das funções quadráticas e linear, além dos limites que definem as regiões em que cada função é aplicada.

2.	Função plot_funcao_por_partes: Cria o gráfico interativo usando matplotlib e ipywidgets. A função divide o intervalo de x em três partes, cada uma correspondendo a uma função diferente:
•	Para x menor ou igual a limite1, plota a primeira função quadrática.
•	Para x entre limite1 e limite2, plota a segunda função quadrática.
•	Para x maior que limite2, plota a função linear. O gráfico inclui linhas de limite (limite1 e limite2) e marca pontos de descontinuidade onde as funções se encontram. A interatividade permite ajustar os parâmetros das funções e dos limites para observar como essas alterações afetam a forma do gráfico.
3.	Integração com ipywidgets: Utiliza widgets interativos para ajustar dinamicamente os parâmetros das funções e os limites diretamente no gráfico. Isso facilita a exploração visual dos efeitos das mudanças nos parâmetros sobre a função por partes e ajuda a entender melhor o conceito.


