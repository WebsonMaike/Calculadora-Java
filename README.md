# Calculadora Java (Console)

Calculadora simples feita em Java para praticar lógica de programação, estruturas de repetição e tratamento de erros.

## Funcionalidades

- Operações básicas: soma, subtração, multiplicação e divisão
- Loop de continuação usando `do-while` (permite repetir o cálculo)
- Modo acumulativo: o resultado de uma operação vira a base para a próxima
- Tratamento de erro para divisão por zero
- Validação de opção inválida no menu

## Demonstração

![Calculadora rodando](assets/demo.png)

No exemplo acima: o usuário informa o valor inicial (10), soma 20 (resultado: 30.0), decide continuar e multiplica o resultado por 10 (resultado final: 300.0).

## Como rodar

```bash
javac src/Main.java
java -cp src Main
```

## O que aprendi

- Diferença entre `while` e `do-while` e quando usar cada um
- Uso de `switch` com `break` para evitar fall-through
- Manutenção de estado entre iterações de um loop (variável `resultado`)
- Boas práticas de organização de repositório Git/GitHub

## Próximos passos

- Adicionar opção de reiniciar o cálculo (zerar o resultado acumulado)
- Migrar para versão com interface gráfica (JavaFX) ou API REST (Spring Boot)
