# Dados mapeados
Achei interessante adicionar mais detalhes ao armazenar um bem ou uma renda de uma pessoa, afinal, serão também com esses dados que o  score será calculado.

DadosScore {

	String id;
	int idade;
	List<Bem> bens {
		String tipo;
		double valor;
		 boolean quitado;
	  };
	long cpf;
	Endereco endereco;
	List<FonteRenda> rendas{
	    boolean formal;
	    long documentoEmpregador;
	    double salario;
	    String inicio;
	  }
}
