# ML Mastery Learning Rate Schedule


Aqui estudaremos como configurar uma tabela (cronograma) de taxa de aprendizado adaptável para ajustar o modelo durante a execução do treinamento.

A quantidade de mudança no modelo durante cada etapa deste processo de pesquisa, ou o tamanho da etapa, é chamada de taxa de aprendizado e fornece talvez o hiperparâmetro mais importante a ser ajustado para sua rede neural a fim de obter um bom desempenho em seu problema.

Configurar uma taxa de aprendizagem fixa é muito desafiador e requer experimentação cuidadosa. Uma alternativa ao uso de uma taxa de aprendizado fixa é variar a taxa de aprendizado ao longo do processo de treinamento.

Keras fornece uma tabela de taxa de aprendizado ``ReduceLROnPlateau`` que ajustará a taxa de aprendizado quando um platô no desempenho do modelo for detectado, **por exemplo**, nenhuma mudança para um determinado número de épocas de treinamento.


Thanks God! 
