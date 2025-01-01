# Hello-World

This is my first project in Visualg

**Var**

As variáveis devem sempre iniciar com o **IDENTIFICADOR:TIPO**

**Identificadores devem iniciar sempre com:**

1. Uma letra  
2. Os próximos caracteres devem ser letras ou números  
3. Não utilizar nenhum símbolo, exceto `_`  
4. Identificadores não podem ter espaços em branco  
5. Não podem conter letras com acentos  
6. Não pode ser uma palavra reservada, tais como `Algoritmo`, `Var`, `Início`, etc.  

**Exemplos inválidos:**
- Média (contém acento)  
- Salário Bruto (contém acento e espaço)  
- 9dade (inicia com um número)

---

**Tipos primitivos:**
- **Inteiro:** São números que não são fracionários (1, 3, -5, 198, 0)  
- **Real:** Possuem partes fracionárias (0.5, 5.0, 9.8, -77.3)  
- **Caractere:** Tudo que é colocado entre aspas ("LG", "Algoritmo", "123")  
- **Lógico:** Guarda apenas dois valores, verdadeiro e falso  

```visualg

Algoritmo "HELLO WORLD - AULA 2 - CURSO EM VIDEO"

Var

msg:caractere // Observe que criou na tabela ao lado uma variável vazia >>

Início

    escreval("hello world") // escreval escreve e salta uma linha nova
    escreval("agora ele pula a linha quando escrevo escreval")

    // Para preencher a variável, precisamos criar uma atribuição:

    msg <- "Olá, mundo! Feito com atribuição da variável MSG"
    escreval(msg)

Fimalgoritmo
