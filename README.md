# Simulacro de Examen II Entornos de Desarrollo 3er Trimestre

Simulacro de examen II de la asignatura **Entornos de Desarrollo** de DAM (CESUR Mallorca) para el curso 2022-2023.

## :clipboard: Enunciado:

## :mag: Análisis de entidades:

Dado el enunciado anterior, se distinguen los siguientes elementos para el diagrama de clases a desarrollar:

-  Agencia
-  Coche
-  Garage
-  Cliente
-  Reserva

Cada una de estas entidades tendrá los atributos que se han mencionado en el enunciado.

## :bulb: Solución propuesta:

![Captura de Pantalla del diagrama](diagrama.png "Captura de Pantalla del diagrama")

## :pencil2: Posibles mejoras

-  Los modelos de coches, marcas y colores podrían ser acotados mediante clases de tipo Enum para mayor integridad.
-  Se ha establecido la relación entre Agencia y Coche como composición dado que se ha supuesto que una agencia de alquileres no puede existir sin tener coches para alquilar.
-  Cabe mencionar que un Coche puede estar en varias reservas siempre y cuando sean con fechas diferentes. Este hecho debería ser tratado de alguna forma, ya sea en el modelo o mediante instrucciones cuando se traduzca a código fuente.
