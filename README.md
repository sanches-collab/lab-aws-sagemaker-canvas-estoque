# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Fiz meu projeto até a 3 fase,mas vou contar aqui tudo o que fiz e dica,pra quem quiser fazer o seu próprio,sem exceder a conta grátis.


## 🎯 Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)


- Dataset usado :Peguei o banco de dados ,dataset-1000-com-promocional-e-renovacao-estoque

dataset-1000-com-preco-variavel-e-renovacao-estoque

 Análise - Valor de medição 1 
No primeiro o MASE era 0.109, ou seja na primeira medicação o valor de erro deste foi maior do que o segundo,comparando os dois ,o segundo foi melhor.

Valor da medicação 2

Model status
Avg. wQL
1.058
MAPE
1.000
WAPE
1.000
RMSE
6.854
MASE
0.093

Nessa segunda medição,os valores de Avg.wql,MAPE,RMSE foram quase iguais ,nos dois bancos de dados,mas o primeiro foi um pouco menor esses números, então nesses parâmetros o 1 foi melhor, só perdeu no MASE 

Lembrando que Avg.wql - métrica representa a perda média ponderada de quantil. É comumente usado para avaliar a precisão de modelos de regressão quantílica. Valores mais baixos indicam melhor desempenho.

MAPE - (Erro Percentual Absoluto Ponderado): Semelhante ao MAPE, mas leva em consideração pesos diferentes em observações diferentes. Novamente, valores mais baixos são melhores.

WAPE - (Erro Percentual Absoluto Ponderado): Semelhante ao MAPE, mas leva em consideração pesos diferentes em observações diferentes. Novamente, valores mais baixos são melhores.

RMSE - (Root Mean Square Error): Esta métrica calcula a raiz quadrada das diferenças quadradas médias entre os valores previstos e reais. Valores menores de RMSE indicam melhor ajuste.

MASE - (Erro Médio Absoluto em Escala): É uma versão em escala do MAE (Erro Médio Absoluto) que leva em conta a sazonalidade e a tendência. Um valor próximo de 0 indica bom desempenho.

  Eu,passei pelas 3 fases do projeto ,o último que foi da predição, não deu pra fazer pois constava que os dados não eram suficientes,para fazer a predição tanto no 1 quanto no segundo dataset, acredito que eu possa ter errado na parte de build ,escolha dos valores a ser medido em cada estoque,e não prossegui com o projeto pois excedeu minhas tentativas gratuitas e tive que excluir o modelo para não ser cobrada e ficar rodando o projeto e ir aumentando os gastos.


## 🚀 Dica para quem for fazer o projeto 

- A primeira dica é fazer um alerta logo que abrir a conta Sage Maker canvas,para alertar caso exceda a conta grátis.

- Segundo pra quem for fazer o projeto,tem que ficar de olho no tanto de dados que você pode gerar ,o número de dados que vai ser analisado.
Seria bom fazer uma tentativa fora do SageMaker cavas,testar no Chatgpt ou outro meio ,antes de fazer o projeto no SageMaker cavas,para não exceder a sua conta gratuita.


