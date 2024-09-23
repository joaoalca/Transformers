# Transformers
Pontos positivos e negativos Tradução usando Transformer com Controle de Versões

Não consgui fazer as alterações necessárias para que o treinamento rodasse, mesmo com a A100 e 1 época o treino não foi completado, por isso não tenho commits significativos. Mas trago pontos positivos e negativos que encontrei analisando código.

Pontos positivos:
Um dos pontos positivos para mim é a implementação personalizada da taxa de aprendizado com o uso de CustomSchedule, que ajusta dinamicamente a learning rate com base no número de steps, o que parece ser bem importante em modelos complexos.

Pontos negativos:
O Notebook da forma que está no autoestudo, não rodou nem com a A100. O treino com apenas 1 época estourava o limite de tempo do colab.
