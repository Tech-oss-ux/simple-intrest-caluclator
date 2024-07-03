# simple-intrest-caluclator
import java.util.Scanner;

public class loops {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("Enter principal amount : ");
        int p = s.nextInt();
        System.out.println("enter time : ");
        int t = s.nextInt();
        System.out.println("enter rate");
        int r = s.nextInt();
        int i = p * r * t / 100;
        System.out.println("The simple intrest :- " +i);

        
        }

    }
