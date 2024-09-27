Este é um sistema onde podemos cadastrar e gerenciar e atualizar dados de pessoas.
Para usa-lo basta usar o comando "pessoa pessoa1 = new pessoa()" na classe main e botar as informações da pessoa Nome, idade e cpf.
Em seguida ultize os seguintes comandos para cadastrar a pessoa1
     
     GerenciadorDePessoas gerenciador = new GerenciadorDePessoas();
      gerenciador.cadastrarPessoa1(pessoa1);
      gerenciador.exibirPessoa1;

Para atualizar os dados dessa pessoa segue os seguintes comandos;
    
    pessoa1.setidade(9);
    gerenciador.atualizarPessoa1(pessoa1);
    gerenciador.exibirPessoa1();
    
E da mesma forma pode ser feito para a pessoa 2.


Aqui está um exemplo do codigo em pratica 

public class Main {
   public static void main(String[] args) {
        pessoa pessoa1 = new pessoa("Arthur", 14, "3883298328");
        pessoa pessoa2 = new pessoa("Gabriel", 18, "7171727172782");

    GerenciadorDePessoas gerenciador = new GerenciadorDePessoas();

    gerenciador.cadastrarPessoa1(pessoa1);
    gerenciador.cadastrarPessoa2(pessoa2);

    gerenciador.exibirPessoa1();
    gerenciador.exibirPessoa2();

    pessoa1.setidade(9);
    gerenciador.atualizarPessoa1(pessoa1);
    gerenciador.exibirPessoa1();
    
   }
}
