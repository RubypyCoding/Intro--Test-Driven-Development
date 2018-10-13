

## Test Driven Development

#### ¿Qué es un Test?

Las pruebas (tests) verifican que el código se comporte y produzca el resultado deseado.

Es importante entender las pruebas ya que el desarrollo basado en pruebas `test-driven development` es una metodología para entregar código de calidad.

#### ¿Qué es TDD?

El `TDD` es una metodología que permite desarrollar código pensando acerca de lo que quieres que el programa o aplicación haga y cómo quieres que el código se comporte antes de empezar a codificar.

Por el momento es importante comprender este concepto ya que varios de los ejercicios que realizarás en este bootcamp usarán pruebas `tests`, de esta manera tendrás que desarrollar tomando en cuenta las pruebas correspondientes para asegurarte que el programa se comporta y produce el resultado deseado.

## Proceso RED - GREEN - REFACTOR 

Para llevar a cabo el testeo `TDD` de tus programas seguiremos las siguientes etapas:

1) Etapa RED. Asegurate de que esté funcionando la librería para realizar las pruebas en el folder donde está ubicado el programa a testear. Está etapa nos indicará que hay ejemplos y fallas en las pruebas. Es normal todavía no hay código.

2) Etapa GREEN. Escribe el código lo más simple que puedas. No es importante que sea perfecto pero sí que funcione. El propósito principal en esta etapa es pasar la prueba, generalmente seguirán existiendo fallas en el código hasta pasar la pruebas correspondientes.

3) Etapa REFACTOR. Está etapa es un doble chequeo de que todas las pruebas están siendo pasadas. Es una oportunidad para mejorar el código con confianza ya que ejecutando las pruebas siempre estaremos probando que las expectativas actuales del código están siendo cumplidas.

4) Repetir hasta que las expectativas han sido cumplidas. Este proceso es conocido como RED-GREEN-REFACTOR.


## Ruby y TDD

En el caso de ruby estaremos usando `RSpec Testing Framework` que  es una librería diseñada que permite a los programadores describir el comportamiento y salidas de sus programas.


#### Instalando RSpec

Para usar `RSpec` en tus programas necesitarás tener instalado `RSpec gem`:

```ruby
$ gem install rspec
```

#### Ejecutando RSpec

Para ejecutar la prueba `test` es importante ubicarse en el folder del programa correspondiente y escribir en la terminal el siguiente comando:

```ruby
$ rspec
```

## Python y TDD

En el caso de Python estaremos usando el `unittest module` que viene incluido en el interprete de Python.  Es un módulo que permite a los programadores describir el comportamiento y salidas de sus programas. 

Las pruebas construidas para `unittest` son clases extendidas de `unittest.TestCase`.


#### Ejecutando pruebas con unittest

Para ejecutar la prueba `test` es importante ubicarse en el folder del programa correspondiente y escribir en la terminal el nombre del archivo que contiene la prueba. Por convención estos archivo empiezan con `test_`, de esta manera son reconocidos como pruebas `tests` a ser ejecutadas:

```python
$ test_<nombre_de_archivo>.py
```








