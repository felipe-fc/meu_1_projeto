# meu_1_projeto
Uma classe java que chama um método de outra classe java publica.
## Resumo:
O objetivo desse projeto é fazer a ligação entre duas classes javas que estão no mesmo diretório sendo que a principal chama um método da classe secundária para escrever uma mensagem na tela.É o método da classe secundária que escreve a mensagem
para melhor compreensão do mecanismo escolhemos compilar e construir esse projeto ultilizando apenas a linha de comando e o compilador,e claro a maquina virtual java para executar a classe que será  o produto final desta compilação.
Ou seja,um script fará o papel de uma ferramenta de construção tal qual uma interface IDE que coordena todos os arquivos fontes de um projeto.

###MINHA CLASSE...

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package minhaclasse;

/**
 *
 * @author Felipe
 
 */
public class MinhaClasse {

  
   

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic her 
        Ssi Variavel = new Ssi();
        Variavel.minhaclasse();
    }


}

###SSI....


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package minhaclasse;

/**
 *
 * @author Felipe
 
 */
public class Ssi {

    public Ssi() {
    }

    
    
    public void minhaclasse(){
         System.out.println("Olá, eu sou uma classe Ssi");
    }
}
