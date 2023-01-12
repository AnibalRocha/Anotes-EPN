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

# clases y programas en java
```c
import java.util.Scanner;

/*
 * @autor : luis
 * @date : 06.12.22
 * @version: ...
 * Determinar el area de un rectangulo
*/
public class App {
    /*
     * Programa pricnipal
     * @param args; no requiere
     * @throws Exception
    */
    public static void main(String[] args){
        //calcularAreaRect();
        //showSignosExt();
        
    }

    private static void showSignosExt() {
        int nroTerminos=0;
        Scanner sc= new Scanner(System.in);
        System.out.print("ingrese nro.Terminos:");
        nroTerminos = sc.nextInt();
        
        for (int i=0; i < nroTerminos; i++){
            //if (i%2==0)
                System.out.print((i%2==0)?"+ ":"- ");
            //else

            //System.out.print("- ");
        }
        sc.close();
    }

    private static void calcularAreaRect() {
        //Declarar la varibale e iniciacion
        int longitud =0, ancho =0 , areaRect=0;
        Scanner sc= new Scanner(System.in);

        System.out.println("ingrese la longitud");
        longitud = sc.nextInt();

        System.out.println("Ingrese el ancho:");
        ancho = sc.nextInt();

        areaRect = ancho*longitud;

        System.out.println("El area es:" + areaRect);
        sc.close();
    }
}
// deber 
```
# Introducción a la Programación,Algoritmos y diseño

## Introduccion y Terminologia de Hadware

- Intalacion de Visual Code con los paquetes de java
- Controles de Java en visual code
    - ctrol + shift + p
    - ctrol + p
    - ctrol + b
    - ctrol + t
    - ctrol + space, shift + space
    - ctrol + alt + a / ctrol + k + c
    - ctrol + d

- comandos de git
    - $ gitversion
    - $ pwd
    - $ gitinit
- ¿ QUE ES EL GIT?
    * herramienta para facilitar el desarrollo colaborativode software.

### ALgoritmia
    * Apartir de un problema se puede solucionar a travez de pasos consecutivos especificamente funciona un algoritmo, desde la parte incial y final.
    * se esctructura haciendo la solucion del problema (algortimo, diagrama de flujo, codigo) 

>> EJEMPLOS DE TESTING DE JAVA
  ```c
  publicclassTesting{/*** valida la compilación del java*/publicstaticvoidTestJava(){
    System.out.printf("java are ready..!");}
    /**
     * valida la compilación del java con saludo
     * @paramnombre: escribe tu nombre
     * @paramfecha: es la fecha actual*     @returnun saludo*/publicstaticStringTestJavaSaluda(Stringnombre,Stringfecha){
     return"java te saluda "+nombre+" "+fecha;}
  }
  ```

  ### VARIABLES PRIMITIVAS
  ```JAVA
  int, long(tipos enteros)
  float, double(tipos de punto flotante)
  char(tipo carácter)
  ```
  ### VARIABLES DE REFERENCIA
  ```JAVA
  Stringname= "ThanhNguyen";
  Calendar fechaNac;
  
  String: str
  charAt(index)      
  // obtener un carácterLength
  // obtener la longitud del stringEquals
  // comparación equalsIgnoreCase
  // ignorar si es mayúsculas o minúscula 
  Scanner : std
  Scanner stdIn = new Scanner(System.in);
  
  <variable> = stdIn.nextLine();
  nextInt() 
  //Se salta los espacios dejados en blanco hasta que encuentra un valor de tipo
  intnextLong() 
  //Se salta los espacios dejados en blanco hasta que encuentra un valor de tipo   
  longnextFloat() 
  //Se salta los espacios dejados en blanco hasta que encuentra un valor de tipo 
  floatnextDouble() 
  //Se salta los espacios dejados en blanco hasta que encuentra un valor de tipo double“salta los espacios dejados en blanco ”
  next() 
  //Se salta los espacios dejados en blanco hasta que encuentra un token. Devuelve el token como un valor tipo String.
  ```
### CADENA DE CARACTERES 
``` JAVA
    // caracteres + cadena de caracteres : string/ array / vector
    charletra ='a';
    // 1 2 3 q ` # $ % 6 & \n \t \r %%
    charcaracter='1';
    // --> |1| (8bit = 1 byte) --> |0|0|0|1|1|1|
    charpalabra[10]="HOLA";
    // |H|O|L|A|||||||| --> vectorcharpalabras[]="Como estas pepe...";
    Stringpalabras;   →palabras[]
```
### ENTRADA DESDE CONSOLA
```JAVA
    c = charAt( );
    while(c ! =  EOF)  { ... }
    while((c = charAt( ))! = EOF) { ... }
    while(c = charAt( )! = EOF) 
```

## IDE DE DESARROLLO CON POO - JAVA
Programación Orientada a Objetos en Java - AEPI. La programación orientada a objetos (POO) es un paradigma de programación que usa objetos para crear aplicaciones. Está basada en tres pilares fundamentales: herencia, polimorfismo, encapsulación.

![Image text](IMAGENES_MD\POO.PNG)

### PROGRAMACION ESTRUCTURADA
>> La programacion estructura esta conformado por:
- Procedimientos  → `voidABC(<params>) { code}`
- Funciones → `<TipoDato> ABC(<params>) { code...; return<TipoDato> }`
- Variables globales y locales-Librerías → `*.h`

>> Ejemplo
```JAVA
    main()
    {
        addLagartija(); 
        //[ESTRUCTURA]-> structlagartija    [intvidaMeses, intdedos, stringnombre, .... ]
        restar();
        ---
    }
```
## PROGRAMACION O.O
    ESTA ESTRUCTURADO POR:
    - LIBRERIAS, PAQUETES
    + HERENCIAS

    - CLASES
        -METODOS -> ``` <ámbito> voidABC(<params>) { code}
                        <ámbito> <TipoDato> ABC(<params>) { code...; return<TipoDato> } ```
        -ATRIBUTOS -> ``` <ámbito> Variables globales y locales```
    - OBJETOS
    - ENCAPSULAMIENTO
    - ABSTRACCION 
    - ESPECIFICACION
    - GENERALIZACION
    - EVENTO - MENSAJE

    + Ambito
        + publico
        - privato
        ~ protegido
---
    UN OBJETO (IGUANA) DEBE SER DECLARADO:
    > CARACTERISTICAS
        + NOMBRE
        + TAMAÑO
        + COLOR
    > ACCIONES
        + COMER
        + CORRER
        + REPRODUCCIOR

## HERENCIA
    La HERENCIA tambien se denomina EXTENSION o GENERALIZACION

    UNA HERENCIA ES UNA CLASE MADRE DONDE IRA DISTRIBUYENDO A LOS OBJETOS QUE TOME Y HERENDEN DE LA CLASE MADRE
    COMO (VEHICULO):
    * TODOS los coches SON vehiculos
    LA HERENCIA ES UN MECANISMO  POR EL QUE SE PUEDE CREAR NUEVAS CLASES A PARTIR DE OTRAS EXISTENTES
    - heredando  la clase y ser posible modificacion y añadiendo atributos y operacionales

    *SUBCLASE.- SE PUEDE ELEGIR REDIFINIR LAS OPERACIONES
## NOMENCLATURA
![Image text](IMAGENES_MD\NOMENCLATURA.PNG)

## IMPLEMENTACION
```JAVA
    //CLASE QUE SE REPRESENTA UN VEHICULO 

    public class Vehiculo{
        // colores que se puede pintar el vehiculo
        public static enum Color{ROJO, VERDE, AZUL}

        // ATRIBUTOS
        private Color color;
        private final int numSerie;

        // contructor de vehiculo
        public Vehiculo(Color color , int numSerie)
        {
            this.color=color;
            this.numSerie=numSerie;

        }
    }
```
---
```JAVA
    // RETORNA LOS VALORES DE VEHICULO
    
    // RETORNA LOS VALORES DE COLOR
    public Color color(){
        return color;
    }

    //RETORNA LOS VALORES DE SERIE
    public int numSerie(){
        return numSerie;
    }
    
    //REALIZACION DE PINTAR DEL VEHICULO A UN COLOR
    public void pintar(Color c)
    {
        color = c;
    }

```
---
```JAVA
    //USAMOS EL METODO DE HERENCIA 
    public class Coche extends Vehiculo{

        // CILINDRADA DEL COCHE
        private int cilindrada;

        /** RETORNA LA CILINDRADA DEL COCHE...*/
        public int cilindrada(){
            return cilindrada;
        }

        // CAMBIA LA CILINDRADA DEL COCHE
        public void cambiaCilindrada(int c){
            this.cilindrada=c;
        }
    }
```
    LOS CONSTRUCTORES NO SE HEREDAN
        * LAS SUBCLASES DEBEN DEFINIRSE SU PROPIO CONSTRUCTOR
    NORMALMENTE SERA NECESARIO INICIALIZACION DE LOS ATRIBUTOS DE LAS SUPERCLASES 
        * PARA ELLO SE LLAMA CONSTRUCTORES DESDE LA SUBCLASE
```JAVA
    /* CONTRUCTORES DE UNA SUBCLASE */
    public Subclase(parametros....){
        // invoca el constructor de la clase
        super(parametros para la superclases);
        // inializa sus atributos
    }
```
    SE LLAMA SUPER Y DEBE SER PRIMERA INSTROCCION DEL CONSTRUCTOR DE LA SUBCLASE

![Image text](IMAGENES_MD\SUPERCLASE.PNG)

    EN EL CASO DE QUE LA SUPERCLASE NO TENGA UN CONSTRUCTOR SIN PARAMETROS SE PRODUCIRA UN ERROR DE COMPILACION

![Image text](IMAGENES_MD\SUPERCLASE1.PNG)

## CASO DE USO
Toma todos los requerimientos para proyectar un programa y asi cumplir con los requerimientos de la estructura de un programa a la cual se construya a fututro

![Image text](IMAGENES_MD\CASOSDEUSOS.PNG)

    ESTA COMPUESTO DE:
        * DIAGRAMAS
            -ACTORES
                Es la persona que interactura con el sistema (hardware y software)
            -FUNCIONALIDADES(CASOS DE USO)
            -RELACIONES
                Usamos para ligar a los casos relacionando al campo de ejecucion
                * Tipos de relaciones:

![Image text](IMAGENES_MD\ENLACESUSOS.PNG)
    
    <<include>>
    Especifica a un caso de uso base, declarando la dependencia que declara un caso de uso
    
    <<extend>>
    incluye un conjunto de pasos que ocurren en algunas ocupaciones, interrumpiento los casos a ejecutarse

        * ESPECIFICACION 
            -ESCENARIO
            -RESTRICCIONES


## javax.swing.JOptinePane

    Es una clase que nos provee una conjunto de ventanas de dialogo que es ideal, para mostrar mensajes al usuario. Ya sean informativos, advertencias, errores, confirmaciones

## INTERFAZ

    Una interfaz de Java es un mecanismo que tiene este lenguaje de programación para enunciar un conjunto de especificaciones y comportamiento que otras clases van a implementar.
    Una interfaz de programación de aplicaciones (API) es un conjunto de herramientas, definiciones y protocolos que se utiliza para integrar los servicios y el software de aplicaciones.

```JAVA
    public interface IdentificadorInterfaz {
    // Cuerpo de la interfaz ...
    } 
```
```JAVA
    public interface Modificacion {
        void incremento(int a);
    }
```
```JAVA
    public interface IdentificadorInterfaz {
        // Cuerpo de la interfaz ...
    } 
```
```JAVA
/**
 * Declaracion de la interfaz Modificacion
 */
public interface Modificacion {
    void incremento(int a);
}
```
```JAVA
    /**
    * Declaracion de la interfaz Constantes
    */
    public interface Constantes {
        double VALOR_MAXIMO = 10000000.0;
        double VALOR_MINIMO = -0.01;
    }
```
```JAVA
/**
 * Declaracion de la interfaz Numerico
 */
public interface Numerico {
    double EPSILON = 0.000001;
    void establecePrecision(float p);
    void estableceMaximo(float m);
}
```
```JAVA
/**
 * Declaracion de la clase Acumulador
 */
public class Acumulador implements Modificacion {
    private int valor;
 
    public Acumulador (int i) {
        this.valor = i;
    }
 
    public int daValor () {
        return this.valor;
    }
 
    public void incremento (int a) {
        this.valor += a;
    }
}
```
### Interfaz Grafica

    La interfaz de usuario es la parte del programa que permite al usuario interaccionar con él. La API de Java proporciona una biblioteca de clases para el desarrollo de Interfaces gráficas de usuario (en realidad son dos).
  ---  
    - La interfaz de usuario es la parte del programa que permite al usuario interaccionar con él.

- La API de Java proporciona una biblioteca de clases para el desarrollo de Interfaces gráficas de usuario (en realidad son dos).

- La biblioteca proporciona un conjunto de herramientas para la construcción de interfaces gráficas que tienen una apariencia y se comportan de forma semejante en todas las plataformas en las que se ejecuten.

- La estructura básica de la biblioteca gira en torno a componentes y contenedores.

- Los contenedores contienen componentes y son componentes a su vez, de forma que los eventos pueden tratarse tanto en contenedores como en componentes. La API está constituida por clases, interfaces y derivaciones. AWT y Swing
---
    A continuacion, un ejemplo de la creacion de un panel:
```JAVA

 JFrame frm  = new JFrame();                                  
 frm.setTitle("Principal");                                   
 frm.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);          
 frm.setResizable(false);                                     
 frm.setSize(500,500);                                        
 frm.setVisible(true); 
```
 
