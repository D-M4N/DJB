# DJB

{ MY TAG }
 string tag = "$ 😎 D-M4N 😎 $";
            Console.ForegroundColor = ConsoleColor.Cyan;
            Console.WriteLine(String.Format("{0," + ((Console.WindowWidth / 2) + (tag.Length / 2)) + "}", tag));
            
            Console.Read();
