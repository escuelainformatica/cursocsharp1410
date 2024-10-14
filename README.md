# cursocsharp1410

```sharp
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
    }
}


```
