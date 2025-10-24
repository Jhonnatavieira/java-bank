# 💳 Java Bank

Sistema bancário simples desenvolvido em Java, utilizando conceitos de Programação Orientada a Objetos (POO). Permite criar contas, realizar transações financeiras e consultar histórico de movimentações via chave Pix.

---

## 🚀 Funcionalidades

- Criar contas com chave Pix
- Realizar depósitos e saques
- Consultar saldo da conta
- Gerar extrato de transações
- Histórico agrupado por data/hora
- Validação de saldo e exceções personalizadas

---

## 🛠 Tecnologias utilizadas

- Java 21
- Gradle
- IntelliJ IDEA
- Padrões de projeto (POO)
- Coleções e Streams (Java Collections API)

---

## 📂 Estrutura do projeto

```text
java-bank/
├── src/
│   └── main/
│       └── java/
│           └── br/com/dio/
│               ├── model/       # Classes de domínio (AccountWallet, MoneyAudit)
│               ├── repository/  # Repositório de contas
│               ├── service/     # Lógica de negócio
│               └── Main.java    # Ponto de entrada da aplicação
├── build.gradle.kts
└── README.md
```

---


---

## 📦 Como executar
Para obter uma cópia local deste projeto e começar a trabalhar nele, siga estes passos:

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/Jhonnatavieira/java-bank.git](https://github.com/Jhonnatavieira/java-bank.git)
    ```

2.  Navegue até a pasta do projeto:
    ```bash
    cd java-bank
    ```

3.  Abra o projeto no IntelliJ IDEA e aguarde o Gradle sincronizar as dependências.

4.  Execute a classe `Main.java` para iniciar a aplicação no console.

## 💡 Exemplos de uso

Ao executar a aplicação, as opções aparecerão no console. Comece pela opção:

**`1 - Criar conta`**

Em seguida, para testar outras funcionalidades:

* **Para consultar/movimentar:** Informe a chave pix da conta (ex: `123`).
* **Para depositar:** Informe o valor em centavos (ex: `10000` para R$ 100,00).


    
