# Chatbot de Soporte Técnico - ISP Argentina

## Descripción
Chatbot simulador de soporte técnico para una empresa de servicios de Internet.
Desarrollado como Trabajo Práctico Integrador de Organización Empresarial - UTN.

## Proceso automatizado
Gestión de consultas técnicas de clientes: 
1. Validación de identidad 
2. Clasificación del problema
3. Derivación a técnico si corresponde.

## Tecnologías utilizadas
- HTML5
- JavaScript (vanilla)
- Base de datos simulada en JSON

## Cómo ejecutar
1. Clonar el repositorio
2. Abrir el archivo `index.html` en cualquier navegador
3. No requiere instalación ni servidor

## Flujo del bot
1. El cliente ingresa su DNI
2. El sistema valida si existe en la base de datos
3. El cliente selecciona el tipo de problema
4. El bot sugiere soluciones paso a paso
5. Si no se resuelve, se genera un ticket y se deriva a un técnico

## Clientes de prueba
| DNI | Estado |
|-----|--------|
| 12345678 | Activo |
| 87654321 | Activo |
| 11111111 | Suspendido |

## Diagrama BPMN
Ver archivo `diagram.svg` en este repositorio.