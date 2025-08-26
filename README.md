# Faktoriel.sln

- **Link:** [Quera Problem #589](https://quera.org/problemset/589)
- **Description:** Write programs that take the number **n** and calculate and display its factorial.
- **Solution:** Implemented in C#.

namespace faktoriel
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.WriteLine("Enter a number:");
            int n = Convert.ToInt32(Console.ReadLine());
            int factoriel = 1;
            for (int i = 2; i <= n; i++)
            { 
                factoriel *= i;
            }
            Console.WriteLine(factoriel);
        }
    }
}
