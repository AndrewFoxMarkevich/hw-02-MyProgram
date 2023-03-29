# hw-02-MyProgram

using System;
class MyProgram2
{
    static void Main()
    {
        while (true)

        {
            Console.Clear();

            string action;

            Console.WriteLine("Select data type: byte, sbyte, short, ushort, int, uint, long, ulong");
            action = Console.ReadLine();

            switch (action)

            {
                case "byte":

                    Console.WriteLine("Input a number");
                    decimal num = decimal.Parse(Console.ReadLine());

                    if (num <= 0 || num >= 255)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }


                    else
                    {
                        byte total = (byte)num;

                        Console.WriteLine(total);
                    }

                    break;


                case "sbyte":

                    Console.WriteLine("Input a number");
                    decimal num1 = decimal.Parse(Console.ReadLine());

                    if (num1 < -128 || num1 > 127)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        sbyte total1 = (sbyte)num1;

                        Console.WriteLine(total1);
                    }

                    break;

                case "ushort":

                    Console.WriteLine("Input a number");
                    decimal num2 = decimal.Parse(Console.ReadLine());

                    if (num2 < 0 || num2 > 65535)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        ushort total2 = (ushort)num2;

                        Console.WriteLine(total2);
                    }

                    break;

                case "short":

                    Console.WriteLine("Input a number");
                    decimal num3 = decimal.Parse(Console.ReadLine());

                    if (num3 < -32768 || num3 > 32767)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        short total3 = (short)num3;

                        Console.WriteLine(total3);
                    }

                    break;

                case "int":

                    Console.WriteLine("Input a number");
                    decimal num4 = decimal.Parse(Console.ReadLine());

                    if (num4 < -2147483648 || num4 > 2147483647)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        int total4 = (int)num4;

                        Console.WriteLine(total4);
                    }

                    break;

                case "uint":

                    Console.WriteLine("Input a number");
                    decimal num5 = decimal.Parse(Console.ReadLine());

                    if (num5 < 0 || num5 > 4294967295)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        uint total5 = (uint)num5;

                        Console.WriteLine(total5);
                    }

                    break;

                case "long":

                    Console.WriteLine("Input a number");
                    decimal num6 = decimal.Parse(Console.ReadLine());

                    if (num6 < -9223372036854775808 || num6 > 9223372036854775807)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        long total6 = (long)num6;

                        Console.WriteLine(total6);
                    }

                    break;

                case "ulong":

                    Console.WriteLine("Input a number");
                    decimal num7 = decimal.Parse(Console.ReadLine());

                    if (num7 < 0 || num7 > 18446744073709551615)
                    {
                        Console.WriteLine("you have entered an invalid value");
                    }

                    else
                    {
                        ulong total7 = (ulong)num7;

                        Console.WriteLine(total7);
                    }

                    break;
            }

            Console.ReadLine();
        }

    }
}
