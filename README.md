# teste_idade
teste em java para classificar idade

package teste_idade

import java.util.Scanner;

public class teste_idade {

	public static void main(String[]args) {
  
		int idade
    
		string nome
		
		Scanner ler = new Scanner(System.in);
		
		System.out.println("Informe seu nome: ");
    
		nome = ler.nextLine();
    
		System.out.println("Informe sua idade: ");
    
		idade = ler.nextInt();
		
		  if (idade >= 0 && idade <= 12) {
      
			  System.out.println(nome+"vvocê é uma criança.");
        
			  }else if (idade >= 13 && idade <= 17) {
        
				  System.out.println(nome+" você é um adolescente.");
          
			  }else if (idade >= 18 && idade <= 59) {
        
				  System.out.println(nome+" você é um adulto.");
          
			  }else if (idade >= 60) {
        
				  System.out.println(nome+" você é um idoso.");
          
			  }else if (idade < 0) {
        
				  System.out.println("idade inválida");
				  
		  
		  }
	}
}
