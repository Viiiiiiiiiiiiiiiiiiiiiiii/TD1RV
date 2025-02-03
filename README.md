# Our First Game Ever : Call Of Duty Black
using System;

class Program
{
    static void Main()
    {
        // Demander à l'utilisateur combien de nombres naturels il veut afficher
        Console.Write("Entrez le nombre n pour afficher les premiers n nombres naturels: ");
        int n = int.Parse(Console.ReadLine());

        int somme = 0;

        // Afficher les nombres naturels et calculer la somme
        Console.WriteLine("Les premiers " + n + " nombres naturels sont :");
        for (int i = 0; i < n; i++)
        {
            Console.Write(i + " ");
            somme += i;  // Ajouter le nombre courant à la somme
        }

        // Afficher la somme des nombres
        Console.WriteLine("\nLa somme des premiers " + n + " nombres naturels est : " + somme);
    }
}
