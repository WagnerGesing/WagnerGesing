class Conta {
    double salario;
    // ... outros atributos ...

    void saca(double quantidade) {
        double novoSaldo = this.saldo - quantidade; 
        this.saldo = novoSaldo;
    }
}
