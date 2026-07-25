import java.util.Scanner;

public class Main{
public static void main(String[] args){

    Scanner scanner = new Scanner (System.in);

    double v1, v2, resultado;
    int soma;

    System.out.println("Digite o Primeiro valor: ");
    v1  = scanner.nextDouble();
        System.out.println("Digite o Segundo valor: ");
        v2 = scanner.nextDouble();
        System.out.println("Qual o operador ?");
        System.out.println("1-soma");
        System.out.println("2-Subtracao");
        System.out.println("3-Multiplicacao");
        System.out.println("4-Divisao");
        soma = scanner.nextInt();

        switch (soma){
            case 1:
                resultado = v1+v2;
                System.out.println(resultado);
                break;
            case 2:
                resultado = v1-v2;
                System.out.println(resultado);
                break;
            case 3:
                resultado = v1*v2;
                System.out.println(resultado);
                break;
            case 4:
                resultado = v1/v2;
                System.out.println(resultado);
                break;
        }
    }
}