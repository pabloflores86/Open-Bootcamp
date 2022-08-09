
**PARTE 1**

package com.mycompany.introduccionjava;

public class IntroduccionJava {

    public static void main(String[] args) {

        
        System.out.println(Suma(10, 20, 5));
                
    }
    public static int Suma (int a, int b, int c){
        return (a + b + c);
            }
}


**PARTE 2**
Clase MAIN

package com.mycompany.introduccionjava;

public class IntroduccionJava {

public static void main(String[] args) {

    Coche miCoche = new Coche();
    miCoche.AgregarPuerta();
    System.out.println(miCoche.numeroPuertas);
}
}

Clase Coche

package com.mycompany.introduccionjava;

public class Coche {
  

public int numeroPuertas = 0;
public void AgregarPuerta () { 
    this.numeroPuertas++;
}
   
}

