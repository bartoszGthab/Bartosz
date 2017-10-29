System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            string name = Console.ReadLine(); // Odczytujemy linie z klawiatury (zatwierdza klawisz enter) do zmiennej o nazwie 'name'
            if (name.EndsWith("a")) // jeśli zmienna "name" konczy się na "a" to wtedy
            {
                Console.WriteLine("Żenskie imie!!");
            }
            else
            { // a jeśli NIE kończy sie na "a"
                Console.WriteLine("Męskie imie!!");
            }
            Console.ReadLine(); // Pauza żeby dało się odczytać wynik, możesz spróbować co bedzie bez tej linii
        }
    }
}
