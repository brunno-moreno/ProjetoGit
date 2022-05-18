import java.util.Scanner;

public class Main {

	/*
	 * Desenvolver um programa que pergunte o peso de uma pessoa e também
	 * pergunte o código do planeta no qual ela gostaria de obter como resposta o
	 * valor do seu peso neste referido planeta. As informações da tabela abaixo
	 * (somente as colunas Código e Planeta) devem aparecer como menu de escolha ao
	 * usuário:
	 * 
	 * Código Planeta Gravidade Relativa 1 Mercúrio 0,37 2 Vênus 0,88 3 Marte 0,38 4
	 * Júpiter 2,64 5 Saturno 1,15 6 Urano 1,17
	 * 
	 * Para calcular o peso no planeta escolhido, utilize a fórmula pesoNoPlaneta =
	 * (pesoNaTerra/10) * gravidadeRelativa. Caso o usuário digite um código que não
	 * esteja na tabela, informar que o código inserido está errado.
	 */

	public static void main(String[] args) {		

		//Preparação
		Scanner scanner = new Scanner(System.in);
		double peso = 0.0;
		int codigo = 0;
		
		//Entrada
		System.out.println("---Descubra seu peso em outros planetas---");
		System.out.print("\nDigite seu peso em kg: ");
		peso = scanner.nextDouble();
		
		
		//Tabela
		System.out.println("\n\nAgora observe a tabela abaixo e em seguida escolha um código referente ao planeta desejado.");
		System.out.println("\nCódigo	Planeta	    \r\n"
				+ "  1	Mercúrio       \r\n"
				+ "  2	Vênus	       \r\n"
				+ "  3	Marte	       \r\n"
				+ "  4	Júpiter	       \r\n"
				+ "  5	Saturno	      \r\n"
				+ "  6	Urano	       \r\n");
		
		System.out.print("Digite o código: ");
		codigo = scanner.nextInt();
		
		//Comando Switch
		switch(codigo) {
		case 1: System.out.println("Você teria "+(peso/10) * 0.37+ "kg em Mercúrio");
		break;
		case 2: System.out.println("Você teria "+(peso/10) * 0.88+ "kg em Vênus");
		break;
		case 3: System.out.println("Você teria "+(peso/10) * 0.38+ "kg em Marte");
		break;
		case 4: System.out.println("Você teria "+(peso/10) * 2.64+ "kg em Júpiter");
		break;
		case 5: System.out.println("Você teria "+(peso/10) * 1.15+ "kg em Saturno");
		break;
		case 6: System.out.println("Você teria "+(peso/10) * 1.17+ "kg em Urano");
		break;
		default: System.out.println("Código inválido");
		}
		
	}

}
