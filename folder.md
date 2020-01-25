WAP IN C# TO SHOW THE USE OF FOR-LOOP.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)
        {
            long p;
            int n;
            Console.WriteLine("Value of n  2 to power n");

            Console.WriteLine("________________________");
            p = 1L;
            for (n = 0; n < 10; n++)
            {
                if (n == 0)
                    p = 1L;
                else
                    p = p * 2;

                
                Console.WriteLine(n+"\t\t"+p);
            }
            Console.ReadKey();


        }
    }
}

