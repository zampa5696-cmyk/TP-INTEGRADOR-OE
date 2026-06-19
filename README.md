# Chatbot de Asistencia Tecnica para Proveedor de Internet - ISP Argentina

## Descripción General
Aplicación de chatbot diseñada para simular el proceso de atención y soporte técnico de una empresa proveedora de servicios de Internet. Este proyecto fue desarrollado como Trabajo Práctico Integrador de la materia Organización Empresarial en la UTN.

## Funcionalidades Principales
El sistema automatiza la atención de consultas técnicas mediante las siguientes etapas:

1. Verificación de la identidad del cliente.
2. Identificación y categorización del inconveniente reportado.
3. Escalamiento del caso a un técnico especializado cuando sea necesario.

## Tecnologías Implementadas
- HTML5
- JavaScript (vanilla)
- Base de datos simulada en JSON

## Instrucciones de Uso
1. Clonar el repositorio
2. Abrir el archivo `index.html` en cualquier navegador
3. No se requiere instalación de dependencias ni configuración de servidor.

## Funcionamiento del Chatbot
1. El usuario ingresa su DNI
2. El sistema verifica la existencia y estado del cliente en la base de datos.
3. El usuario selecciona la categoría del problema que desea resolver.
4. El chatbot proporciona recomendaciones y pasos de solución.
5. Si el inconveniente persiste, se genera un ticket de soporte y el caso es derivado a un técnico.

## Datos de Prueba
| DNI | Estado |
|-----|--------|
| 12345678 | Activo |
| 87654321 | Activo |
| 11111111 | Suspendido |

## Documentación del Proceso
El diagrama BPMN correspondiente al flujo de atención puede consultarse en el archivo`diagram.svg` incluido en este repositorio.