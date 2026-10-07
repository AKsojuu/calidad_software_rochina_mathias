# Calidad de Software

Este repositorio contiene materiales y actividades relacionados con la materia **Calidad de Software**.

## Objetivo

La calidad de software busca asegurar que un sistema sea confiable, mantenible, seguro y útil para sus usuarios. Esto se logra mediante buenas prácticas de desarrollo, revisión del código y diferentes tipos de pruebas.

## Conceptos básicos

### Calidad de software

La calidad de software se refiere a qué tan bien un producto cumple con sus requisitos, funciona correctamente y puede ser modificado con seguridad.

Algunos atributos importantes son:

- **Funcionalidad:** el sistema realiza las tareas esperadas.
- **Confiabilidad:** el sistema funciona de manera estable.
- **Mantenibilidad:** el código puede comprenderse y modificarse fácilmente.
- **Usabilidad:** los usuarios pueden utilizar la aplicación sin dificultad.
- **Seguridad:** la aplicación protege la información y evita accesos no autorizados.
- **Rendimiento:** la aplicación responde de forma adecuada bajo distintas condiciones.

### Pruebas de software

Las pruebas permiten verificar que el comportamiento del sistema coincide con los requisitos esperados. Una prueba exitosa reduce el riesgo de errores en producción.

## Pruebas unitarias

Las pruebas unitarias verifican el comportamiento de una unidad pequeña del código, como una función o un método, de forma aislada.

Principales características:

- Se enfocan en una función concreta.
- Se ejecutan de forma rápida.
- Ayudan a detectar errores en lógica y condiciones.
- Deben ser independientes entre sí.
- Generalmente se ejecutan con herramientas como Jest, Pytest, JUnit o PHPUnit.

Ejemplo de objetivo de una prueba unitaria:

> Verificar que una función de suma devuelve el resultado esperado para varios valores.

## Pruebas end-to-end

Las pruebas end-to-end evalúan el flujo completo de una aplicación, desde la interacción del usuario hasta la respuesta del sistema.

Principales características:

- Simulan acciones reales del usuario.
- Verifican la integración entre interfaces, servicios y datos.
- Detectan problemas que pueden pasar desapercibidos en pruebas unitarias.
- Su ejecución suele ser más lenta y requiere mayor preparación.
- Herramientas comunes incluyen Cypress, Playwright, Selenium y TestCafe.

Ejemplo de objetivo de una prueba end-to-end:

> Verificar que un usuario puede iniciar sesión, acceder a su cuenta y cerrar sesión correctamente.

## Diferencias principales

| Tipo de prueba | Alcance | Velocidad | Objetivo principal |
| --- | --- | --- | --- |
| Unitarias | Una función o método | Rápida | Comprobar la lógica individual |
| End-to-end | Flujo completo de la aplicación | Más lenta | Comprobar la experiencia y la integración |

## Recomendaciones

- Escribir pruebas antes o junto con el desarrollo cuando sea posible.
- Mantener las pruebas pequeñas y verificables.
- Usar nombres claros que describan el comportamiento esperado.
- Evitar dependencias innecesarias entre pruebas.
- Ejecutar pruebas unitarias frecuentemente.
- Complementar las pruebas unitarias con pruebas de integración y end-to-end.

## Contribución

Cada actividad y ejercicio del repositorio debe incluir una explicación breve, el código necesario y las pruebas correspondientes.
