# ☕ ONE - Oracle Next Education | Primeiros Passos em Java

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)](https://www.jetbrains.com/idea/)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 📖 Sobre o Projeto

Este repositório contém os **primeiros exercícios práticos em Java** desenvolvidos durante o programa **ONE - Oracle Next Education** em parceria com a **Alura**. Os exercícios são focados nos fundamentos da linguagem Java, incluindo:

- ☕ Sintaxe básica do Java
- 🖥️ Uso do método `main`
- 📝 Saída de dados com `System.out.println()`
- 🧮 Operações matemáticas básicas
- 🏗️ Estrutura de classes Java
- 💻 Desenvolvimento no IntelliJ IDEA

---

## 🎯 Exercícios Realizados

### 👋 **Exercício 1: Cumprimento Personalizado**
**Objetivo:** Criar uma classe `Perfil` que imprima uma mensagem de cumprimento

```java
public class Perfil {
    public static void main(String[] args) {
        System.out.println("Olá, Flávio");
    }
}
```

**Saída:**
```
Olá, Flávio
```

---

### 💬 **Exercício 2: Múltiplas Mensagens**
**Objetivo:** Adicionar uma segunda mensagem de cumprimento

```java
public class Perfil {
    public static void main(String[] args) {
        System.out.println("Olá, Flávio");
        System.out.println("Tudo bem?");
    }
}
```

**Saída:**
```
Olá, Flávio
Tudo bem?
```

---

### 📚 **Exercício 3: Anotações de Estudo**
**Objetivo:** Criar uma classe `Estudos` para documentar conceitos importantes

```java
public class Estudos {
    public static void main(String[] args) {
        System.out.println("JVM (Java Virtual Machine) - é a Máquina Virtual do Java responsável por executar o bytecode");
        System.out.println("JRE (Java Runtime Environment) - Ambiente de Execução do Java que fornece as bibliotecas padrões do Java para o JDK compilar o seu código e para a JVM executar o seu program");
    }
}
```

**Saída:**
```
JVM (Java Virtual Machine) - é a Máquina Virtual do Java responsável por executar o bytecode
JRE (Java Runtime Environment) - Ambiente de Execução do Java que fornece as bibliotecas padrões do Java para o JDK compilar o seu código e para a JVM executar o seu program
```

---

### ➕ **Exercício 4: Operação de Soma**
**Objetivo:** Criar uma classe `Soma` que calcule e imprima o resultado de uma adição

```java
public class Soma {
    public static void main(String[] args) {
        System.out.println(10+5);
    }
}
```

**Saída:**
```
15
```

---

### ➖ **Exercício 5: Operação de Subtração**
**Objetivo:** Criar uma classe `Subtracao` que calcule e imprima o resultado de uma subtração

```java
public class Subtracao {
    public static void main(String[] args) {
        System.out.println(10-5);
    }
}
```

**Saída:**
```
5
```

---

## 🛠️ Tecnologias Utilizadas

- **Java 17+** (ou superior)
- **IntelliJ IDEA** (IDE)
- **JDK (Java Development Kit)**
- **JVM (Java Virtual Machine)**

---

## 📁 Estrutura do Projeto

```
📦 primeiros-passos-java/
├── 📂 src/
│   ├── ☕ Perfil.java        # Exercícios 1 e 2
│   ├── 📚 Estudos.java       # Exercício 3
│   ├── ➕ Soma.java          # Exercício 4
│   └── ➖ Subtracao.java     # Exercício 5
└── 📋 README.md              # Documentação do projeto
```

---

## 🚀 Como Executar

### **Pré-requisitos:**
- JDK 17 ou superior instalado
- IntelliJ IDEA (ou outra IDE Java)
- Variável de ambiente JAVA_HOME configurada

### **Passos:**

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/primeiros-passos-java.git
   ```

2. **Abra o projeto no IntelliJ IDEA:**
   - File → Open → Selecione a pasta do projeto

3. **Execute cada classe individualmente:**
   - Abra o arquivo `.java` desejado
   - Clique com o botão direito no arquivo
   - Selecione "Run 'NomeDaClasse.main()'"

4. **Ou compile e execute via terminal:**
   ```bash
   # Compilar
   javac Perfil.java
   
   # Executar
   java Perfil
   ```

---

## 🎓 Conceitos Aprendidos

Durante o desenvolvimento destes exercícios, foram praticados os seguintes conceitos:

- **Estrutura de Classe Java**: Declaração de classes com `public class`
- **Método main**: Ponto de entrada da aplicação Java
- **System.out.println()**: Saída de dados no console
- **Operadores Aritméticos**: Uso de `+` e `-` para operações matemáticas
- **Tipos de Dados**: Trabalho com números inteiros e strings
- **Compilação**: Processo de transformação de código Java em bytecode
- **JVM, JRE e JDK**: Compreensão da arquitetura Java
- **Convenções de Nomenclatura**: PascalCase para nomes de classes
- **Estrutura de Projeto**: Organização de arquivos `.java`
- **IDE IntelliJ IDEA**: Familiarização com ambiente de desenvolvimento

---

## 📝 Conceitos Importantes

### ☕ **JVM (Java Virtual Machine)**
Máquina Virtual do Java responsável por executar o bytecode e garantir a portabilidade do código Java entre diferentes plataformas.

### 📦 **JRE (Java Runtime Environment)**
Ambiente de Execução do Java que fornece as bibliotecas padrões necessárias para executar aplicações Java.

### 🛠️ **JDK (Java Development Kit)**
Kit de Desenvolvimento Java que inclui o compilador, ferramentas de desenvolvimento e a JRE para desenvolvimento completo de aplicações.

---

## 🔄 Possíveis Melhorias

- Adicionar variáveis para armazenar valores
- Implementar entrada de dados com `Scanner`
- Criar métodos adicionais além do `main`
- Adicionar comentários explicativos no código
- Implementar mais operações matemáticas (multiplicação, divisão, módulo)
- Usar variáveis para tornar o código mais dinâmico

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
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Java Tutorial - W3Schools](https://www.w3schools.com/java/)
- [Download JDK](https://www.oracle.com/java/technologies/downloads/)
- [Curso de Java - Alura](https://cursos.alura.com.br/)

---

<div align="center">
  <img src="https://img.shields.io/badge/Powered%20by-Java-orange?style=for-the-badge&logo=openjdk" alt="Powered by Java">
</div>
