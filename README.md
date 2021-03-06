# Proyecto de Estructura de Datos: Sudoku

Este programa permite resolver sudokus en el formato clásico de 9 x 9 casillas.


### Tabla de contenido

* [Acerca del proyecto](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#acerca-del-proyecto)
* [Requerimientos del programa](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#requerimientos-del-programa)
* [¿Qué es sudoku?](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#qu%C3%A9-es-sudoku)
* [Reglas del juego](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#reglas-del-juego)
* [Instrucciones para ejecutar el programa](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#instrucciones-para-ejecutar-el-programa)
* [Preguntas Frecuentes](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#preguntas-frecuentes)
* [Contacto](https://github.com/IvanaLuBE/Sudoku/blob/master/README.md#contacto)
****




### Requerimientos del programa
Para correr el programa se necesita un Entorno de Desarrollo Integrado(EDI) para Java, como [Neatbeans](https://netbeans.org/images_www/v6/download/community/8.2/) o [Eclipse](https://www.eclipse.org/downloads/).
***


### ¿Qué es sudoku?

Sudoku es un juego matemático japonés. Consiste en un recuadro de 81 casillas y estás están divididas en 9 cuadrantes de 3 x 3 casillas cada uno.

El objetivo del juego es rellenar todas las casillas a partir de las pistas iniciales mientras se siguen las siguientes reglas:
* Las casillas solo se pueden rellenar con numeros del 1 al 9.
* Un número no se puede repetir en una misma columna, en un mismo renglón o en un mismo cuadrante de 3 x 3 casillas.


***

### Instrucciones para ejecutar el programa
1. Descargar el programa contenido en este repositorio, puede clonarlo mediante [Git bash](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) 
o bien descargarlo de la página principal del [repositorio](https://github.com/IvanaLuBE/Sudoku). Para la última opción debe presionar el botón verde **Code** y descargarlo como ZIP.
2. Abrir el EDI de su preferencia.
3. Hacer click en **Abrir proyecto** y seleccionar el archivo **Sudoku** que acaba de descargar. Si descargó el archivo como ZIP debe descomprimirlo primero.
 Al abrir el proyecto en el EDI se despliegan los siguientes archivos.
  
   ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/Directorio.PNG)

 4. El archivo que contiene al ejecutable es el último: SudokuI.java. Para ejecutar el programa basta con hacer click derecho en el archivo y seleccionar la opción **Run File**.
 
    ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/RunFile.png)
 5. A continuación se desplegará la siguiente interfaz:
 
    ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/Interfaz.png)
    
 6. Una vez configurado el paso anterior ya puede usar el programa. Para hacerlo debe ingresar en las casillas los números del sudoku a resolver.
 
    Por ejemplo:
 
    ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/SudokuSinResolver.png)
    
7. Al oprimir el botón **Resolver** el programa muestra la primera solución que encontró. 

   Es importante destacar que esta solución no es la única respuesta posible.

   En la solución los números que usted ingresó se muestran en casillas blancas y los de la solución en casillas verdes.
 
    ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/SudokuResuelto.png)
8. Si quiere resolver otro sudoku, el botón **Limpiar** deja listo el programa para usarse nuevamente.
9. Si ya acabo de usarlo puede cerrar el programa con el botón derecho superior que tiene una X y posteriormente cerrar el EDI.


 ***
 
 
 
 ## Preguntas Frecuentes
 1.  ¿Cómo puedo saber si el sudoku que ingresé tiene algún error?
 
     El programa indica con un mensaje en la parte inferior cuando encuentre un casilla en la que no se cumpla alguna de las reglas.
     Algunos de los errores más comunes se muestran en las siguientes imágenes:
     
     ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/ErrorColumna.png)
     ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/ErrorCuadrante.png)
     ![alt text](https://github.com/IvanaLuBE/Sudoku/blob/master/images/ErrorCaracterInvalido.png)
     
 2. Al resolver el sudoku por mí mismo encontré otra solución, ¿por qué no es la misma que muestra el programa?
 
    El programa muestra la primera respuesta encontrada, pero esto no significa que sea la única, ni hay una solución mejor que otra. 
    
 3. ¿Se guardan los sudokus que resolví?
 
    No, lamentablemente no se guarda el historial de juegos resueltos.
    
 4. ¿Hay algún sudoku que no pueda resolver?
 
    No, si hay alguna respuesta posible la encontrará. El programa funciona de manera rápida y eficiente
    
 5. ¿Que tanto espacio de memoria necesita el programa para ejecutarse?
 
    El programa es muy liviano, necesita solo 792 KB de memoria.
    
 6. ¿Hay un número límite de juegos que pueda resolver?
 
    No, puede utilizarlo todas las veces que quiera.
    
 7. ¿Puedo utilizar otro formato de sudoku?
 
     No, es cierto que existen distintos formatos como Supersudoku de 16×16 casillas o Juuni sudoku de 12 x 12 casillas, pero este programa solo sirve para el formato clásico.
 ***
    
 ### Contacto
 Si tienes alguna duda no dudes en contactarme al correo : ivanalucho@gmail.com

    
