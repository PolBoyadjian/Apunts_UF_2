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
 
# Llenguatge de programació

## Codi executable

- Compila o interpreta
 - Compila/interpreta del codi font es fa:
  - Anàlisis léxic
  - Anàlisis sintactic
 - Un codi font correctament escrit no significa que funcioni segons lo desitjat
 - No es realitza un alàlisis semantic
 
## Llenguatjes compilats

- Exemples
 - C
 - C++
- Ventatja:
 - Execució molt eficient
- Desventatja:
 - Es necesari compilar cada vegada que el codi font es modifiqui
 
## Llenguatje interpretat

- Exemples
 -PHP
 -Javascripts
- Ventatja
 - El codi font s'interpreta directament
- Desventatja
 - Execució menys eficient

## Java
- Llenguatje compilat e interpretat
- Codi font Java es compila i s'obte un bytecode
- Després el bytecode s'interpreta per executarlo
- Ventatjes:
 - Estructurat i orientada a objectes
 - Facil d'apredre
 - Buna documentació i base d'usuaris
- Desventatjes:
 - Menys eficient que lleguatjes compilats

## Tipus
- Segons la forma en la que operan:
 - Declaratius: Indiquem el resultat a obtenir sense especifiar els pasos
  - Lógics: Utilitza normes (Prolog)
  - Funcionals: Utilitza funcions (Lisp, Haskell)
  - Algebraics: Utilitza sentencies (SQL)
 - Normalment son lleguatjes interpretats
 - Imperatius: Indiquem els pasos a seguir per obtenir el resultat
  - Estructurats: (C)
  - Orientat a objectes: (Java)
  - Multiparadigma: (C++, Javascript)
 - Llenguatjes orientats a objectes son també lleguatjes estructurats
 - Molts son compilats
 - Abstracció
  - Baix nivell: Ensamblador
  - Mitj nivell: C
  - Alt nivell: C++, Java
