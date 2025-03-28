<h1>
    <a href="https://github.com/Rafael705">
     <img align="center" width="40px" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></a>
    <span> 📌 Guia de Tipos e Variáveis em Java </span>
</h1>



## 📝 Assuntos Abordados
- Numéricos inteiros e decimais
- Tipos lógicos
- Caracteres
- Objetos
- Diferença entre variável e constante

---

## 🔢 Tipos de Dados

### 🔹 Tipos Numéricos Inteiros
Os tipos numéricos inteiros são usados para armazenar números sem casas decimais. Dependendo do tamanho necessário, pode-se escolher entre:

- `byte`: Armazena números pequenos (-128 a 127), ocupando 1 byte.
- `short`: Armazena números um pouco maiores (-32.768 a 32.767), ocupando 2 bytes.
- `int`: O tipo mais comum, armazenando valores de -2.147.483.648 a 2.147.483.647, ocupando 4 bytes.
- `long`: Usado para números ainda maiores, ocupando 8 bytes. Quando atribuímos um valor muito grande, devemos adicionar um `L` ao final.

```java
long populacaoMundial = 8000000000L;
```

### 🔹 Tipos Numéricos Decimais (Parte Fracionária)
Usados para armazenar números com casas decimais:

- `float`: Ocupa 4 bytes e precisa terminar com `F` ao ser declarado.
- `double`: Ocupa 8 bytes e é mais preciso, sendo o tipo padrão para números com casas decimais.

```java
float preco = 3.14F;
double salario = 4500.99;
```

### 🔹 Tipos Lógicos
O tipo `boolean` armazena apenas dois valores possíveis: `true` (verdadeiro) ou `false` (falso). Muito usado para controle de fluxo no código.

```java
boolean luzAcesa = true;
```

### 🔹 Tipos de Caracteres
O tipo `char` armazena um único caractere entre aspas simples (`' '`).

```java
char letra = 'A';
```

### 🔹 Objetos
Objetos são instâncias de classes e podem armazenar múltiplos tipos de dados, além de métodos.

```java
String nome = "Rafael";
```

Aqui, `String` é uma classe que representa cadeias de caracteres.

---

## 🖊️ Declaração de Variáveis
Variáveis são espaços na memória que armazenam valores. Para declarar uma variável, usamos a sintaxe:

```java
<tipo> <nome> = <atribuição opcional>;
```

Exemplos:

```java
int idade;
int anoFabricacao = 2021;
double salarioMinimo = 2500.0;
```
Se não atribuirmos um valor, a variável recebe um valor padrão do seu tipo (`0` para números, `false` para booleanos e `null` para objetos).

---

## 🔐 Variáveis vs. Constantes

- **Variáveis**: Podem ter seus valores alterados durante a execução do programa.
- **Constantes**: Valores que **nunca se alteram**. Para definir uma constante, usa-se a palavra-chave `final`, e o nome deve estar em **caixa alta**.

Exemplo:

```java
final double VALOR_DE_PI = 3.14;
```

Como `VALOR_DE_PI` é uma constante, seu valor não pode ser alterado depois de definido.

---

## 📌 Autor
💻🛠️ Feito por **Rafael Pontes** 💻🛠️

