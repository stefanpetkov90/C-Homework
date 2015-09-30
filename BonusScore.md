using System;

class BonusScore
{
    static void Main()
    {
        Console.Write("Please enter a score from '1' to '9': ");
        string bonusScore = (Console.ReadLine());

        switch (bonusScore)
        {
            case "1": Console.WriteLine("10");
                break;
            case "2": Console.WriteLine("20");
                break;
            case "3": Console.WriteLine("30");
                break;
            case "4": Console.WriteLine("400");
                break;
            case "5": Console.WriteLine("500");
                break;
            case "6": Console.WriteLine("600");
                break;
            case "7": Console.WriteLine("7000");
                break;
            case "8": Console.WriteLine("8000");
                break;
            case "9": Console.WriteLine("9000");
                break;

            default: Console.WriteLine("invalid score");
                break;
        }
    }
}
