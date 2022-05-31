# Desafio-Dio-RPG-POO
Abstraindo um Jogo de RPG Usando Orientação a Objetos com C#

Class Ponto Rpg {
	  // pontos cartesianos (representa o indice da matriz/mapa)
	  int x, y;
	

	  // Construtor padrão
	  PontoRpg(this.x, this.y);
	

	  // Construtor nomeado (inicia zerado)
	  PontoRpg.zero() {
	    this.x = this.y = 0;
	  }
	

	  // Sobrescrita do método toString da classe Object
	  @override
	  String toString() {
	    return "$x, $y";
	  }
	}
