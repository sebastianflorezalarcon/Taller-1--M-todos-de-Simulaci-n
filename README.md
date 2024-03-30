# Taller-1--Metodos-de-Simulacion
## Modelo SIR
Uno de los modelos más sencillos para la evolución de una epidemia es el modelo SIR, propuesto
en 1927 por W. O. Kermack & A. G. McKendrick que se utiliza para simular enfermedades en las
que una persona infectada, una vez recuperada (o muerta) no se puede volver a infectar.
Considere una población con un número constante de personas donde cada una puede estar
susceptible, infectada (casos activos) o retirada. Sean $s$, $i$, $r$ las fracciones de la población que están
susceptibles, infectadas o retiradas, respectivamente ($s + i + r = 1$). Asumamos que, a cada
momento, la cantidad de susceptibles que se infecta por unidad de tiempo es proporcional a la
cantidad e susceptibles multiplicada por la cantidad de infectados, ���, donde � es una constante
que nos dice qué tan contagiosa es la enfermedad. Por el contrario, la cantidad de infectados que
dejan de serlo por unidad de tiempo es solamente proporcional al número de infectados, ��,
donde 1/� da el tiempo característico de recuperación. Las ecuaciones diferenciales acopladas
que rigen el comportamiento son, por lo tanto:
