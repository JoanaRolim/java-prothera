# Projeto Java - Gestão de Funcionários

Este projeto é uma aplicação Java que gerencia informações de funcionários de uma empresa, realizando diversas operações conforme especificado nos requisitos.

## Estrutura do Projeto

Industria/

└── src/

├── Pessoa.java

├── Funcionario.java

└── App.java

## Requisitos do Projeto

1. **Classe Pessoa**:

   - Atributos: `nome` (String) e `dataNascimento` (LocalDate).
2. **Classe Funcionario**:

   - Extende a classe `Pessoa`.
   - Atributos: `salario` (BigDecimal) e `funcao` (String).
3. **Classe Principal**:

   - Executa as seguintes ações:
     1. Inserir todos os funcionários conforme a tabela fornecida.
     2. Remover o funcionário "João" da lista.
     3. Imprimir todos os funcionários com todas suas informações:
        - Data no formato `dd/MM/yyyy`.
        - Salário formatado com separador de milhar como ponto e decimal como vírgula.
     4. Aplicar um aumento de 10% no salário de todos os funcionários.
     5. Agrupar os funcionários por função em um mapa (Map).
     6. Imprimir os funcionários agrupados por função.
     7. Imprimir os funcionários que fazem aniversário nos meses de outubro e dezembro.
     8. Imprimir o funcionário com a maior idade (nome e idade).
     9. Imprimir a lista de funcionários em ordem alfabética.
     10. Imprimir o total dos salários dos funcionários.
     11. Imprimir quantos salários mínimos cada funcionário ganha, considerando que o salário mínimo é R$ 1212,00.

## Instruções para Compilação e Execução

### Pré-requisitos

- Java Development Kit (JDK) instalado.

### Passo a Passo

1. **Clonar o Repositório**

   ```sh
   git clone https://github.com/JoanaRolim/java-prothera.git
   cd Industria
   ```

   **2. Abrir o Projeto no Visual Studio Code**

* Abra o Visual Studio Code.
* Selecione  **`File > Open Folder` e escolha a pasta** Industria.
* **Compilar os Arquivos Java**

  * Abra o terminal no VS Code (`Terminal > New Terminal`).
  * Navegue até a pasta  `src` do projeto:

    `cd src`

    * Compile os arquivos Java:

    javac *.java

### Executar o Programa

* No terminal, execute a classe  `App`:

  java App

### Saída Esperada

O programa deve exibir informações dos funcionários conforme especificado nos requisitos, incluindo a lista de funcionários, agrupamentos, aniversários em outubro e dezembro, funcionário mais velho, ordenação alfabética, total de salários, e salários mínimos por funcionário.

<img width="761" alt="Captura de Tela 2024-06-13 às 17 55 34" src="https://github.com/JoanaRolim/java-prothera/assets/62566283/96aa3a89-e13d-4da4-9560-aba8f6e3a4dc">
<img width="976" alt="Captura de Tela 2024-06-13 às 17 55 43" src="https://github.com/JoanaRolim/java-prothera/assets/62566283/7b20c764-1b25-452f-936a-01cf65ed2011">


