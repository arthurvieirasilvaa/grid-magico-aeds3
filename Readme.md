# Trabalho Prático 2 - Algoritmos e Estruturas de Dados III

- **Disciplina**: Algoritmos e Estruturas de Dados III
- **Curso**: Ciência da Computação
- **Instituição**: Universidade Federal de São João Del Rei
- **Docente**: Leonardo Chaves Dutra da Rocha
- **Data**: 18 de Setembro de 2023

## 📖 Objetivo:

Implementar soluções para o problema de movimentação de Harry Potter em um grid mágico, onde ele deve alcançar um artefato sem sua energia cair para 0 ou menos.
Cada célula do grid contém uma poção (que aumenta a energia) ou um monstro (que reduz a energia). O mago deve sair da célula (1,1) e alcançar o artefato na célula (R,C) com a maior energia possível. A tarefa é encontrar a energia mínima necessária no início para que ele consiga concluir a jornada com energia positiva.

## 🖥️ Tecnologias

- **Linguagem**: C
- **Ambiente**: Linux

## 🧠 Estratégias Utilizadas

- **Algoritmo Gulosa**
- **Programação Dinâmica**

## 📝​ Descrição do Projeto

[Ver descrição](./descricao.pdf)

## 📚 Documentação do Projeto

[Ver documentação](./documentação.pdf)

## ✏️ Instruções

### ⚒️ Compilação

- Compilar os arquivos:
```
make
````

- Limpar os arquivos:
```
make clean
```

### 🚀 Execução

````
./tp2 <estrategia> entrada.txt
````

⚠️ ***Obs***: estratégia é 1 para o Algoritmo Guloso ou 2 para a Programação Dinâmica e entrada.txt é o nome do arquivo de teste que será lido
