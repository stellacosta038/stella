using System;

class Program {
  static void Main(string[] args) {

    Console.Write("Digite o valor de N: ");
    int n = int.Parse(Console.ReadLine());
    
    int[,] matriz = new int[n,n];

    Console.WriteLine("Digite a matriz:");

    for (int i=0; i<n; i++) {
      string[] valores = Console.ReadLine().Split(' ');
      for (int j=0; j<n; j++) {
        matriz[i,j] = int.Parse(valores[j]);
      }
    }

    Console.Write("Diagonal principal: ");
    for (int i=0; i<n; i++) {
      Console.Write(matriz[i,i] + " ");
    }

    int negativos = 0;
    for (int i=0; i<n; i++) {
      for (int j=0; j<n; j++) {
        if (matriz[i,j] < 0) {
          negativos++;
        }
      }
    }
    Console.WriteLine("\nNúmeros negativos: " + negativos);

  }
}
