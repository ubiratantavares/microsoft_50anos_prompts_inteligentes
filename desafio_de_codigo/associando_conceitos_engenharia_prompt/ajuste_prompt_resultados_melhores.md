# Ajuste de Prompt para Resultados Melhores

## Descrição

Muitas vezes, a resposta de um modelo de IA pode ser genérica ou imprecisa.

Por isso, ajustar o prompt corretamente é fundamental para guiar a IA.

Neste desafio, associe a estratégia de ajuste de prompt com seu objetivo.

## Entrada

Considere as seguintes estratégias:

* Adicionar contexto

* Usar exemplos

* Especificar formato da resposta

* Dividir tarefas complexas

## Saída

A saída esperada é o objetivo correspondente à estratégia de prompt:

* Permite que a IA entenda melhor a situação ou intenção

* Ajuda a IA a replicar padrões esperados

* Garante que a saída seja apresentada do jeito desejado

* Torna o problema mais simples e direcionado

## Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. 

Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada               | Saída                                                        |
|-----------------------|--------------------------------------------------------------|
| Adicionar contexto    | Permite que a IA entenda melhor a situação ou intenção      |
| Usar exemplos         | Ajuda a IA a replicar padrões esperados                     |
| Especificar formato da resposta | Garante que a saída seja apresentada do jeito desejado |
| Dividir tarefas complexas | Torna o problema mais simples e direcionado              |

Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.

Os desafios apresentados aqui têm como objetivo principal exercitar os conceitos aprendidos e proporcionar um primeiro contato com lógica de programação.

Caso não tenha experiência em programação, utilize o template disponível e preencha com os conceitos aprendidos. 

Para resetar o template, basta clicar em “Restart Code”.

## Template Inicial

```Python
# Recebe a entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição.
def ajustar_prompt(estrategia):
  if estrategia == "Adicionar contexto":
    return "Permite que a IA entenda melhor a situação ou intenção"

  # COMPLETE AQUI: Preencha corretamente cada conceito, considerando as descrições abaixo:
  elif estrategia == "Usar exemplos":
    return "escreva aqui o conceito correspondente"

  elif estrategia == "Especificar formato da resposta":
    return "escreva aqui o conceito correspondente"

  elif estrategia == "Dividir tarefas complexas":
    return "escreva aqui o conceito correspondente"

print(ajustar_prompt(entrada))
```
