# Tipos de Prompt

## Descrição

Na engenharia de prompt, diferentes estruturas de prompts são usadas para guiar um modelo de IA a produzir a saída desejada. Neste desafio, você vai associar tipos comuns de prompt com suas descrições correspondentes.

## Entrada

Será fornecido um dos seguintes tipos de prompt:

* Prompt de Instrução

* Prompt de Pergunta

* Prompt com Exemplos

* Prompt de Contexto

## Saída

A saída deve ser a descrição correspondente ao tipo de prompt fornecido:

* Indica claramente o que o modelo deve fazer

* Formato mais direto, faz uma pergunta para obter uma resposta específica

* Usado para fornecer um conjunto de exemplos antes da tarefa

* Fornece informações antecedentes para guiar a resposta

## Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. 

Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada               | Saída                                                        |
|-----------------------|--------------------------------------------------------------|
| Prompt de Instrução   | Indica claramente o que o modelo deve fazer                  |
| Prompt de Pergunta    | Formato mais direto, faz uma pergunta para obter uma resposta específica |
| Prompt com Exemplos   | Usado para fornecer um conjunto de exemplos antes da tarefa  |

Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.

Os desafios apresentados aqui têm como objetivo principal exercitar os conceitos aprendidos e proporcionar um primeiro contato com lógica de programação. Caso não tenha experiência em programação, utilize o template disponível e preencha com os conceitos aprendidos. Para resetar o template, basta clicar em "Restart Code".

## Template inicial

```Python
# Recebe a entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição:
def descrever_prompt(tipo):
  if tipo == "Prompt de Instrução":
    return "Indica claramente o que o modelo deve fazer"
  
  # COMPLETE AQUI: Preencha corretamente cada conceito, considerando as descrições abaixo: 
  elif tipo == "Prompt de Pergunta":
    return "escreva aqui o conceito correspondente"

  elif tipo == "Prompt com Exemplos":
    return "escreva aqui o conceito correspondente"

  elif tipo == "Prompt de Contexto":
    return "escreva aqui o conceito correspondente"

print(descrever_prompt(entrada))
```
