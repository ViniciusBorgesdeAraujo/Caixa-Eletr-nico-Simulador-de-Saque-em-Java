# Caixa Eletrônico – Simulador de Saque em Java

Este projeto simula o funcionamento de um **caixa eletrônico**, onde o usuário informa um valor e o programa devolve a quantidade mínima de notas necessárias para compor esse valor.

## Propósito do Projeto

Este projeto foi desenvolvido como parte de uma prática de lógica de programação e pensamento algorítmico. Ele demonstra como **dividir um problema grande em partes menores** para encontrar uma solução mais simples e eficiente.

---

## Como dividir problemas grandes em partes menores

Um dos segredos para resolver problemas em programação é **quebrá-los em partes menores e bem definidas**. Neste projeto, por exemplo, o problema geral ("simular o saque de um caixa eletrônico") foi dividido em etapas:

1. **Receber o valor do saque**
2. **Definir as notas disponíveis**
3. **Calcular a quantidade de cada nota necessária**
4. **Exibir o resultado para o usuário**

Cada uma dessas etapas foi transformada em um **método separado**, facilitando a leitura, o teste e a manutenção do código.

---

## Pensamento Algorítmico: O segredo

O pensamento algorítmico é a capacidade de **pensar passo a passo** para resolver um problema. Você desenvolve isso praticando a decomposição de problemas, identificando padrões e criando soluções lógicas.

Neste projeto:

- Utilizamos **laços de repetição** para calcular as notas.
- Aplicamos **divisão inteira e módulo** para determinar quantas notas de cada tipo são necessárias.
- Organizamos o código de forma modular, deixando-o limpo e reutilizável.

---

## Dicas práticas para evoluir como programador

Você pode aplicar hoje mesmo:

- **Resolva um problema por dia**, mesmo que pequeno.
- **Explique seu código** em voz alta ou escrevendo, como se estivesse ensinando alguém.
- **Divida o problema** em funções ou métodos. Isso facilita o raciocínio e deixa o código mais limpo.
- **Refatore**: sempre revise seu código e veja se pode melhorá-lo.
- **Use comentários inteligentes**: documente seu raciocínio, não o óbvio.

---

## Código-Fonte

```java
public static int obterValorSaque(Scanner scanner) { ... }

public static int[] calularNotas(int valor, int[] notas) { ... }

public static void exibirNotas(int[] notas, int[] quantidadeNotas) { ... }
```

---

## Aprendizado

Este projeto mostra que com passos simples e bem definidos, podemos resolver até problemas que parecem difíceis. A prática constante e o raciocínio estruturado são a chave para evoluir como desenvolvedor.

---
