## Exercício 3 

package revprova03;

import java.util.Scanner;

public class RevProva03 {
  public static void main(String[] args) {
        Media();
    }

    public static void Media() {
        Scanner l = new Scanner(System.in);
        System.out.println("Digite a quantidade de elementos: ");
        int t = l.nextInt();

        System.out.println("Elementos = ");
        double[] v1 = new double[t];
        
        double soma = 0;
        double media = 0;
        for (int i = 0; i < v1.length; i++) {
            v1[i] = l.nextDouble();
            soma += v1[i];
            media = soma / t;
        }
        System.out.println("A media é = " + media );
    }

}

