---
layout: default
title: Sesión 03
nav_order: 4
---

# Sesión 03
## Introducción

La simulación de cuerpos blandos podrá ser usada para simular objetos con una deformación suave. Fue principalmente diseñada para agregar movimientos secundarios a una animación, tales como el movimiento de vaivén de las partes blandas del cuerpo, cuando éste se mueve.

También funcionará para la simulación de cuerpos blandos más genéricos que sean capaces de flexionarse, deformarse y reaccionar a fuerzas como la gravedad y el viento o colisionar con otros objetos.

Si bien es un método capaz de simular ropa y cuerpos rígidos deformables, hasta un cierto punto, la simulación de Ropa podrá hacer de mejor manera lo primero, debido a que fue especialmente diseñada para ese propósito.

La simulación funcionará mediante la combinación de la animación existente de un objeto con las fuerzas que actúen sobre el mismo. Existirán fuerzas externas como la gravedad o campos de fuerzas, así como fuerzas internas que mantendrán la unión entre los vértices del objeto. De esta manera, será posible simular el tipo de formas que podría adquirir un objeto en el mundo real, si tuviera volumen, estuviera relleno de alguna sustancia y fuera afectado por fuerzas reales.

Los cuerpos rígidos podrán interactuar con otros objetos mediante Colisiones. Asimismo, podrán interactuar consigo mismos mediante Colisiones propias.

El resultado de la simulación de cuerpos blandos podrá ser convertido en un objeto estático. También será posible capturar y editar una simulación, esto es, editar resultados intermedios y reiniciar la simulación a partir de allí.

## Escenarios típicos para el uso de cuerpos blandos

Los cuerpos blandos son apropiados para:

- Zarandeo de personales al moverse.

- Objetos elásticos y deformables hechos de materiales similares a goma o gelatina.

- Ramas de árboles moviéndose con el viento, cuerdas ondulantes, etc.

- Banderas, mangas anchas, almohadones u otros tipos de telas simples reaccionando a fuerzas.

## Creación de un cuerpo blando
La simulación de cuerpo blando funciona con todos los objetos que poseen vértices o puntos de control (mallas, curvas, superficies y celosías).

Para añadir una simulación de cuerpo blando a un objeto, ve a la pestaña de Física en el panel de Propiedades y activa el botón de Cuerpo blando (*Soft Body*). 

Puedes iniciar la simulación de cuerpo blando reproduciendo la animación con Alt-A y detenerla pulsando Esc o Alt-A.

##  Interacción en tiempo real

Al trabajar con una simulación de cuerpo blando, resulta muy útil utilizar el editor de línea de tiempo (*Timeline*). Puedes desplazarte entre fotogramas y la simulación se mostrará siempre en su estado actual. Es posible interactuar con la simulación en tiempo real; por ejemplo, moviendo objetos de colisión o agitando el objeto de cuerpo blando.

Asimismo, puedes seleccionar el objeto de cuerpo blando mientras se ejecuta la simulación y aplicar el modificador desde la pestaña de modificadores en el panel de propiedades (*Properties*). Esto hace que la deformación sea permanente.

## Consejos

- Los cuerpos blandos funcionan especialmente bien si los objetos tienen una distribución uniforme de vértices. Se necesitan suficientes vértices para lograr buenas colisiones. La deformación (la rigidez) cambia si se añaden más vértices en una zona determinada.

- El cálculo de las colisiones puede llevar mucho tiempo. Si algo no es visible, ¿por qué calcularlo?

- Para acelerar el cálculo de colisiones, a menudo resulta útil utilizar un objeto adicional —más simple, invisible y ligeramente más grande— para gestionar la colisión.

- Utiliza cuerpos blandos solo cuando tenga sentido. Si intentas cubrir la malla de un cuerpo con una prenda ajustada y animarla únicamente mediante cuerpos blandos, no obtendrás buenos resultados. Es posible activar la autocolisión en el cabello simulado con cuerpos blandos, pero es un camino que deberás recorrer por tu cuenta. Más adelante trataremos el tema de las colisiones en detalle.

- Prueba a utilizar una malla de deformación (*Lattice*) o una curva guía (*Curve Guide*) con propiedades de cuerpo blando en lugar del objeto en sí; esto puede resultar muchísimo más rápido.

## Ejemplos
 - Soft Body:: Blender [https://youtu.be/e3FM_VJndJg?si=fiEK3sDBVTDvTwkK](https://youtu.be/e3FM_VJndJg?si=fiEK3sDBVTDvTwkK)
 - Simulación Soft Body en Blender 2.9 [https://youtu.be/T_Ckr6UTHbo?si=uAl8x8jgPdJGQ9Ss](https://youtu.be/T_Ckr6UTHbo?si=uAl8x8jgPdJGQ9Ss)
 - Blender 4.5 ¿Cómo trabajar con Softbody? (tutorial)  [https://youtu.be/fcO06z5-EoA?si=XL_WJ-IpRl8QAA3P](https://youtu.be/fcO06z5-EoA?si=XL_WJ-IpRl8QAA3P)
 - Física de cuerpos blandos para principiantes (Tutorial de Blender)[https://youtu.be/6Dtwhd1N0bY](https://youtu.be/6Dtwhd1N0bY)
 
 


Obtenido de: https://docs.blender.org/manual/es/5.2/physics/soft_body/introduction.html#typical-scenarios-for-using-soft-bodies 

## Blackboard
Todas las actividades se entregan a las 3:00 am los días lunes.
