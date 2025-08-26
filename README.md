# Faktoriel.sln

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
