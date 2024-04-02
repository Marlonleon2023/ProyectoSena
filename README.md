# Sistema de Control de Ingreso de Estudiantes del Centro de Industria y Construcción del Sena

El Centro de Industria y Construcción del Sena regional Tolima quiere implementar un sistema de control de ingreso que permita contar los estudiantes que ingresan durante los seis días a la semana, así como el número de estudiantes por formación. Para el ejemplo, se tienen en cuenta las siguientes formaciones: ADSO, producción multimedia, desarrollo de videojuegos y sistemas. El algoritmo debe indicar el total de estudiantes clasificados por cada programa y por día. Al finalizar la semana, debe generar un reporte con la cantidad de estudiantes que ingresaron al centro de formación.

## Instrucciones de uso

1. **Ejecución del programa**: Para ejecutar el programa, simplemente sigue las instrucciones que aparecen en pantalla.
2. **Ingreso de información**: Proporciona el nombre de cada estudiante que ingresa al centro y selecciona su formación entre las opciones disponibles.
3. **Clasificación de estudiantes**: El sistema clasifica automáticamente a los estudiantes por formación y por día.

## Formaciones disponibles

El programa reconoce las siguientes formaciones disponibles en el Centro de Industria y Construcción del Sena:
- **ADSO**: Arquitectura y Desarrollo de Software
- **Producción multimedia**
- **Desarrollo de videojuegos**
- **Sistemas**

## Generación de informes

Al finalizar la semana, el sistema genera un informe detallado que incluye:
- La cantidad de estudiantes que ingresaron al centro de formación, clasificados por formación y por día.


## Variables a tener  en cuanta 
1. estudianteDia: Esta variable se reinicia a cero al comienzo de cada día para calcular cuántos estudiantes ingresaron en cada día de la semana, asegurando que no se acumulen los estudiantes de los días anteriores.

2. estudenContador: Se utiliza para realizar un seguimiento del número total de estudiantes que ingresan al centro de formación a lo largo de la semana.

2. ingresoenDia: Se incrementa en 1 si al menos un estudiante ingresó durante el día actual, lo que ayuda a rastrear cuántos días de la semana tuvieron al menos un estudiante que ingresó al centro de formación.



## Autor y contacto
Autor: Marlon Esteban Leon rojas 
Contacto: marlonestebanleonrojas@gmail.com
