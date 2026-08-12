# 🧠 Trabalho Prático — Alocação Dinâmica em C

![Linguagem](https://img.shields.io/badge/C-00599C?style=flat-square\&logo=c\&logoColor=white)
![Projeto](https://img.shields.io/badge/Projeto-Acadêmico-blueviolet?style=flat-square)
![Conteúdo](https://img.shields.io/badge/Conteúdo-Alocação%20Dinâmica-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-green?style=flat-square)

Projeto acadêmico desenvolvido para aplicar, na prática, os conceitos de **alocação dinâmica de memória na linguagem C**, utilizando ponteiros e funções da biblioteca padrão.

## 👨‍💻 Equipe

* Andreas Gunther
* Davi Carvalho
* Marcos Henrique

## 🎯 Objetivo

O objetivo deste trabalho é desenvolver exercícios utilizando **alocação dinâmica de memória de forma correta e explícita**, aplicando os conceitos estudados em sala de aula.

Durante as atividades foram utilizadas principalmente as funções:

* `malloc()`
* `calloc()`
* `realloc()`
* `free()`

## 🧩 Conceitos de Alocação Dinâmica

### `malloc()`

Reserva dinamicamente uma determinada quantidade de memória.

O conteúdo inicial dessa memória é **indeterminado**, portanto seus valores não devem ser utilizados antes de serem inicializados.

Exemplo:

```c
int *vetor = malloc(5 * sizeof(int));
```

### `calloc()`

Reserva memória para uma determinada quantidade de elementos e inicializa todos os bytes do bloco com zero.

Exemplo:

```c
int *vetor = calloc(5, sizeof(int));
```

### `realloc()`

Permite alterar o tamanho de um bloco de memória que já havia sido alocado anteriormente.

Exemplo:

```c
vetor = realloc(vetor, 10 * sizeof(int));
```

### `free()`

Libera um bloco de memória que foi alocado dinamicamente e que não será mais utilizado.

Exemplo:

```c
free(vetor);
```

A liberação correta da memória é importante para evitar **vazamentos de memória** (*memory leaks*).

## 📂 Estrutura do Projeto

```text
.
├── q1-aloc.c
├── q2-aloc.c
├── q1_parte2.c
├── q2_parte2.c
├── q3_parte2.c
└── README.md
```

### Arquivos

| Arquivo       | Descrição                        |
| ------------- | -------------------------------- |
| `q1-aloc.c`   | Exercício 1 de alocação dinâmica |
| `q2-aloc.c`   | Exercício 2 de alocação dinâmica |
| `q1_parte2.c` | Exercício 1 da segunda parte     |
| `q2_parte2.c` | Exercício 2 da segunda parte     |
| `q3_parte2.c` | Exercício 3 da segunda parte     |

Cada programa é independente e trabalha diferentes aplicações dos conceitos de alocação dinâmica.

Entre as operações realizadas estão:

* Entrada de dados pelo usuário;
* Manipulação de ponteiros;
* Alocação de memória com `malloc()` e `calloc()`;
* Redimensionamento com `realloc()`;
* Manipulação dos dados armazenados;
* Liberação da memória com `free()`.

## 🧠 Conceitos Aplicados

Durante o desenvolvimento foram trabalhados conceitos como:

* Ponteiros;
* Alocação dinâmica;
* Gerenciamento de memória;
* Vetores dinâmicos;
* Entrada e saída de dados;
* Manipulação de dados;
* Redimensionamento de memória;
* Liberação de memória.

## 🚀 Como Compilar e Executar

É necessário possuir o compilador **GCC** instalado.

Abra o terminal e acesse a pasta onde estão os arquivos do projeto.

Para visualizar os arquivos:

```bash
ls
```

### Exercício 1

Compile:

```bash
gcc q1-aloc.c -o q1
```

Execute:

```bash
./q1
```

### Exercício 2

Compile:

```bash
gcc q2-aloc.c -o q2
```

Execute:

```bash
./q2
```

### Exercício 1 — Parte 2

Compile:

```bash
gcc q1_parte2.c -o q1p2
```

Execute:

```bash
./q1p2
```

### Exercício 2 — Parte 2

Compile:

```bash
gcc q2_parte2.c -o q2p2
```

Execute:

```bash
./q2p2
```

### Exercício 3 — Parte 2

Compile:

```bash
gcc q3_parte2.c -o q3p2
```

Execute:

```bash
./q3p2
```

## 🖥️ Demonstração

### `q1-aloc.c`

Execução do primeiro exercício de alocação dinâmica.

<img width="1102" height="669" alt="Execução do exercício q1-aloc" src="https://github.com/user-attachments/assets/6f7a8c1e-d80b-42fa-aae9-9ada0b77ab19" />

---

### `q2-aloc.c`

Execução do segundo exercício de alocação dinâmica.

<img width="1165" height="777" alt="Execução do exercício q2-aloc" src="https://github.com/user-attachments/assets/8a2c98a6-be69-4336-a9a6-538eb97e19f3" />

---

### `q1_parte2.c`

Execução do primeiro exercício da segunda parte.

<img width="721" height="731" alt="Execução do exercício q1 parte 2" src="https://github.com/user-attachments/assets/152ce2b5-109b-478c-896f-5f53dfc40205" />

---

### `q2_parte2.c`

Execução do segundo exercício da segunda parte.

<img width="843" height="747" alt="Execução do exercício q2 parte 2" src="https://github.com/user-attachments/assets/4af6ef74-4cca-4f68-ab6f-dd43084c7bc4" />

---

### `q3_parte2.c`

Execução do terceiro exercício da segunda parte.

<img width="1051" height="769" alt="Execução do exercício q3 parte 2" src="https://github.com/user-attachments/assets/0b899a2d-faff-48ea-90f6-0604bb38090d" />

## 📚 Objetivo Acadêmico

Este trabalho foi desenvolvido como parte dos estudos de **Estrutura de Dados**, com foco na compreensão do funcionamento da memória durante a execução de programas em C.

A implementação dos exercícios permitiu praticar o gerenciamento manual de memória e compreender a importância de realizar corretamente a **alocação, manipulação, redimensionamento e liberação de memória**.

## 🛠️ Tecnologias Utilizadas

* C
* GCC
* Git
* GitHub

## 📄 Projeto Acadêmico

Projeto desenvolvido para fins educacionais durante os estudos da disciplina de **Estrutura de Dados**.
