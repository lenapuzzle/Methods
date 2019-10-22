# Methods

using System;

namespace methods
{
    class Program
    {
        static void Main(string[] args)
        {
            SayHi("Lena", 35);
            SayHi("Jing", 25);
            SayHi("Ben", 26);
             
            Console.ReadLine();
        }

        static void SayHi(string name, int age) // New method "Say Hi", which is called above in Main method
        {
            Console.WriteLine("Hello " + name + "!" + " You are " + age);
        }
    }
}
