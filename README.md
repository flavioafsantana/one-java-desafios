# 🔢 ONE - Oracle Next Education | Variáveis e Tipos de Dados em Java

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)](https://www.jetbrains.com/idea/)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 📖 Sobre o Projeto

Este repositório contém **6 exercícios práticos** sobre **variáveis e tipos de dados em Java** desenvolvidos durante o programa **ONE - Oracle Next Education** em parceria com a **Alura**. Os exercícios são focados em conceitos fundamentais da linguagem, incluindo:

- 🔢 Tipos primitivos (int, double, char)
- 📝 Tipos de referência (String)
- 🔄 Conversão de tipos (Casting)
- 🧮 Operações aritméticas
- ➕ Concatenação de strings
- 💾 Declaração e inicialização de variáveis

---

## 🎯 Exercícios Realizados

### 📊 **Exercício 1: Cálculo de Média**
**Objetivo:** Calcular a média de duas notas decimais e exibir o resultado

```java
public class Media {
    public static void main(String[] args) {
        double nota1 = 8.0;
        double nota2 = 7.0;
        double media = (nota1 + nota2) / 2;
        System.out.println("Media = " + media);
    }
}
```

**Saída:**
```
Media = 7.5
```

**Conceitos aplicados:**
- Declaração de variáveis do tipo `double`
- Operações aritméticas (soma e divisão)
- Concatenação de strings com operador `+`

---

### 🔄 **Exercício 2: Casting de Tipos**
**Objetivo:** Converter (casting) uma variável double para int

```java
public class Casting {
    public static void main(String[] args) {
        double numeroDouble = 8.0;
        int numeroInt = 7;
        numeroInt = (int) numeroDouble;
        System.out.println("Casting de double para int: " + numeroInt);
    }
}
```

**Saída:**
```
Casting de double para int: 8
```

**Conceitos aplicados:**
- Declaração de variáveis `double` e `int`
- Casting explícito com `(int)`
- Perda de precisão na conversão (parte decimal é descartada)

---

### 🔤 **Exercício 3: Concatenação de Char e String**
**Objetivo:** Declarar variáveis char e String e concatená-las em uma mensagem

```java
public class Main {
    public static void main(String[] args) {
        char letra = 'J';
        String palavra = "ava";
        String mensagem = "Juntando letra " + letra + " a palavra " + palavra + ". Formamos a palavra: " + letra + palavra;
        System.out.println(mensagem);
    }
}
```

**Saída:**
```
Juntando letra J a palavra ava. Formamos a palavra: Java
```

**Conceitos aplicados:**
- Declaração de variável do tipo `char` (usa aspas simples)
- Declaração de variável do tipo `String` (usa aspas duplas)
- Concatenação múltipla com operador `+`

---

### 🛒 **Exercício 4: Cálculo de Valor Total**
**Objetivo:** Calcular o valor total multiplicando preço pela quantidade

```java
public class Main {
    public static void main(String[] args) {
        double precoProduto = 29.90;
        int quantidade = 10;
        double valorTotal = precoProduto * quantidade;
        System.out.println("O valor total é: " + valorTotal);
    }
}
```

**Saída:**
```
O valor total é: 299.0
```

**Conceitos aplicados:**
- Operação de multiplicação entre `double` e `int`
- Promoção automática de tipo (int → double)
- Cálculo de valores monetários

---

### 💵 **Exercício 5: Conversão de Dólar para Real**
**Objetivo:** Converter um valor em dólares para reais usando cotação fixa

```java
public class Main {
    public static void main(String[] args) {
        double valorEmDolares = 25;
        double valorDolar = 4.94;
        double valorEmReal = valorEmDolares * valorDolar;
        System.out.println("O valor em reais é: " + valorEmReal);
    }
}
```

**Saída:**
```
O valor em reais é: 123.5
```

**Conceitos aplicados:**
- Operações com números decimais
- Conversão de moedas
- Multiplicação de valores `double`

---

### 💰 **Exercício 6: Cálculo de Desconto**
**Objetivo:** Calcular e aplicar desconto percentual ao preço original

```java
public class Main {
    public static void main(String[] args){
        double precoOriginal = 150.75;
        double percentualDesconto = 20.0;
        double valorDoDesconto = (percentualDesconto / 100) * precoOriginal;
        double precoComDesconto = precoOriginal - valorDoDesconto;
        System.out.println("Preço original: " + precoOriginal);
        System.out.println("Valor do desconto: " + valorDoDesconto);
        System.out.println("Preço com desconto: " + precoComDesconto);
    }
}
```

**Saída:**
```
Preço original: 150.75
Valor do desconto: 30.15
Preço com desconto: 120.6
```

**Conceitos aplicados:**
- Cálculo de porcentagem
- Múltiplas operações aritméticas
- Formatação de saída com múltiplos `println()`
- Subtração de valores

---

## 🛠️ Tecnologias Utilizadas

- **Java 17+** (ou superior)
- **IntelliJ IDEA** (IDE)
- **JDK (Java Development Kit)**
- **Tipos Primitivos e de Referência**

---

## 📁 Estrutura do Projeto

```
📦 variaveis-tipos-java/
└── 📋 README.md                   # Documentação dos exercícios
```

**Nota:** Os exercícios foram desenvolvidos e testados localmente. Este repositório contém a documentação completa de cada exercício realizado.

---

## 🚀 Como Executar

### **Pré-requisitos:**
- JDK 17 ou superior instalado
- IntelliJ IDEA (ou outra IDE Java)
- Variável de ambiente JAVA_HOME configurada

### **Para reproduzir os exercícios:**

1. **Crie um novo projeto Java na sua IDE**

2. **Copie o código de cada exercício:**
   - Crie uma nova classe com o nome indicado (Media, Casting ou Main)
   - Cole o código do exercício desejado
   - Execute a classe

3. **Ou compile e execute via terminal:**
   ```bash
   # Exemplo para o exercício 1
   # Salve o código em um arquivo Media.java
   
   # Compilar
   javac Media.java
   
   # Executar
   java Media
   ```

---

## 🎓 Conceitos Aprendidos

Durante o desenvolvimento destes exercícios, foram praticados os seguintes conceitos:

- **Tipos Primitivos**: Uso de `int`, `double` e `char`
- **Tipos de Referência**: Trabalho com `String`
- **Declaração de Variáveis**: Sintaxe `tipo nomeVariavel = valor;`
- **Casting Explícito**: Conversão forçada de tipos com `(tipo)`
- **Operadores Aritméticos**: Soma (`+`), divisão (`/`), multiplicação (`*`) e subtração (`-`)
- **Concatenação**: União de strings com operador `+`
- **Aspas Simples vs Duplas**: `'a'` para char, `"texto"` para String
- **Perda de Precisão**: Entendimento de truncamento em casting
- **Ordem de Precedência**: Operações matemáticas e concatenação
- **Cálculos Percentuais**: Conversão e aplicação de porcentagens
- **Operações Monetárias**: Trabalho com valores em dinheiro
- **Múltiplas Saídas**: Uso sequencial de `println()` para formatação
- **System.out.println()**: Saída formatada no console

---

## 📝 Tipos de Dados em Java

### 🔢 **Tipos Primitivos**

| Tipo    | Tamanho | Descrição                        | Exemplo        |
|---------|---------|----------------------------------|----------------|
| `byte`  | 8 bits  | Inteiro de -128 a 127            | `byte b = 10;` |
| `short` | 16 bits | Inteiro de -32.768 a 32.767      | `short s = 1000;` |
| `int`   | 32 bits | Inteiro de -2³¹ a 2³¹-1          | `int i = 100000;` |
| `long`  | 64 bits | Inteiro de -2⁶³ a 2⁶³-1          | `long l = 100000L;` |
| `float` | 32 bits | Decimal de precisão simples      | `float f = 3.14f;` |
| `double`| 64 bits | Decimal de precisão dupla        | `double d = 3.14159;` |
| `char`  | 16 bits | Caractere Unicode                | `char c = 'A';` |
| `boolean`| 1 bit  | Verdadeiro ou falso              | `boolean b = true;` |

### 📦 **Tipos de Referência**

- **String**: Sequência de caracteres
- **Arrays**: Coleções de elementos do mesmo tipo
- **Classes**: Tipos personalizados definidos pelo programador

---

## ⚠️ Importante sobre Casting

### **Casting Implícito (Widening)**
Conversão automática de um tipo menor para um tipo maior:
```java
int i = 100;
double d = i; // Automático, sem perda de dados
```

### **Casting Explícito (Narrowing)**
Conversão manual de um tipo maior para um tipo menor:
```java
double d = 9.78;
int i = (int) d; // Resultado: 9 (parte decimal é perdida)
```

---

## 🔄 Possíveis Melhorias

- Adicionar entrada de dados com `Scanner`
- Implementar validação de valores
- Criar métodos para reutilização de código
- Adicionar tratamento de exceções
- Implementar operações com mais tipos primitivos
- Criar exemplos com conversão entre todos os tipos

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/novo-exercicio`)
3. Commit suas mudanças (`git commit -m 'Adiciona novo exercício'`)
4. Push para a branch (`git push origin feature/novo-exercicio`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido durante o programa **ONE - Oracle Next Education**

---

## 🔗 Links Úteis

- [Oracle Next Education](https://www.oracle.com/br/education/oracle-next-education/)
- [Alura](https://www.alura.com.br/)
- [Documentação Java - Oracle](https://docs.oracle.com/en/java/)
- [Tipos Primitivos em Java](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
- [Type Casting em Java](https://www.w3schools.com/java/java_type_casting.asp)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Curso de Java - Alura](https://cursos.alura.com.br/)

---

<div align="center">
  <img src="https://img.shields.io/badge/Powered%20by-Java-orange?style=for-the-badge&logo=openjdk" alt="Powered by Java">
</div>
