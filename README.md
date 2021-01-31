# Apunts_UF_2

# Introduccion

## Objetivos de las pruebas

- Probar si el software no hace lo que debe hacer
- Probar si el software hace lo que no debe hacer
 
 # Pruebas

## Tipos de las pruebas

- Pruebas dinámicas: Requieren la ejeción de la aplicación.
- Pruebas estáticas: Se realizan sin ejecutar el código de la aplicación.

## Estretegias de prueba

- Caja negra: Se estudia el sistema desde fuera.
- Caja blanca: Se examina el código fuente y su ejecución.

## Estrategias de prueba de caja negra

- Se estudia el sistema desde fuera
- Se traba sobre la interfaz
- No se tienen en cuenta los detalles internos
- Se proporcionan entradas y se estudian las salidas
- Principales técnicas:
  - Particiones de equivalencia
  - Valores límite
  
## Estrategias de prueba de caja blanca

- Se comprueba el código fuente y su ejecución
- Se comprueba el código de ejecución dentro de cada unidad
- También se comprueba el código entre unidades durante la integración y entre subsistemas
- Principales técnicas:
  - Cobertura de código
  - Prueba de bucles

## Tipos de purebas

- Funcionales: Valoran el cumplimiento de los requisitos
- No Funcionales: Valoran aspectos adicionales como rendimiento, seguiradad...

## Pruebas funcionales

- Pruebas unitarias
- Pruebas de regresión
- Pruebas de integración
- Pruebas de humo
- Pruebas del sistema
- Pruebas alfa y beta
- Pruebas de aceptación

## Pruebas no funcionales

- Pruebas de usuabilidad
- Pruebas de rendiemiento
- Pruebas de stress
- Pruebas de seguridad
- Pruebas de compatibilidad
- Pruebas de portabilidad

## Mecanismos de prueba

- Manual
  - Pruebas realizadas por personal de la empresa o externo
- Automático
  - Compara los resultados obtenidos y los resultados esperados

## Soporte del depurador

- Puntos de ruptura
- Ejecución paso a paso
- Análisis de variables
  
## Automatización de pruebas

- Frameworks de pruebas
- Aserciones

## Frameworks para pruebas

- Java: JUnit, TestNG
- C++: CppUnit, Google Test
- PHP: PHPUnit
- Javasript: Mocha

## Caso de prueba

- Se compone por:
  - Una entrada conocida y sale por una salida esperada
  
## JUnit 4/5 - Anotaciones

- Las anotaciones se anteponen a la definición del método de prueba. Son:
  - JUnit4
    - BeforeClass: Se invoca antes de iniciar todos los tests y solo puede haber un método con esta anotación
    - Before: Se ejecuta antes de cada test
    - Test: Representa un test que se debe ejecutar
    - After: Se ejecuta después de cada test
    - AfterClass: Se invoca después de finalizar todos los test y sólo puede haber un método con esta anotación
    - Ignore: Los métodos marcados con esta anotación serán ignorados
   - JUnit5
     - BeforeAll
     - BeforeEach
     - Test
     - AfterEach
     - AfterAll
     - Ignore
 
# Integración

## Formas de integración

- Bib bang
- Descendente
- Ascendente
- Continua
 
## Integración continua

- Jenkins
- Bamboo
- TravisCI
- CircleCI
 
## Cobertura del código

- Indica el código que ha sido ejecutado durante las prubas
- Aconsejable que sea lo más cercano a 100%
- Si es 100% se ha ejecutado todo
- Si es menor no se ha ejecutado todo
- Se puede realizar la cobertura desde el IDE o servicio web

# Calidad

## Proceso/Producto

- QA garantiza la calidad en los procesos por los cuales se desarrollan los productos
- QC garantiza la calidad de los productos, se centran en identificar los defectos producidos

## Factores de calidad
- Operación
- Revisión
- Transición

## Operación del producto
- Corrección
- Fiabilidad
- Eficiencia
- Seguridad
- Facilidad de uso

## Revisión
- Mantenibilidad
- Flexibilidad
- Facilidad de prueba

## Transición
- Portabilidad
- Reusabilidad
- Interoperatividad
