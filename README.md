# operadores-aritmeticos
desenvolvimento de controle de gasto no mes 


//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {

        double pao = 9.50;
        double queijo = 7.00;
        double acucar = 1.00;
        double desconto = 5.00;
        int TotalDiasDoMes = 30;

        double ValorTotal = pao + queijo + acucar;
        double ValorTotalComDesconto = ValorTotal - desconto;
        double ValorTotalDivido = ValorTotalComDesconto / 2;
        double ValorTotalMensal = ValorTotalComDesconto * TotalDiasDoMes;

        System.out.println( " valor total = R$ " + ValorTotalMensal);
    }
}
