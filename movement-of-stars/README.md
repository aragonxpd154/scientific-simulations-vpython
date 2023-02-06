# two-movement-of-starts

Este script cria uma simulação de duas estrelas em movimento, usando a biblioteca VPython. A constante gravitacional "G" e a massa das estrelas "M" são definidas como constantes. A distância inicial entre as duas estrelas é definida como "rdist". O valor de "dt" define o intervalo de tempo usado para atualizar a posição das estrelas.

Dois objetos esféricos são criados como representações das estrelas, usando a função "sphere". As posições iniciais, as massas e as cores das estrelas são definidas. As propriedades da trajetória são habilitadas para criar uma linha traçando o movimento das estrelas.

O loop principal "while True" calcula a força gravitacional entre as estrelas usando a equação de gravitação universal e atualiza as posições das estrelas. A função "rate" controla a velocidade da simulação. O loop se repetirá indefinidamente até que o programa seja interrompido.

Em resumo esse é um script de simulação de física utilizando a biblioteca VPython. Ele simula o movimento de duas estrelas que se atraem pela força gravitacional, e o comportamento das duas estrelas é exibido em uma animação. Além disso, o script também calcula e exibe o comportamento da energia potencial gravitacional, centrífuga e total das duas estrelas em um gráfico. O centro de massa das duas estrelas também é calculado e exibido.
