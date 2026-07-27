import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        double v1, v2, resultado;
        int soma;
        char continuar;

        System.out.print("Digite o Primeiro valor: ");
        resultado = scanner.nextDouble();

        do {
            System.out.println("1-Soma");
            System.out.println("2-Subtracao");
            System.out.println("3-Multiplicacao");
            System.out.println("4-Divisao");
            System.out.print("Escolha operador: ");
            soma = scanner.nextInt();

            System.out.print("Digite o Segundo valor: ");
            v2 = scanner.nextDouble();


            switch (soma) {
                case 1:
                    resultado = resultado + v2;
                    System.out.println("Resultado: " + resultado);
                    break;
                case 2:
                    resultado = resultado - v2;
                    System.out.println("Resultado: " + resultado);
                    break;
                case 3:
                    resultado = resultado * v2;
                    System.out.println("Resultado: " + resultado);
                    break;
                case 4:
                    if (v2 == 0){
                        System.out.println("Erro: divisão por zero.");
                    } else {
                        resultado = resultado / v2;
                        System.out.println("Resultado: " + resultado);
                    }
                    break;
                    default:
                        System.out.println("Opção inválida.");
                    }
                    System.out.println("Resultado Final:  " + resultado);

                    System.out.println("Deseja continuar com o ultimo resultado? (s/n) ");
                    continuar = scanner.next().charAt(0);

            } while (continuar == 's' || continuar == 'S');

            System.out.println("Resultado Final: . " + resultado);
            scanner.close();
        }
}
