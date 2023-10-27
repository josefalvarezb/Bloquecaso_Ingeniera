/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package temp.bloque.caso;

import java.util.Scanner;
public class TempBloqueCaso {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
    int opcion;
        
            
        
            Scanner leer = new Scanner(System.in);
            System.out.println("1. Practica clase 16");
            System.out.println("2. Practica clase 17");
            System.out.println("3. Practica clase 18");
            System.out.println("4. Dividir dos numeros");
            System.out.println("5. Multiplicar un numero cantidad de veces deseadas");
            System.out.println("6. Encontrar el menor número de 5 valores ingresados.");
            System.out.println("7. Sumar tres valores distintos.");
            System.out.println("8. Determinar un patron.");
            System.out.println("9. Determinar si un numero es multiplo de otro.");
            System.out.println("10. Calcular potencia.");
            System.out.println("11. Encontrar y mostrar numeros primos.");
            System.out.println("12. Nombrar las posiciones decimales de un numero.");
            System.out.println("Ingrese cualquier otro numero para salir del programa.");
            System.out.println("Ingrese su opcion: ");
            opcion = leer.nextInt();
            
            while (opcion < 13 && opcion > 0){
               switch (opcion){
                   case 1: 
                       System.out.println("Mi primer programa practica de sintaxis");
        System.out.println("Ingrese el numero entero");
        int Numero = leer.nextInt();
        System.out.println("Ingrese el numero real");
        double Valor = leer.nextDouble();
        System.out.println("Ingrese la letra");
        char Letra = leer.next().charAt(0);
        
        
        if (Numero<0){
               System.out.println("Negativo" + Numero); 
        }//segundo if
        else
            if (Numero == 0){
        System.out.println("cero" + Numero);
            }
            else {
             System.out.println("positivo" + Numero);
            }
        System.out.println("Se termino la practica del lunes 16 valor: "+Valor+" y Letra "+Letra+" No se usaron");
         break;
         
         
         case 2:
        System.out.println("Uso de residuo");
        System.out.println("Ingrese un numero entero: ");
        int Numer = leer.nextInt();
        if (Numer % 2 == 0){
            System.out.println("Par " + Numer);
        }
        else {
        System.out.println("Impar " + Numer);
        }
        break;
        
         case 3: {
             System.out.println("Uso de operadores logicos y matematico");
        System.out.println("p | q");
        System.out.println("V | V");
        System.out.println("V | F");
        System.out.println("F | V");
        System.out.println("F | F");
        System.out.println("Ingrese el Numero1 entero v=1 o F=0");
        int Numero1 = leer.nextInt();
        System.out.println("Ingrese el Numero2 entero V=1 o F=0");
        int Numero2 = leer.nextInt();
        
        if (Numero1 == 1 && Numero2 == 0){
            System.out.println("Respuesta verdadera");
        }
        else{
            if (Numero1 == 0 && Numero2 == 0){
            System.out.println("Respuesta Falsa");
        }
        
            else{
           if (Numero1 == 0 || Numero2 == 1){
                System.out.println("Respuesta falsa");
           }     
           else {
               if (Numero1 == 1 && Numero2 == 1){
                   System.out.println("Respuesta Verdadera");
               }
               else{
                   if (Numero1 == 0 && Numero2 == 0){
                       System.out.println("Respuesta Falsa");
                    }
                   else{
                       if (Numero1 == 0 || Numero1 == 1){
                         System.out.println("Respuesta Falsa"); 
                       }
                       else {
                           if (Numero1 == 1 || Numero2 == 0 ){
                               System.out.println("respuesta Falsa");
                           }
                       }
                   }
               }
           }//fin del else grande
            } // fin de caso 3
           break;
               
          case 4:{
             char res = 's';
             while (res == 's' || res == 'S') {
                 System.out.println("Ingrese numero 1: ");
                 int numprim = leer.nextInt();
                 System.out.println("Ingrese numero 2: ");
                 int num2 = leer.nextInt();
                 System.out.println("Dividendo " + numprim);
                 System.out.println("Divisor " + num2);
                 System.out.println("Cociente " + numprim / num2);
                 System.out.println("Residuo " + numprim % num2);
                 
                 System.out.println("Le gustaria continuar? (s/n)");
                 res = leer.next().charAt(0);
             } // fin del while
             }// fin del caso
               break;
                       
        
        
        
        
            case 5 :
             double c = 1;
             int numero, limite;
             System.out.println("Ingrese numero a multiplicar");
             numero = leer.nextInt();
             System.out.println("Ingrese el limite");
             limite = leer.nextInt();
             while (c<= limite){
                 System.out.println(numero + " * " + c + " = " + numero*c);
                 c++;
             }
             break;
         
               
               
               
       
        
         case 6:
            System.out.println("Este programa consiste en encontar el menor numero de 5 valores ingresados");
        
        System.out.println("Ingrese primer numero: ");
        int num1 = leer.nextInt();
        System.out.println("Ingrese segundo numero: ");
        int num2 = leer.nextInt();
        System.out.println("Ingrese tercer numero: ");
        int num3 = leer.nextInt();
        System.out.println("Ingrese cuarto numero: ");
        int num4 = leer.nextInt();
        System.out.println("Ingrese quinto numero: ");
        int num5 = leer.nextInt();
        
        
        
        if(num1 >= 1 && num1 <= 100 && num2 >= 1 && num2 <= 100 && num3 >= 1 && num3 <= 100 && num4 >= 1 && num4 <= 100 && num5 >= 1 && num5 <= 100){
 
            if (num1 < num2 && num1 < num3 && num1 < num4 && num1 < num5){
            System.out.println("El menor numero es : " + num1);
            } else if (num2 < num1 && num2 < num3 && num2 < num4 && num2 < num5){
            System.out.println("El menor numero es : " + num2);
            } else if (num3 < num1 && num3 < num2 && num3 < num4 && num3 < num5){
            System.out.println("El menor numero es : " + num3);
            } else if (num4 < num1 && num4 < num2 && num4 < num3 && num4 < num5){
            System.out.println("El menor numero es : " + num4);
            } else if (num5 < num1 && num5 < num2 && num5 < num3 && num5 < num4){
            System.out.println("El menor numero es : " + num5);
            } else{
            System.out.println("Todos los numeros son iguales");
            }
        } else{
        System.out.println("Ingrese numeros que esten dentro del rango del 1 al 100");
        }
        break;
        
         case 7:
        System.out.println("Este programa consiste en dar tres valores se muestra su suma");
        
        System.out.println("Ingrese su primer numero: ");
        int valor1 = leer.nextInt();
        System.out.println("Ingrese su segundo numero: ");
        int valor2 = leer.nextInt();
        System.out.println("Ingrese su tercer numero: ");
        int valor3 = leer.nextInt();
        
        if (valor1 != valor2 && valor1 != valor3 && valor2 != valor1 && valor2 != valor3 && valor3 != valor1 && valor3 != valor2){
        int suma = valor1 + valor2 + valor3;
        System.out.println("Suma = " + suma);
        }
        
        else if (valor1 == valor2 || valor1 == valor3 || valor2 == valor1 || valor2 == valor3 || valor3 == valor1 || valor3 == valor2){
        if (valor1 == valor2){
        System.out.println("Suma = " +  valor3);
        } else if (valor1 == valor3){
        System.out.println("Suma = " + valor2);
        } else if (valor2 == valor1){
        System.out.println("Suma = " + valor3);
        } else if (valor2 == valor3){
        System.out.println("Suma = " + valor1);
        } else if (valor3 == valor1){
        System.out.println("Suma = " + valor2);
        } else{
        System.out.println("Suma = " + valor1);
        }
        
        } // cierre else if
        
        break; // cierre else if
        
         // case 8: //
        // aqui va //
       
        
        case 9:
         
            System.out.println("Este programa consiste en leer dos numeros");
            System.out.println("Si el primero es multiplo del segundo mostrar la suma de ambos sino la resta");
         
            
            System.out.println("Ingrese el primer numero: ");
            int numero1 = leer.nextInt();
            
            System.out.println("Ingrese el segundo numero: ");
            int numero2 = leer.nextInt();
           
            if (numero1 % numero2 == 0){
            int sumanum = numero1 + numero2;
            System.out.println("El numero " + numero1 + " es multiplo de " + numero2 +  " por lo cual la suma de ambos es " + sumanum);
            }
            
            else{
            int sumanum2 = numero1 - numero2;
            System.out.println("El numero " + numero1 + " no es multiplo de " + numero2 + " por lo cual la resta de ambos es " + sumanum2);
            }
        break;   
            

         case 10:

        System.out.print("Ingresa la base: ");
        double base = leer.nextDouble();

        System.out.print("Ingresa el exponente: ");
        int exponente = leer.nextInt();

        double resultado = 1; 

        int contador = 1;
        while (contador <= exponente) {
            resultado *= base; 
            contador++;
        }

        System.out.println("La potencia es: " + resultado); 
        break;
        
         case 11:
             break;
        
        
         case 12: 
         System.out.println("Este programa consiste en que el usuario ingrese un numero de 5 digitos ");
         System.out.println("Y nombrar las posiciones decimales de cada uno");
         
         
        System.out.print("Ingresa un número entero de 4 dígitos: ");
        int nume = leer.nextInt();

        int cuartoDigito = nume % 10;
        int tercerDigito = (nume / 10) % 10;
        int segundoDigito = (nume / 100) % 10;
        int primerDigito = nume / 1000;

        System.out.println(primerDigito + " Milesimas ");
        System.out.println(segundoDigito + " Centesimas");
        System.out.println(tercerDigito + " Decimas");
        System.out.println(cuartoDigito + " Unidades");
        
        break;
    
        
         
               
        
               }
            System.out.println("1. Practica clase 16");
            System.out.println("2. Practica clase 17");
            System.out.println("3. Practica clase 18");
            System.out.println("4. Dividir dos numeros");
            System.out.println("5. Multiplicar un numero cantidad de veces deseadas");
            System.out.println("6. Encontrar el menor número de 5 valores ingresados.");
            System.out.println("7. Sumar tres valores distintos.");
            System.out.println("8. Determinar un patron.");
            System.out.println("9. Determinar si un numero es multiplo de otro.");
            System.out.println("10. Calcular potencia.");
            System.out.println("11. Encontrar y mostrar numeros primos.");
            System.out.println("12. Nombrar las posiciones decimales de un numero.");
            System.out.println("Ingrese cualquier otro numero para salir del programa.");
            System.out.println("Ingrese su opcion: ");
            
            opcion = leer.nextInt();
             
          }// cierre while
        

    }
    
}
