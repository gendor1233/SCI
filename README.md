# SCI
My_Proj

              // checking if a number is divisible by 2,4 and 8

using System

namespace Check
{
    class Program
    {
        static void Main(string[] args)
        {
            string userno;
            int user;
            Console.WriteLine("Enter the number");
            userno = Console.ReadLine();
            user = Convert.ToInt32(userno);
          
           
            if (user >= 0) {

                if(user == 0)
                {
                    Console.WriteLine("You just inputed zero");
                    Console.ReadLine();


                }
                else if (user % 2 == 0 && user % 4 == 0 && user % 8 == 0)
                {

                    Console.WriteLine("Its divisible");
                    Console.ReadLine();

                }
                else {

                    Console.WriteLine("Its not divisible");
                    Console.ReadLine();
                }
            
            }
            else {
            Console.WriteLine("Its less than zero");
                    Console.ReadLine();
            }
            Console.ReadLine();
            Console.ReadLine();
            Console.ReadLine();
            Console.WriteLine("press enter to exit");
            Console.ReadLine();
            Console.ReadLine();
               
            }  
            
            
            
// Creating an Instance of a Class
using right;

namespace ClassProg
{
    class Program
    {
        static void Main(string[] args)
        {
            printer myprinter = new printer();
            myprinter.Write("hello");
            

        }
    }



}
    namespace right
{
    class printer
    {
        public void Write(string mystring)
        {
        Console.WriteLine("===== {0} =====",mystring); 
        Console.ReadLine();
        } 
 
    }
}

//USE OF CONDITIONAL STATEMENT (Goal1-180516)

namespace ConditionalStatement
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Would you prefer what is behind door number 1, 2, 3,4, 5 ");
            string exValue = Console.ReadLine();
            if (exValue == "1")
            {
                Console.WriteLine("You won a new Samsung 40 inch plasma tv");
                Console.ReadLine();
            }
            else if (exValue == "2")
            {
                Console.WriteLine("You won a new Haier Thermocool freezer");
                Console.ReadLine();
            }
            else if (exValue == "3")
            {
                Console.WriteLine("You won a new car");
                Console.ReadLine();

            }
            else if (exValue == "4")
            {
                Console.WriteLine("");
                Console.ReadLine();
            }
            else if (exValue == "5")
            {
                Console.WriteLine("You won a catoon of noodles");
                Console.ReadLine();
            }
            else {
                Console.WriteLine("sorry, we didn't understand.  You lose!!!!!!!!");
                Console.ReadLine();
                

  

                
