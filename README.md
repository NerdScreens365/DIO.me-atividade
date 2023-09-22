# DIO.me-atividade

aspecto VerificacaoSaldoAspecto {

    antes(): saqueEmContas() {
        se (saldoInsuficiente()) {
            gerarLogDeErro("Saldo insuficiente para o saque.");
        }
    }
    boolean saldoInsuficiente() {
        // Lógica para verificar o saldo da conta e retornar verdadeiro se for insuficiente, falso caso contrário
    }
    gerarLogDeErro(String mensagem) {
        // Lógica para gerar um log de erro com a mensagem fornecida
    }
}
