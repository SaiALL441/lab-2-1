using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace lab_2_1
{
    public delegate int AddDelegate(int a, int b, int c);
    class Program
    {
        
        static void Main(string[] args)
        {
            AddDelegate aD = new AddDelegate( delegate (int x, int y, int z)
            {
                int res = (x + y+x)/2;
                return res;
            });
            int sum = aD(6, 2, 10);
            Console.WriteLine(sum);
            Console.ReadKey();

        }
    }
}


