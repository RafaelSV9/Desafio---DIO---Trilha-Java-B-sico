# Desafio---DIO---Trilha-Java-B-sico
Desafio - DIO - Trilha Java Básico
Explicação do Código:
Importação do Scanner:

java
Copiar código
import java.util.Scanner;
Importa a classe Scanner para ler a entrada do usuário via terminal.

Classe ContaTerminal:

java
Copiar código
public class ContaTerminal {
Define a classe principal do programa.

Método Main:

java
Copiar código
public static void main(String[] args) {
Define o ponto de entrada do programa.

Criação do Scanner:

java
Copiar código
Scanner scanner = new Scanner(System.in);
Cria um objeto Scanner para ler a entrada do usuário.

Leitura dos Dados:

java
Copiar código
System.out.println("Por favor, digite o número da Agência:");
String agencia = scanner.nextLine();

System.out.println("Por favor, digite o número da Conta:");
int numero = scanner.nextInt();
scanner.nextLine(); // Consumir a nova linha deixada pelo nextInt()

System.out.println("Por favor, digite o seu Nome:");
String nomeCliente = scanner.nextLine();

System.out.println("Por favor, digite o seu Saldo:");
double saldo = scanner.nextDouble();
Solicita e lê os dados da conta bancária do usuário.

Exibição da Mensagem:

java
Copiar código
System.out.println("Olá " + nomeCliente + ", obrigado por criar uma conta em nosso banco, sua agência é " 
                   + agencia + ", conta " + numero + " e seu saldo " + saldo + " já está disponível para saque.");
Exibe a mensagem final com os dados fornecidos pelo usuário.

Fechamento do Scanner:

java
Copiar código
scanner.close();
Fecha o scanner para liberar recursos.

Este código realiza a leitura dos dados via terminal e exibe a mensagem final conforme solicitado.