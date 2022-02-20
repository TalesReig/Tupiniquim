# Projeto Tupiniquim

#Robô Tupiniquim Academia do Programador 2022

##CONTEXTO
A AEB (Agência Espacial Brasileira) entrou em contato com a turma da Academia do Programador 2022 para realização de um novo projeto. Com medo do Covid, o presidente Bolsonaro pretende se esconder do vírus em Marte, mas antes, a AEB vai enviar uma nave espacial (codinome Tupiniquim I) tripulada com um Robô para fazer análises do planeta vermelho. Os alunos da 9ª edição da Academia do Programador, reconhecidos como excelentes programadores, foram contratados para desenvolver o software que irá guiar o Robô nesta empreitada.

1 SOBRE O SISTEMA A área escolhida para análise é curiosamente retangular e os robôs devem andar por ela com suas câmeras ligadas coletando todo tipo de informação. A posição de um robô é representada por uma combinação de coordenadas X e Y e também uma letra representando a direção que ele está olhando. A área é dividida em um grid para simplificar a navegação. Um exemplo de posição poderia ser: 0,0,N, significando o robô está na parte inferior esquerda com a face para o norte. Use as orientações: N =norte, S = sul, L = leste, O = oeste. Para controlar o robô, a AEB envia simples strings com os comandos. Letras possíveis são: E, D e M. As letras E e D fazem o robô virar 90 graus para esquerda e direita respectivamente, sem sair do lugar. A letra M significa se mover uma posição no grid para frente, mantendo a mesma direção. Assuma que mover o robô para frente, significa mover sua posição de (X, Y) para (X, Y+1). Por exemplo, um robô na posição (0,0) com a face para o norte, ao se mover uma posição, vai parar em (0,1).

2 ENTRADA O programa deve possuir os seguintes parâmetros: – A primeira linha deve ser as coordenadas do canto superior direito da área. O canto inferior esquerdo é sempre (0,0). – O resto das entradas deve ser os comandos que o robô deve executar. Cada comando deve ser enviado em 2 partes: a primeira parte é a posição inicial do robô e a segunda uma série de instruções que aquele robô deve seguir para explorar a área. A posição é dada com 2 inteiros e uma letra, separados por espaços, correspondendo pelas coordenadas X e Y e a orientação do robô. Cada robô vai executar as instruções de forma sequencial: o segundo robô só iniciará suas ações quando o primeiro terminar.

3 SAÍDA Para cada robô, a posição final e sua orientação depois de executada as instruções. 4 EXEMPLO Para cada robô, a posição final e sua orientação depois de executada as instruções.

##Input:
5 5 1 2 N EMEMEMEMM 3 3 L MMDMMDMDDM

##Output esperado: 
1 3 N 5 1 L
