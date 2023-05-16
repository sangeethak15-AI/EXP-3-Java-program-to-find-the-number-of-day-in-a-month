# EXP-3-Java-program-to-find-the-number-of-day-in-a-month
## AIM:
To write a java program to find the number of days in a month

## PROCEDURE:
1.Import required packages.

2.Declare main method with the signature "public static void main(String[] args)".

3.Get the month input from user.

4.Use switch method to find the number of days for the given month input.

5.Display the output.
## PROGRAM:
```

import java.util.Scanner;

public class days {
        public static void main(String[] args) {
            Scanner sc=new Scanner(System.in);
            System.out.println("Enter the month number");
            int Month=sc.nextInt();
            switch(Month)
            {
                case 1:
                    System.out.println("31 days");
                    break;
                case 2:
                    System.out.println("28 days");
                    break;
                case 3:
                    System.out.println("31 days");
                    break;
                case 4:
                    System.out.println("30 days");
                    break;
                case 5:
                    System.out.println("31 days");
                    break;
                case 6:
                    System.out.println("30 days");
                    break;
                case 7:
                    System.out.println("31 days");
                    break;
                case 8:
                    System.out.println("31 days");
                    break;
                case 9:
                    System.out.println("30 days");
                    break;
                case 10:
                    System.out.println("31 days");
                    break;
                case 11:
                    System.out.println("30 days");
                    break;
                case 12:
                    System.out.println("31 days");
                    break;
                default:
                    System.out.println("Invalid month number");
                    break;

        }
    }
}
```
## OUTPUT:

![image](https://github.com/sangeethak15-AI/EXP-3-Java-program-to-find-the-number-of-day-in-a-month/assets/93992063/e63a6c0f-0f60-42ce-8dbc-2c859f556ca3)

## RESULT:
To write a java program to find the number of days in a month was successfully done.
