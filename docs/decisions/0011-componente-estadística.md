# Componente Estadística

* Status: proposed
* Date: 2023-11-07

## Context and Problem Statement

Queremos conseguir hacer estadisticas de las rutas y los pedidos.

## Decision Drivers

* RF05:Módulo de estadísticas

## Considered Options

* Apache Common Maths
* Implementar una clase

## Decision Outcome

Chosen option: "Apache Common Maths", because nos ahorramos diseñarlo

### Positive Consequences

* Fácil de implementar

### Negative Consequences

* Hay que intalarse la librería y Apache Maven

## Pros and Cons of the Options

### Apache Common Maths

Es una librería para realizar estadisticas

* Good, because Compatible con Java
* Good, because Autocontenida
* Good, because Ligera
* Bad, because Requiere instalarse tambien Apache Maven

### Implementar una clase

Crear una clase que haga las estadisticas

* Good, because Tiene solo lo que necesitamos
* Bad, because Pesa más
* Bad, because Más dificil de implementar
