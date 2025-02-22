using System;

namespace MyCompiler {
    class Program {

         void ejemploc() {
         String path ="C:\\p1\\misarchivos\\archivo.txt";
             String contenido = "Mi primer archivo plano";
            file.WriteAllText(path,contenido);
             Console.WriteLine("Archivo creado");        
         }

        void ejemploleer() {
            String path ="C:\\p1\\misarchivos\\archivo.txt"; 
            String contenido = file.ReadAllText (path);
            Console.WriteLine ("contenido del archivo");
            Console.WriteLine (contenido);
            }

        void ejemploleerlieas() {
            String path ="C:\\p1\\misarchivos\\archivo.txt"; 
            String[] lineas = file.ReadAllLines (path);
            foreach(string linea in lineas) {
                Console.WriteLine("líneas Numero :"+ linea);
                } 

int contador = 1; 

foreach (var linea in listaDeLineas) 
{
    Console.WriteLine($"Línea Número {contador}: {linea}");
    contador++; 
}

            
       }

        
        }
    }

