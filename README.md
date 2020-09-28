# my__coding-
googelist
using System;
// متاسفانه انگیلیسم ضعیفه و خب تازه اول کارم (ریدم) یه تازه کار گوگل لیست 
///و این اولین اپی هست که با اطلاعات النم که تازه شروع کردم نوشتم 
//// زبان سی شارپه پیدا نکردم تو گزینه های سی رو زددم 
```
namespace develop_of_pasword_and_user
{
    class Program
    {
        static void Main(string[] args)
        {
            string username = "ahmadreza";
            int password = 123456;
            int x;
            while (true)
            {
                Console.Write("user==");
                string inputuser = Console.ReadLine();
                if (inputuser.ToLower() != username.ToLower())
                {
                    Console.WriteLine("paswode eshtebal ");
                    continue;
                }
                else
                {
                    Console.WriteLine("password==>");
                    int pasword = Convert.ToInt32(Console.ReadLine());
                    if (password == pasword)
                    {
                        Console.WriteLine("pasword is right ");

                        do
                        {
                            Console.WriteLine("1vorod be safe karbari ");
                            Console.WriteLine("2didane nomre ");
                            Console.WriteLine("virayeshe borofile  ");
                            Console.Write("khoroho ro bede ==>");
                            x = Convert.ToInt32(Console.ReadLine());


                            switch (x)
                            {
                                case 1:
                                    Console.WriteLine("inja safe karbari ast ");
                                    break;
                                case 2:
                                    Console.WriteLine("khob dari nomre hato mibini ");
                                    break;
                                case 3:
                                    Console.WriteLine("virayesh porote ");
                                    break;

                            }
                        } while (!(x == 1 || x != 2 || x != 3));
                        { Console.WriteLine("jozve dastorat nist "); }

                    }
                    else
                    {
                        Console.WriteLine("paswoed is mistake ");
                        continue;
                    }

                }
                Console.ReadKey();
            }

        }
    }
}
```
