import java.util.Scanner;

public class Khan{
    public static void main(String []args){
        Scanner src=new Scanner(System.in);
        System.out.println("please enter your number: ");
        int num1=src.nextInt();
        System.out.println("please enter your second number: ");
        int num2=src.nextInt();
        int sum =num1+num2;
        System.out.println(sum);
    }
}
