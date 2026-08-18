## Documentação | gqs-algoritmo-01-py
### Aluno: Luiz Henrique Souza dos Santos
### RA: 4251923673
#

#### Objetivo 
Este é um algoritmo em Python que verifica se uma palavra ou frase pode ser lido no sentido normal ou no sentido inverso, desconsiderando espaços, pontuação, caracteres especiais e diferença entre letras maiúsculas e minúsculas.
#

#### Funcionamento
A função ```analisar()``` realiza as seguintes etapas:

- Verifica se a entrada é ```None```.
- Remove caracteres que não sejam letras ou números.
- Converte o texto para letras minúsculas.
- Inverte a string utilizando slicing.
- Compara o texto original tratado com sua versão invertida.
- Retorna ```True``` se for um palíndromo e ```False``` caso contrário.


A biblioteca ```import re``` é utilizada para a limpeza da entrada e já faz parte da biblioteca padrão do Python.
#

#### Uso

Execute o arquivo Python:

```python nome_do_arquivo.py```

#### Exemplo:
```
texto = "o gato preto na parede"

print(analisar(texto))
```
```
output:

True
```
#

**Exemplos:**

O programa possui dois testes:
```
Teste 1: True
Teste 2: True
```


As frases são tratadas removendo espaços e caracteres especiais antes da verificação.

Função
```analisar(entrada)```

Parâmetro	```Tipo Retorno```
entrada	```True ou False```
```
Retorna: True // Quando a entrada é um palíndromo
Retorna: False // Quando não é um palíndromo.
```
