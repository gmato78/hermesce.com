---
name: consultar-operacion-comex
description: Enviar una consulta a hermes CE sobre una operación de comercio exterior (importación o exportación). hermes CE responde en menos de 24 horas hábiles.
---

# Consultar una operación de comercio exterior

Capacidad expuesta en https://hermesce.com como herramienta WebMCP (`navigator.modelContext`, tool `consultar_operacion_comex`) y como formulario declarativo (`#contact-form`).

Permite a un agente generar un lead de comercio exterior en nombre de una persona: describe la operación y los datos de contacto, y hermes CE responde en menos de 24 horas hábiles.

## Cuándo usarla

Cuando alguien necesita despacho de aduana, clasificación arancelaria, coordinación de embarques, intervención de organismos, almacenamiento o una operación DDP / llave en mano en Argentina, y quiere contactar a hermes CE.

## Parámetros

| Parámetro | Requerido | Descripción |
|---|---|---|
| `nombre` | sí | Nombre y apellido de quien consulta |
| `email` | sí | Email de contacto |
| `detalle` | sí | Descripción de la operación: qué se importa/exporta, origen, frecuencia o etapa |
| `empresa` | no | Empresa |
| `telefono` | no | Teléfono o celular |
| `servicio` | no | Servicio buscado: Despacho de Aduana · Clasificación Arancelaria · Coordinación de Embarques · Intervención de Organismos · Almacenamiento · DDP Puerta a Puerta · Trade Llave en Mano |

## Cómo se invoca

En la página, llamar a la herramienta WebMCP `consultar_operacion_comex` con esos parámetros, o completar y enviar el formulario `#contact-form`. El envío genera un lead que hermes CE procesa.

## Notas

hermes CE — empresa de comercio exterior especializada en despacho de aduana. Buenos Aires, Argentina. Operaciones desde 1997.
