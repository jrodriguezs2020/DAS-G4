# Modularizar reparto y rutas

* Status: proposed
* Date: 2023-10-26

## Context and Problem Statement

En el contexto del problema hemos optado por hacer un paquete para lo relacionado con el reparto y rutas, ya que así se separan los algoritmos de optimización y se encapsulan, facilitando así futuras iteraciones y la decisión de como gestionar la selección de los dichos algoritmos.

## Decision Drivers

* RF4: Módulo reparto y rutas

## Considered Options

* Paquete Reparto

## Decision Outcome

Chosen option: "Paquete Reparto", because comes out best.

## Pros and Cons of the Options

### Paquete Reparto

Hacer un paquete que contenga lo necesario para gestionar los repartos.

* Good, because Es escalable
* Good, because Consigue más modularidad
* Bad, because Si se hacen muchos paquetes puede empeorar la visibilidad del diseño
