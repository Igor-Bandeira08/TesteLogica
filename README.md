## Exercício 2 

package revprova02;

import java.util.Scanner;

public class RevProva02 {

    public static void Maior() {
        Scanner a = new Scanner(System.in);
        System.out.println("quantidade de elementos: ");
        int n = a.nextInt();
        int[] vetor = new int[n];
        int n1 = Integer.MIN_VALUE;
        System.out.println("digite os elementos do vetor: ");
        for (int i = 0; i < vetor.length; i++) {
            vetor[i] = a.nextInt();
            if (vetor[i] > n1) {
                n1 = vetor[i];
            }
        }
            System.out.println("elemento maior: " + n1);
            

        
    }
    public static void main(String[] args) {
        Maior();
    }
    
}
