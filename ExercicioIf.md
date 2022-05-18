    import java.util.Locale;
    import java.util.Scanner;

     /*Leia 2 valores com uma casa decimal (x e y), que devem representar as coordenadas
      *de um ponto em um plano. A seguir, determine qual o quadrante ao qual pertence o
      *ponto, ou se está sobre um dos eixos cartesianos ou na origem (x = y = 0).
      *Se o ponto estiver na origem, escreva a mensagem “Origem”.
      */

    public class Questao4 {

	public static void main(String[] args) {
    
    //Preparação
		Scanner scanner = new Scanner(System.in);
		double x, y;

    //Entrada
		System.out.print("Digite o valor de x: ");
		x = scanner.nextDouble();

		System.out.print("Digite o valor de y: ");
		y = scanner.nextDouble();

    //Comando If
		if ((x > 0.0) && (y > (0.0)) {
			System.out.println("Q1");
		}

		else if ((x < 0.0) && (y > 0.0)) {
			System.out.println("Q2");
		}

		else if ((x < 0.0) && (y < 0.0)) {
			System.out.println("Q3");
		}

		else if ((x > 0.0) && (y < 0.0)) {
			System.out.println("Q4");
		}

		else {
			System.out.println("Origem");
		}

	 }

     }
