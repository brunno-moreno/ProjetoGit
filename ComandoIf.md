Comando If em Java -> usado para tomada de decisões que podem variar.
*Lmebre-se do import para usar o Scanner -> import java.util.Scanner;

Vamos ver um exemplo com um sistema de escola que avalia se o aluno está aprovado ou reprovado, considerando a média necessária como 70 pontos:


public class Main {

	public static void main(String[] args) {

//Preparação do código

Scanner ler = new Scanner(System.in);

double nota1, nota2, media;


//Entrada de dados

System.out.println(”Qual a nota 1? “);
nota1 = ler.nextDouble();

System.out.println(”Qual a nota 2? “);
nota2 = ler.nextDouble();


//Processamento

media = (nota1 + nota2) / 2;


//Saída de dados
System.out.println(”A média do aluno é:  “+media);


//Uso do if para decidir se o aluno está aprovado ou reprovado
if(media ≥ 70) {

System.out.println(”O aluno está aprovado!”);

}

else {

System.out.println(”O aluno está reprovado!”);

}

System.out.println(”Até o próximo semestre!”);

    }
}