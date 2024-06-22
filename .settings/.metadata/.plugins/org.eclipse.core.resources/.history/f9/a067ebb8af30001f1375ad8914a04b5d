public class Main {

    public static void main(String[] args) {
        Cliente kaique = new Cliente();
        kaique.setNome("Kaique");

        Conta cc = new ContaCorrente(kaique);
        cc.depositar(7000);

        Conta cp = new ContaPoupanca(kaique);

        Cliente joao = new Cliente();
        joao.setNome("João");

        Conta cc1 = new ContaCorrente(joao);
        cc1.depositar(3000);

        Conta cp1 = new ContaPoupanca(joao);

        cc.transferir(3000, cp);
        cc1.transferir(1000, cp1);

        cc.imprimirExtrato();
        cp.imprimirExtrato();
        cc1.imprimirExtrato();
        cp1.imprimirExtrato();
    }
}
