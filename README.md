public class Eletronico extends Produtos {
    protected int GarantiaMes;

    public Eletronico(String nome, double preco, int estoque, int GarantiaMes) {
        super(nome, preco, estoque);
        this.GarantiaMes = GarantiaMes;

    }
    public int getGarantiaMes() {
        return GarantiaMes;
    }

    public void setGarantiaMes(int garantiaMes) {
        GarantiaMes = garantiaMes;
    }


    @Override
    public void exibir() {
        System.out.println("=== ELETRÔNICO ===");
        System.out.println("Nome: " + getNome());
        System.out.println("Preço: R$ " + getPreco());
        System.out.println("Estoque: " + getEstoque());
        System.out.println("Garantia: " + GarantiaMes + " meses");
        System.out.println();
        System.out.println("honorario");
        System.out.println("estoque " + estoque);

        
    }
}
