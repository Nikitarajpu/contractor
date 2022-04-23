# contractor
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    class Program 
    {
    	public int num;
    	public string name;
    	public Program(int num1,string name1)
        {
            num=num1;
            name=name1;
           Console.WriteLine("this is constructor");
        }
        public static void Main(string[]args) 
        {
        	Program p1=new Program(100,"Nikita");
        	Console.WriteLine(p1.num);
            Console.WriteLine(p1.name);
            Console.ReadLine();
        }   
    }
}
