// Напишите программу, которая на вход принимает число и выдаёт, является ли число чётным (делится ли оно на два без остатка)

 System.Console.Write("input x: ");
  int x = Convert.ToInt32(Console.ReadLine());

  System.Console.Write("input y: ");
   int y = Convert.ToInt32(Console.ReadLine());

     if (x % 2 == 0)
     {
     Console.WriteLine("YES");
     }
     else
     {
     Console.WriteLine("NO");
     }

     if(x%y == 0)
     {
        Console.WriteLine("yes");
     }
     else
     {
        Console.WriteLine("no");
     }
