# Modularizar-Pedidos

* Status: proposed
* Date: 2023-10-26

## Context and Problem Statement

En el contexto del problema hemos optado por hacer un paquete englobando todo lo relacionado con los pedidos ya que nos facilitará el trabajo para futuras iteraciones y reunirá las clases que tengan el mismo objetivo.

## Decision Drivers

* RF03: Módulo pedidos.
* RF03.3: Contabilizar número de intentos de realizar pedidos.

## Considered Options

* 0002-1-Paquete Pedidos

## Decision Outcome

Chosen option: "0002-1-Paquete Pedidos", because Facilitará la implementación de las futuras decisiones y nos permitirá reunir en el mismo paquete todo lo relacionado con los pedidos.

## Pros and Cons of the Options

### 0002-1-Paquete Pedidos

Hacer un paquete que contenga la clase GestorPedidos y Pedidos.

* Good, because Es escalable.
* Good, because Consigue más modularidad.
* Bad, because Si se hacen muchos paquetes puede empeorar la visibilidad del diseño.
