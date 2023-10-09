# back001
import * as leitor from "readline-sync"


function main() { 
	// exercicio 2 
	let nome = leitor.question("insira i nome do item: ")
	let valor = leitor.questionFloat("Insira o valor do item: ")
	let desconto = leitor.questionionInt("Insira o desconto: ")
	let valorDesconto = (( 100-desconto) /100)
	console.log("O nome do item é : $(nome} ");
	console.log("O valor do item é: $(valor} ");
	console.log(" O valor com desconto é: $(valor*valordesconto) ");

}
    
main()
  // exercicio 3 
  import * as leitor from "readline-sync"

  funtcion main() {}
	let adulto = leitor. questionInt("Insira a quantidade de adultos que existem na festa: ")
	let criança = leitor.questioinInt("Insira a quabtidade de criança que existe na festa: ")
	console.log("The total party size is: ", calcula (adulto, criança))

  {
	function calcula(adulta , criança): Number {
     return adulto  + criança 
	}
  }


  // exercicio 4 
  function main() {
	// bloco das variaveis
	let salarioBruto: Number 
	let salarioINSS: Number 
	let salarioLiquido: Number 
	   
	 salarioBruto = leitor.question(" Insira o valor do seu salario Bruto");

	 salarioINSS = INSS(salarioBruto)
	 salarioLiquido = IRRF(salarioINSS) 
         
	 //Funçao para o calculo  de INSS com base no salario bruto 


  }

  // exercicio 5 
  import * as leitor from "readline - sync"  
  
  
     function main () {
		let Number1 = Number
		let Number2 = Number
		let Number3  = Number
		
		Number1 = leitor.question("insira o primeiro valor");
		Number2 = leitor.question("insira o segundo valor");
		Number3 = leitor.question("insira o terceito valor");

		
	 }
