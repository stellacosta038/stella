ausing System;

namespace Pensionato
{
    class Program
    {
        static void Main(string[] args)
        {
            string[] quartos = new string[10];

            Console.Write("Quantos quartos serão alugados? ");
            int n = int.Parse(Console.ReadLine());

            for (int i = 1; i <= n; i++)
            {
                Console.WriteLine($"Aluguel #{i}:");
                Console.Write("Nome: ");
                string nome = Console.ReadLine();
                Console.Write("Email: ");
                string email = Console.ReadLine();
                Console.Write("Quarto (0 a 9): ");
                int quarto = int.Parse(Console.ReadLine());

                quartos[quarto] = $"{nome}, {email}";
            }

            Console.WriteLine("Quartos ocupados:");
            for (int i = 0; i < 10; i++)
            {
                if (quartos[i] != null)
                {
                    Console.WriteLine($"{i}: {quartos[i]}");
                }
            }
        }
    }
}
