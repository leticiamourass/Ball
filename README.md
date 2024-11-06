# Ball

Este repositório contém uma implementação simples de uma classe Ball, que simula o movimento de uma bola que pode ser refletida horizontal e verticalmente ao atingir os limites de um espaço. A classe foi escrita em Java, utilizando conceitos de programação orientada a objetos.

# Descrição

A classe Ball modela uma bola que possui:

- Posições (coordenadas x e y).
- Um raio (tamanho da bola).
- Velocidade e direção (representadas como deltaX e deltaY).
- Capacidade de se mover de acordo com sua velocidade e refletir ao atingir os limites de um espaço, como se estivesse "quicando" nas bordas.

## Funcionalidades

- **Construtores**:
Um construtor que aceita coordenadas x e y, raio, e velocidades deltaX e deltaY em coordenadas cartesianas.
Outro construtor que aceita coordenadas x e y, raio, velocidade e direção em coordenadas polares (magnitude e direção).

- **Métodos**:
  - **mover()**: Move a bola de acordo com os valores de deltaX e deltaY.
  - **refletirHorizontal()**: Reflete a bola horizontalmente (inverte a direção do eixo x).
  - **refletirVertical()**: Reflete a bola verticalmente (inverte a direção do eixo y).
  - **toString()**: Retorna uma representação em string do estado atual da bola, incluindo sua posição e velocidade.

## Exemplo de Execução

Ball[(1.1,2.2),speed=(3.3,4.4)]

Ball[(80.0,35.0),speed=(4.0,6.0)]  

x é: 80.0

y é: 35.0

raio é: 5

deltaX é: 4.0

deltaY é: 6.0

Ball[(84.0,41.0),speed=(4.0,6.0)]

Ball[(88.0,47.0),speed=(4.0,6.0)]

Ball[(92.0,41.0),speed=(4.0,-6.0)]

Ball[(96.0,35.0),speed=(4.0,-6.0)]

Ball[(92.0,29.0),speed=(-4.0,-6.0)]

Ball[(88.0,23.0),speed=(-4.0,-6.0)]

Ball[(84.0,17.0),speed=(-4.0,-6.0)]

Ball[(80.0,11.0),speed=(-4.0,-6.0)]

Ball[(76.0,5.0),speed=(-4.0,-6.0)]

Ball[(72.0,-1.0),speed=(-4.0,-6.0)]

Ball[(68.0,5.0),speed=(-4.0,6.0)]

Ball[(64.0,11.0),speed=(-4.0,6.0)]

Ball[(60.0,17.0),speed=(-4.0,6.0)]

Ball[(56.0,23.0),speed=(-4.0,6.0)]

Ball[(52.0,29.0),speed=(-4.0,6.0)]


