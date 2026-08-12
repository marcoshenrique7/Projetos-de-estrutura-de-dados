# 🔗 Trabalho Prático — Listas Dinâmicas

![Linguagem](https://img.shields.io/badge/C-00599C?style=flat-square\&logo=c\&logoColor=white)
![Projeto](https://img.shields.io/badge/Projeto-Acadêmico-blueviolet?style=flat-square)
![Conteúdo](https://img.shields.io/badge/Conteúdo-Listas%20Dinâmicas-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-green?style=flat-square)

Projeto acadêmico desenvolvido para estudar e implementar os principais tipos de **listas dinâmicas utilizando a linguagem C**, aplicando conceitos de ponteiros, alocação dinâmica de memória e estruturas encadeadas.

## 👨‍💻 Equipe

* Andreas
* Davi
* Marcos

## 🎯 Objetivo

O objetivo deste trabalho é compreender o funcionamento, as características e as aplicações dos quatro principais tipos de listas dinâmicas:

* Lista Simplesmente Encadeada;
* Lista Duplamente Encadeada;
* Lista Circular Simples;
* Lista Duplamente Circular.

Cada estrutura foi implementada manualmente em C, permitindo observar as diferenças de organização, navegação e manipulação dos elementos.

## 🧠 Estruturas Estudadas

### 1. Lista Simplesmente Encadeada

Cada nó possui um valor e um ponteiro para o próximo elemento da lista.

```text
[ dado | próximo ] -> [ dado | próximo ] -> [ dado | NULL ]
```

Características:

* Navegação apenas em uma direção;
* Estrutura simples;
* Inserções e remoções podem ser realizadas dinamicamente;
* Consome menos memória que uma lista duplamente encadeada.

📁 `lista_simples/`

---

### 2. Lista Duplamente Encadeada

Cada nó possui um ponteiro para o elemento anterior e outro para o próximo elemento.

```text
NULL <- [ anterior | dado | próximo ] <-> [ anterior | dado | próximo ] -> NULL
```

Características:

* Permite navegação nos dois sentidos;
* Facilita algumas operações de remoção e inserção;
* Utiliza mais memória devido ao ponteiro adicional.

📁 `lista_dupla/`

---

### 3. Lista Circular Simples

Possui estrutura semelhante à lista simplesmente encadeada, porém o último nó aponta novamente para o primeiro.

```text
[ dado | próximo ] -> [ dado | próximo ] -> [ dado | próximo ]
       ^                                      |
       |______________________________________|
```

Características:

* Não possui um final representado por `NULL`;
* Permite percorrer continuamente os elementos;
* Útil para aplicações que funcionam em ciclos.

📁 `lista_circular/`

---

### 4. Lista Duplamente Circular

Combina as características das listas duplamente encadeadas e circulares.

O último elemento aponta para o primeiro e o primeiro também mantém uma ligação com o último.

```text
      ┌──────────────────────────────────────────┐
      ↓                                          |
[ anterior | dado | próximo ] <-> [ anterior | dado | próximo ]
      |                                          ↑
      └──────────────────────────────────────────┘
```

Características:

* Navegação nos dois sentidos;
* Estrutura circular;
* Permite percorrer continuamente a lista para frente ou para trás;
* Maior flexibilidade, porém com maior consumo de memória.

📁 `lista_dupla_circular/`

## 📂 Estrutura do Projeto

```text
.
├── lista_simples/
├── lista_dupla/
├── lista_circular/
├── lista_dupla_circular/
├── Trabalho Listas - Reinaldo Cotrim.pdf
└── README.md
```

Cada diretório contém a implementação correspondente a um dos tipos de listas estudados.

## ⚙️ Operações Implementadas

As implementações trabalham com operações fundamentais de listas dinâmicas, como:

* Inserção de elementos;
* Remoção de elementos;
* Busca;
* Exibição;
* Percurso da estrutura;
* Manipulação através de ponteiros;
* Alocação dinâmica de memória;
* Liberação da memória utilizada.

Também foram considerados casos de borda, como:

* Lista vazia;
* Inserção do primeiro elemento;
* Remoção do primeiro elemento;
* Remoção do último elemento;
* Lista contendo apenas um nó.

## 📋 Descrição da Atividade

O trabalho foi dividido em diferentes etapas.

### 1. Estudo das estruturas

Para cada tipo de lista foram analisados:

* Estrutura do nó;
* Forma de encadeamento;
* Operações principais;
* Inserção;
* Remoção;
* Busca;
* Exibição;
* Vantagens;
* Limitações.

### 2. Implementação

Foram desenvolvidos quatro exemplos práticos distintos, um para cada estrutura.

Algumas aplicações possíveis são:

| Estrutura                    | Exemplos de aplicação                                 |
| ---------------------------- | ----------------------------------------------------- |
| Lista Simplesmente Encadeada | Fila de impressão, cadastro linear, log de eventos    |
| Lista Duplamente Encadeada   | Histórico de navegação, desfazer/refazer, deque       |
| Lista Circular Simples       | Rodízio de tarefas, escalonamento de processos        |
| Lista Duplamente Circular    | Playlist, carrossel de imagens, rodadas de campeonato |

### 3. Análise Técnica

O trabalho também envolve:

* Descrição das implementações;
* Justificativa dos exemplos utilizados;
* Representação dos nós e ligações;
* Comparação entre as diferentes estruturas.

### 4. Demonstração

Cada implementação deve demonstrar operações como:

* Inserção;
* Remoção;
* Busca;
* Exibição;
* Manipulação de listas vazias;
* Tratamento de casos de borda.

## 🛠️ Requisitos Técnicos

As implementações seguem os seguintes requisitos:

* Desenvolvimento em linguagem C;
* Implementação manual das listas;
* Uso de ponteiros;
* Uso de alocação dinâmica;
* Validação das alocações de memória;
* Liberação correta da memória com `free()`;
* Organização das implementações em diretórios separados.

## 🧩 Conceitos Aplicados

Durante o desenvolvimento foram utilizados conceitos importantes de Estrutura de Dados e da linguagem C:

* Ponteiros;
* `struct`;
* Nós;
* Encadeamento;
* Alocação dinâmica;
* `malloc()`;
* `free()`;
* Manipulação de memória;
* Tipos Abstratos de Dados;
* Modularização;
* Estruturas lineares.

## 🚀 Como Compilar

Entre na pasta da implementação desejada.

Por exemplo:

```bash
cd lista_simples
```

Verifique os arquivos disponíveis:

```bash
ls
```

Em seguida, compile utilizando o GCC.

Para uma implementação composta apenas por `main.c`:

```bash
gcc main.c -o lista
```

Execute com:

```bash
./lista
```

> O comando de compilação pode variar conforme os arquivos existentes dentro de cada diretório.

## 📊 Comparação das Estruturas

| Estrutura              | Próximo | Anterior | Circular |
| ---------------------- | :-----: | :------: | :------: |
| Simplesmente Encadeada |    ✅    |     ❌    |     ❌    |
| Duplamente Encadeada   |    ✅    |     ✅    |     ❌    |
| Circular Simples       |    ✅    |     ❌    |     ✅    |
| Duplamente Circular    |    ✅    |     ✅    |     ✅    |

Cada estrutura apresenta vantagens específicas, e a escolha depende das operações e necessidades do problema que será resolvido.

## 📚 Objetivo Acadêmico

O trabalho foi desenvolvido como parte dos estudos da disciplina de **Estrutura de Dados**, buscando compreender como estruturas dinâmicas são organizadas diretamente na memória.

A implementação manual das listas permite visualizar na prática como os nós são conectados por ponteiros e como operações de inserção, remoção e navegação alteram essas ligações.

## 🛠️ Tecnologias Utilizadas

* C
* GCC
* Git
* GitHub

## 📄 Material da Atividade

O enunciado utilizado para o desenvolvimento do trabalho também está disponível neste diretório:

`Trabalho Listas - Reinaldo Cotrim.pdf`

## 📄 Projeto Acadêmico

Projeto desenvolvido para fins educacionais durante os estudos de **Estrutura de Dados**.
