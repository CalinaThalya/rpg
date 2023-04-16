package rpg;

public class jogo_rpg {
	public class Jogador {
	    private String nome;
	    private int nivel;
	    private int pontosDeVida;
	    private int pontosDeMana;
	    private String classe;

	    public Jogador(String nome, int nivel, int pontosDeVida, int pontosDeMana, String classe) {
	        this.nome = nome;
	        this.nivel = nivel;
	        this.pontosDeVida = pontosDeVida;
	        this.pontosDeMana = pontosDeMana;
	        this.classe = classe;
	    }

	    public String getNome() {
	        return nome;
	    }

	    public void setNome(String nome) {
	        this.nome = nome;
	    }

	    public int getNivel() {
	        return nivel;
	    }

	    public void setNivel(int nivel) {
	        this.nivel = nivel;
	    }

	    public int getPontosDeVida() {
	        return pontosDeVida;
	    }

	    public void setPontosDeVida(int pontosDeVida) {
	        this.pontosDeVida = pontosDeVida;
	    }

	    public int getPontosDeMana() {
	        return pontosDeMana;
	    }

	    public void setPontosDeMana(int pontosDeMana) {
	        this.pontosDeMana = pontosDeMana;
	    }

	    public String getClasse() {
	        return classe;
	    }

	    public void setClasse(String classe) {
	        this.classe = classe;
	    }
	}

}

