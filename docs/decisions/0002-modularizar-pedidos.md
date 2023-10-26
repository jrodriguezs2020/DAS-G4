# Modularizar pedidos

* Status: proposed
* Date: 2023-10-26

## Context and Problem Statement

En el contexto del problema hemos optado por hacer un paquete para lo que se necesita de los pedidos ya que es demasiado para ser gestionado solo por una clase, facilitando así futuras iteraciones y la decisión de como contabilizar pedidos.

## Decision Drivers

* RF3: Módulo pedidos
* RF3.3: Contabilizar número de intentos de realizar pedidos

## Considered Options

* Paquete Pedidos

## Decision Outcome

Chosen option: "Paquete Pedidos", because comes out best.

## Pros and Cons of the Options

### Paquete Pedidos

Hacer un paquete que contenga la clase Gestión y lo que vayamos viendo necesario.

* Good, because Es escalable
* Good, because Consigue más modularidad
* Bad, because Si se hacen muchos paquetes puede empeorar la visibilidad del diseño
