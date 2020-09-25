# HELLO-WORLD

import java.util.Scanner;

public class EX_4{
    public static void main(String[]args){
        Scanner in = new Scanner(System.in);
        double A,b,h;

        System.out.print("Digite a base:");
        b = in.nextDouble();

        System.out.print("Digite a altura:");
        h = in.nextDouble();

        A = (b*h)/2;

        System.out.println("A area total de um triangulo é="+A);
    }
}
