# Proyecto de Introduccion a la Programación 

# Balckjack en c++

## Equipo conformado por: 
- Jose Angel Alvarez
- Gustavo Reyes Rodriguez
- Génesis Nicole Domínguez Betancourt
- William Sebastian Garnica Valdez
- Alonso Martinez Martinez 

Este proyecto consiste en desarrollar un simulador del popular juego de cartas Blackjack utilizando el lenguaje de programación C++. El objetivo principal es crear un código donde los jugadores podrán enfrentarse a la banca, representada por la computadora, en un entorno controlado por las reglas tradicionales del Blackjack.

## ¿Qué es el Blackjack?

 El Blackjack es un juego de cartas que se juega principalmente entre un jugador y la maquina . El objetivo del juego es simple: sumar un valor total de cartas lo más cercano a 21 sin pasarse de ese número. Cada carta tiene un valor numérico específico:

- Las cartas del 2 al 10 tienen su valor nominal.
- Las cartas J, Q, y K  valen 10 puntos.
- El As puede valer 1 o 11 puntos, dependiendo de lo que sea más conveniente para el jugador.

## Reglas del Juego

1.- Distribución de cartas: Al inicio del juego, tanto el jugador como la maquina reciben dos cartas. Las cartas del jugador se revelan ambas, mientras que la banca muestra solo una de sus cartas. 

2.- Acciones:
- Pedir carta: El jugador o maquina puede pedir más cartas si cree que no superará los 21 puntos.
- Quedarse: El jugador o maquina decide mantener su mano actual y no recibir más cartas.

3.- Condiciones de victoria:
- Blackjack: Si un jugador o la banca obtiene exactamente 21 puntos con las dos primeras cartas.
- Gana el jugador: Si el jugador tiene una mano superior a la de la maquina sin exceder los 21 puntos.
- Pierde el jugador: Si el jugador  excede los 21 puntos o si la maquina tiene una mano más alta sin pasarse de 21.
- Empate: Si el jugador y la maquina tienen la misma puntuación.
