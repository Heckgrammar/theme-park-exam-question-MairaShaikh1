using System;

public class Program
{
    public static void Main(string[] args)
    {
        int payment = 0;
        Console.WriteLine("enter how many people are going");
        
        string input = Console.ReadLine();
        
        if (int.TryParse(input, out int people))
        {
            if (people < 6)
            {
                payment = people * 15;
                Console.WriteLine($"your payment is £{payment}");
            }
            else
            {
                payment = (people * 15) - 5;
                Console.WriteLine($"your payment is £{payment}");
            }
        }
        else
        {
            Console.WriteLine("Invalid input. Please enter a valid number.");
        }
    }
}
<img width="640" height="1136" alt="IMG_3206" src="https://github.com/user-attachments/assets/b81ed490-6ef5-4fd9-941b-6898079f707e" />
<img width="640" height="1136" alt="IMG_3207" src="https://github.com/user-attachments/assets/d0ee7ada-eaa3-4e82-b680-a2635c1a31a7" />
<img width="640" height="1136" alt="IMG_3208" src="https://github.com/user-attachments/assets/10a834dc-375d-4865-94a0-b847cd9845ef" />

