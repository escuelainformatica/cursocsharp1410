# cursocsharp1410

```csharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            // como se define una variable?
            // <tipo de dato> <nombre variable> = <asigno valor>;
            // <tipo de dato> <nombre variable>;
            // var <nombre variable> = <asigno valor>;
            // variables:
            int numero = 20; // creando una variable entera y le asigno el numero 20
            int numero2; // esta variable no tiene valor.
            var numero3 = 20; // "var" es para indicar que se asuma el tipo de dato
            string texto = "hola mundo";
            char caracter = 'a'; // solo permite un caracter.
            double dec = 20.3;
            bool booleana = true;
            // tipos de datos
            // int: entero (tambien byte)
            // long: entero mas grande
            // string: textos, los textos se escriben entre comilla double
            // char: caracter, solo permite un caracter y se escribe entre comilla simple
            // double: decimales (tambien float, decimal)
            // bool: booleano
            
            // mostrar las variables
            Console.WriteLine("la variable texto ");
            Console.WriteLine(texto);

        }


        static void Main(string[] args)
        {
            // la variable es valida:
            // desde cuando se define, hasta el final del bloque de codigo
            var numero2 = 20;
            Console.WriteLine(numero2);
            // una variable puede asignarse un valor diferente
            numero2 = 100;
            Console.WriteLine(numero2);
            // arreglo:
            int[] numeros = new int[4] { 1, 2, 3, 4 };
            Console.WriteLine(numeros[2]);  // muestra el 3, ya que parte del indice cero.
            string[] paises = new string[3] { "Chile", "Argentina", "Peru" };
            Console.WriteLine(numeros[0]); // "Chile.
            // listas
            List<int> numeros2 = new List<int>() { 1,2,3,4};
            Console.WriteLine(numeros2[2]); //3 
            numeros2.Add(5); // agrego un elemento nuevo.
            List<string> ciudades = new List<string>();
            ciudades.Add("Arica");
            ciudades.Add("Iquique");
            ciudades.Add("Antofagasta");
        
        }
    }
}


```
