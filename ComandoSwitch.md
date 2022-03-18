/*import para utilizar a GUI*/ ->
  import javax.swing.JOptionPane;


	public static void main(String[] args) {
		
        /*Praticando o comando switch com utilização de GUI em java*/
        /*Criando um pequeno sistema de progresso de meses em 1 ano.*/
		

        //Início do código5

		JOptionPane.showMessageDialog(null, "Progresso de um período de 1 ano");
		String mes = JOptionPane.showInputDialog(null, "Em qual mês estamos?");
		
		switch(mes) {
     	case "Janeiro": JOptionPane.showMessageDialog(null, "Estamos no 1° mês do ano!");
		break;
		case "Fevereiro": JOptionPane.showMessageDialog(null, "Opa, já Estamos no 2° mês do ano!");
		break;
		case "Março": JOptionPane.showMessageDialog(null, "Chegamos no 3° mês do ano!");
		break;
		case "Abril": JOptionPane.showMessageDialog(null, "Força! Estamos no 4° mês do ano!");
		break;
		case "Maio": JOptionPane.showMessageDialog(null, "Você piscou e já estamos no 5° mês do ano!");
		break;
		case "Junho": JOptionPane.showMessageDialog(null, "Olha até onde já chegamos! Estamos no 6° mês do ano!");
		break;
		case "Julho": JOptionPane.showMessageDialog(null, "A primeira metade já foi! Estamos no 7° mês do ano!");
		break;
		case "Agosto": JOptionPane.showMessageDialog(null, "Quase lá! 8° mês do ano!");
		break;
		case "Setembro": JOptionPane.showMessageDialog(null, "Perto do fim! 9° mês do ano!");
		break;
		case "Outubro": JOptionPane.showMessageDialog(null, "Mais perto do que nunca! Chegamos ao 10° mês do ano!");
		break;
		case "Novembro": JOptionPane.showMessageDialog(null, "Rufem os tambores... Estamos no 11° mês do ano!");
		break;
		case "Dezembro": JOptionPane.showMessageDialog(null, "Parabéns, você chegou ao 12° e último mês do ano!");
		break;
		default: JOptionPane.showMessageDialog(null, "Desculpe, isso não é um mês do ano!");
		}
	      
           }	
	 
	    }
