# Microservicios

* Status: proposed
* Date: 2023-11-09

## Context and Problem Statement

Plataforma o software donde desplegar los microservicios.

## Decision Drivers

* RF01: Cambio de arquitectura.

## Considered Options

* Azure Functions
* Lambda AWS

## Decision Outcome

Chosen option: "Azure Functions", because nos ahorramos diseñarlo

## Pros and Cons of the Options

### Azure Functions

Plataforma externa de windows

* Good, because Más información para desarrolladores y menos coodependencia
* Good, because No tenemos que implementar el software

### Lambda AWS

Plataforma externa de amazon

* Good, because No tenemos que implementar el software
* Bad, because Más información para desarrolladores y menos coodependencia
