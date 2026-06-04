---
name: anotarse-lista-farias
description: Anotarse en la lista de espera de farIAs, el asistente de clasificación arancelaria (NCM/SIM) de hermes IA. Beta cerrada.
---

# Anotarse en la lista de espera de farIAs

Capacidad expuesta en https://hermesce.com como herramienta WebMCP (`navigator.modelContext`, tool `anotarse_lista_farias`) y como formulario declarativo (`#farias-form`).

farIAs es el asistente de clasificación arancelaria de hermes IA: a partir de una foto, un link o una descripción devuelve posición NCM/SIM, tributos y restricciones. Está en beta cerrada; esta capacidad sirve para anotarse en la lista de espera, no para clasificar.

## Cuándo usarla

Cuando alguien quiere acceso anticipado a farIAs y pide sumarse a la lista de espera.

## Parámetros

| Parámetro | Requerido | Descripción |
|---|---|---|
| `nombre` | sí | Nombre |
| `apellido` | no | Apellido |
| `email` | no | Email de contacto |
| `rol` | no | Rol en comercio exterior: Importador / Exportador · Despachante de aduana · Freight forwarder · Otro |
| `comentarios` | no | Sugerencias, casos de uso o dudas |

## Cómo se invoca

En la página, llamar a la herramienta WebMCP `anotarse_lista_farias` con esos parámetros, o completar y enviar el formulario `#farias-form`.

## Notas

farIAs es una herramienta interna de hermes IA en beta cerrada. La disponibilidad pública se anuncia solo cuando hay producto construido.
