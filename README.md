<h1>Teste de Unidade com .NET aplicando os fundamentos do TDD</h1>

Este repositório contém um exemplo de teste de unidade utilizando o framework .NET com a linguagem C#. O código implementa uma classe Calculadora com operações matemáticas básicas e testes baseados em TDD (Test-Driven Development).

 **Estrutura do Projeto**

A solução possuem dois projetos, que consiste em:

Projeto NewTalents contendo a Classe Calculadora; e o projeto TestesNewTalents que possui a classe de Testes Unitários UnitTest1.

A classe Calculadora está localizada no namespace NewTalents. Esta classe fornece métodos para operações matemáticas básicas (soma, subtração, multiplicação e divisão) e mantém um histórico das operações realizadas.

**Funcionalidades da Classe Calculadora**
* somar: Soma dois valores inteiros.
* subtrair: Subtrai o segundo valor inteiro do primeiro.
* multiplicar: Multiplica dois valores inteiros.
* dividir: Divide o primeiro valor inteiro pelo segundo.
* historico: Retorna os últimos três resultados das operações realizadas.

### Testes Unitários
Os testes unitários estão localizados no namespace TestesNewTalents. Utilizam o framework xUnit para validar o comportamento da classe Calculadora.

**Descrição dos Testes**

* TesteSomar: Verifica se a soma de dois números está correta.
* TesteSubtrair: Verifica se a subtração de dois números está correta.
* TesteDividir: Verifica se a divisão de dois números está correta.
* TestMultiplicar: Verifica se a multiplicação de dois números está correta.
* TestarDivisaoPorZero: Verifica se a divisão por zero lança a exceção adequada.
* TestarHistorico: Verifica se o histórico de operações está armazenando corretamente os últimos três resultados.

### Conclusão
Este exemplo demonstra a criação e teste de uma classe simples em C# utilizando o framework .NET e técnicas de TDD. Os testes garantem que a implementação da Calculadora funcionando conforme o esperado e que casos especiais, como divisão por zero, sejam tratados corretamente.