
# Exercício de Programação Funcional em Java

Este projeto é baseado no capítulo sobre programação funcional e expressões lambda do curso de Java. O exercício tem como objetivo aplicar conceitos de streams, expressões lambda e operações funcionais em um contexto prático, utilizando uma lista de empregados (“Employee”) lida a partir de um arquivo CSV.

## 🚀 Tecnologias usadas
- Java 21
- Conceitos de programação funcional
- API de Streams do Java
- Manipulação de arquivos com BufferedReader
- Uso de Comparator para ordenação customizada

## 🔨 Funcionalidades 
### Leitura de Arquivo:
- Lê um arquivo CSV contendo informações de empregados.
- Formato do arquivo:
```
String Nome,String Email,Double Salário

```

### Emails de Empregados com Salário Superior a um Valor:

- Solicita ao usuário um valor de referência para o salário.
- Filtra empregados com salário acima desse valor.
- Ordena os emails em ordem alfabética.
- Exibe os emails filtrados.

### Soma de Salários de Empregados com Nome Começando com 'M':

- Filtra empregados cujo nome comece com a letra ‘M’.
- Soma os salários desses empregados.
- Exibe o resultado formatado com duas casas decimais.

## Exemplo de Saída 
### Arquivo de Entrada:
```
Maria,maria@gmail.com,3000.00
Alex,alex@gmail.com,1700.00
Bob,bob@gmail.com,2500.00
Marco,marco@gmail.com,800.00
```

### Entrada do Usuário 
```
Enter full file path: /caminho/para/employees.csv
Enter salary: 2000.00
```

### Saída do Programa
```
Email of people whose salary is more than 2000.00:
Bob@gmail.com
Maria@gmail.com

Sum of salary of people whose name starts with 'M': 3800.00
```
