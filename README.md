## Exercício 1


package revprova01;

import java.util.Scanner;

public class RevProva01 {

    public static void Soma() {
        Scanner a = new Scanner(System.in);

        System.out.println("Quantidade de elementos: ");
        int tamanho = a.nextInt();
        int[] vetor = new int[tamanho];

        System.out.println("Digite os valores:");

        for (int i = 0; i < tamanho; i++) {
            vetor[i] = a.nextInt();
        }

        int soma = 0;
        for (int i = 0; i < tamanho; i++) {
            soma += vetor[i];
        }

        System.out.println("Soma dos elementos: " + soma);
        a.close();
    }

    public static void main(String[] args) {
        Soma();
    }

}
