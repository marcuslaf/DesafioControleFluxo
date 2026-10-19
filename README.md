# Desafio Controle de Fluxo

**Desafio prático de Java sobre controle de fluxo com exceções personalizadas: valide os parâmetros de entrada, trate erros de negócio com `try/catch` e impeça a execução de um laço com valores inválidos.**

**Java flow-control challenge with custom exceptions: validate input parameters, handle business errors with `try/catch`, and prevent loop execution with invalid values.**

---

## Tecnologias | Technologies

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)

## Sobre o Desafio | About the Challenge

**O programa lê dois parâmetros inteiros pelo console. Se o primeiro parâmetro for maior que o segundo, uma exceção personalizada (`ParametrosInvalidosException`) é lançada e uma mensagem de erro de negócio é exibida. Caso contrário, o laço imprime a contagem de 1 até a diferença entre os parâmetros.**

**The program reads two integer parameters from the console. If the first parameter is greater than the second, a custom exception (`ParametrosInvalidosException`) is thrown and a business error message is displayed. Otherwise, the loop prints the count from 1 to the difference between the parameters.**

## Funcionalidades | Features

- Validação de parâmetros com exceção personalizada | Parameter validation with custom exception
- Tratamento de erros de negócio com `try/catch` | Business error handling with `try/catch`
- Leitura de entrada via `Scanner` | Input reading via `Scanner`
- Contagem e impressão em laço `for` | Counting and printing with a `for` loop

## Estrutura | Structure

```
DesafioControleFluxo/
├── src/
│   ├── Contador.java                      # Classe principal com main / Main class with main
│   └── ParametrosInvalidosException.java  # Exceção personalizada / Custom exception
└── README.md
```

---

## Como Usar | How to Use

```bash
# Clonar o repositório | Clone the repository
git clone https://github.com/marcuslaf/DesafioControleFluxo.git
cd DesafioControleFluxo

# Compilar | Compile
javac -d out src/*.java

# Executar | Run
java -cp out Contador
```

### Exemplo | Example

```text
Digite o primeiro parâmetro
2
Digite o segundo parâmetro
6
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
```

### Caso de erro | Error case

```text
Digite o primeiro parâmetro
7
Digite o segundo parâmetro
3
O segundo parâmetro deve ser maior que o primeiro
```

## Autor | Author

**Marcus Lafaiete** — [@marcuslaf](https://github.com/marcuslaf)

---

<div align="center">
  <img src="https://img.shields.io/badge/status-conclu%C3%ADdo-success?style=for-the-badge"/>
</div>
