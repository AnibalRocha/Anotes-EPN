# Anotes-EPN
# >ESTRUCTURA DE JAVA
* Hola.java
## >PAQUETE
## >DECLARACIONES GLOBALES
## >METODOS + main
 -Retorna valor
 | -No retorna valor
```c
public class Hola{`
// Hola debe ser igual que el nombre del proyecto o de clase

   public static void main(){ `

    // void no retorna valores    
    //string nombre -> declaramos una variable "hola luis" <tipo dato>
```
-> dentro del () es la PROPIEDA/ATRIBUTO -> < AMBITO > < TIPO DE DATO > < NOMBREVARIABLE >

< tipo dato > 
- String
- Intege
- Bool
- Int
- ...
// SI ESTA EN MINUSCULA SON DATOS PRIMITIVOS

```c    
        System.out.printf("hola mundo");
        -> STRING NOMBRE = ""; -> DECLARA VARIABLE
        -> NOMBRE = "PAT_MIC"; ->INICIACION
   }
}
```
// SI ESTA EN MINUSCULA SON DATOS PRIMITIVOS

```c    
        System.out.printf("hola mundo");
        -> STRING NOMBRE = ""; -> DECLARA VARIABLE
        -> NOMBRE = "PAT_MIC"; ->INICIACION
   }
}
```
ALGORITMIA -------> ALGORITMO --(+SOLUCION)----> PROBLEMA

## ALGORITMIA
    1 SPC
    2 DF
    3 CODE (JAVA)
    4 +TRACE -> DEBUG

` DETERMINAR EL MAYOR DE 2# `
```c
public class App {
    public static void main(String[ ] arg) {
        int a = 20, b= 10;
        if (a>b){
            System.out.println("El mayor es:"+a);
            
        }else {
            System.out.println("el mayor es:"+b);
    }
}
}
```
```c
public class App {
    public static void main(String[ ] arg) {
        int a = 10, b= 10;
        if (a>b){
            System.out.println("El mayor es:"+a);
            
        }else {
            System.out.println("el mayor es:"+b);
    }
}
}
```
```c
public class probando {

        public static void main(String[ ] arg) {
            int a = 10, b= 80;
            if (a==b)
                System.out.println("Son iguales");
            if(a>b)
                System.out.println("El mayor es:"+a);    
            if(b>a) 
                System.out.println("el mayor es:"+b);
        }
}
```

` para correr por consola de bash `
- javac src/NombreArchoivo.java
- java src/NombreArchivo.java
