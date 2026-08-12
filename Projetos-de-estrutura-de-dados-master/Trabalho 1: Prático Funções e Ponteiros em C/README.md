# 🎮 Trabalho Prático — Funções e Ponteiros em C

![Linguagem](https://img.shields.io/badge/C-00599C?style=flat-square\&logo=c\&logoColor=white)
![Projeto](https://img.shields.io/badge/Projeto-Acadêmico-blueviolet?style=flat-square)
![Conteúdo](https://img.shields.io/badge/Conteúdo-Funções%20e%20Ponteiros-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-green?style=flat-square)

Projeto desenvolvido com o objetivo de aplicar, na prática, os conceitos de **funções, ponteiros e modularização na linguagem C**.

O sistema consiste em um **cadastro de personagens**, permitindo realizar operações de criação, consulta, atualização e exclusão de registros, além de gerar estatísticas relacionadas aos níveis dos personagens.

## 📌 Funcionalidades

O sistema permite:

* Cadastrar personagens;
* Listar todos os personagens cadastrados;
* Atualizar informações de um personagem;
* Excluir personagens;
* Consultar o personagem de maior nível;
* Consultar o personagem de menor nível;
* Calcular a média dos níveis cadastrados.

Essas operações representam um CRUD:

* **Create** — criação de personagens;
* **Read** — consulta e listagem;
* **Update** — atualização;
* **Delete** — exclusão.

## 📂 Estrutura do Projeto

```text
.
├── Persomain.c
├── Persofunc.c
├── Prototipos.h
└── README.md
```

### `Prototipos.h`

Arquivo responsável por armazenar as **constantes e os protótipos das funções** utilizadas pelo programa.

Sua utilização permite uma melhor organização e modularização do código.

### `Persomain.c`

Arquivo principal do programa.

Contém a função `main()` e é responsável por:

* Exibir o menu;
* Receber as opções do usuário;
* Controlar o fluxo principal do programa;
* Chamar as funções necessárias.

### `Persofunc.c`

Arquivo responsável pela implementação das funções declaradas em `Prototipos.h`.

Entre elas estão:

* Cadastro de personagens;
* Listagem;
* Atualização;
* Exclusão;
* Cálculo do maior nível;
* Cálculo do menor nível;
* Cálculo da média dos níveis.

## 🧠 Conceitos Aplicados

Durante o desenvolvimento foram utilizados conceitos importantes da linguagem C, como:

* Funções;
* Ponteiros;
* Estruturas;
* Passagem de parâmetros;
* Arquivos de cabeçalho (`.h`);
* Modularização;
* Manipulação de dados;
* Organização de código.

## 🚀 Como Compilar

Abra o terminal e navegue até a pasta onde estão os arquivos do projeto.

Você pode verificar os arquivos utilizando:

```bash
ls
```

Compile o programa com:

```bash
gcc Persomain.c Persofunc.c -o Tes
```

## ▶️ Como Executar

Após a compilação:

```bash
./Tes
```

## 🖥️ Demonstração

### Menu principal

Menu contendo as funcionalidades disponíveis no sistema.

<img width="1920" height="1080" alt="Menu principal" src="https://github.com/user-attachments/assets/17f0320b-c720-4677-9b5d-88a8f583ac55" />

---

### Cadastro de personagens

Exemplo após acessar a opção de criação e cadastrar dois personagens.

<img width="1920" height="1080" alt="Cadastro de personagens" src="https://github.com/user-attachments/assets/719a54d6-2809-45f5-b08d-37d06382e8f5" />

---

### Listagem de personagens

Exibição de todos os personagens cadastrados no sistema.

<img width="1920" height="1080" alt="Lista de personagens" src="https://github.com/user-attachments/assets/c6465157-fe21-4fb5-864d-5245b544bf6f" />

---

### Atualização de personagem

Tela de atualização mostrando os dados anteriores e as novas informações do personagem.

<img width="1920" height="1080" alt="Atualização de personagem" src="https://github.com/user-attachments/assets/20b969b9-a6d0-4b08-a44e-f2fe919415de" />

---

### Estatísticas

Exibição das estatísticas relacionadas aos níveis dos personagens cadastrados.

<img width="1920" height="1080" alt="Estatísticas dos personagens" src="https://github.com/user-attachments/assets/5a634469-4829-4bfb-adab-a8f9370855f2" />

## 🎯 Objetivo Acadêmico

O objetivo do trabalho foi desenvolver, em equipe, um projeto utilizando **funções e ponteiros de forma explícita e correta**, aplicando os conceitos estudados na disciplina de **Estrutura de Dados**.

O projeto também contribuiu para a prática de modularização, separando as declarações, implementações e fluxo principal do programa em arquivos diferentes.

## 🛠️ Tecnologias

* C
* GCC
* Git
* GitHub

## 📚 Projeto Acadêmico

Este projeto foi desenvolvido para fins educacionais durante os estudos de **Estrutura de Dados**.
