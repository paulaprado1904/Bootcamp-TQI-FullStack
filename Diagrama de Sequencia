´´´mermaid
%%{init: {'theme':'default'}}%%
sequenceDiagram
    participant Cliente
    participant Banco
    participant PessoaFisica
    participant ContaComum
    participant Historico

    Cliente->>Banco: Solicita abertura de conta
    Banco->>PessoaFisica: Coleta dados
    PessoaFisica-->>Banco: Valida CPF
    Banco->>ContaComum: Se válido, cria conta
    ContaComum-->>Banco: Retorna número da conta
    Banco->>Historico: Registra no histórico
    Historico-->>Banco: Retorna confirmação
    Banco-->>Cliente: Retorna confirmação
´´´
