# 🚗 Sistema de Gerenciamento de Concessionária

![Status do Projeto](https://img.shields.io/badge/Status-Finalizado-brightgreen)
![Linguagem](https://img.shields.io/badge/Linguagem-C-blue)
![UFS](https://img.shields.io/badge/Instituição-UFS-red)

## 👩‍💻 Equipe Responsável
* **Sibele Oliveira**

---

## 📝 Sobre o Projeto
Este é um sistema robusto de gerenciamento para uma concessionária de veículos, desenvolvido em **C** e executado via console. O projeto foi concebido para gerenciar desde o fluxo de chegada de clientes até o desempenho detalhado de vendas por vendedor, permitindo um controle administrativo completo de faturamento e metas.

O objetivo primordial deste trabalho é a aplicação prática de **Estruturas de Dados Dinâmicas e Estáticas**, demonstrando como diferentes tipos de organização de dados resolvem problemas específicos de logística e armazenamento em software.

O projeto foi desenvolvido para a disciplina de **Estrutura de Dados**, ministrada pelo **Prof. Dr. Gilton José Ferreira da Silva** no Departamento de Computação (DCOMP) da Universidade Federal de Sergipe (UFS).

---

## ✨ Funcionalidades Principais

* **Gestão de Vendedores:** Cadastro e remoção dinâmica de vendedores.
* **Controle de Vendas:** Registro de vendas (veículo, marca, valor, nota fiscal) vinculado ao vendedor.
* **Fluxo de Atendimento:** Gerenciamento de fila de espera para clientes (ordem de chegada).
* **Relatórios de Desempenho:**
    * Cálculo de faturamento por vendedor e global.
    * Identificação do "Vendedor Destaque" (mais lucrativo).
    * Busca filtrada de vendas por marca.
* **Histórico (Log):** Registro de auditoria das ações realizadas no sistema.
* **Monitoramento de Metas:** Exibição de metas trimestrais fixas.

---

## 🏗️ Estruturas de Dados Utilizadas

A arquitetura do sistema utiliza conceitos fundamentais para otimizar cada processo:

| Estrutura | Aplicação | Motivação |
| :--- | :--- | :--- |
| **Lista Circular Simples** | Vendedores | Permite navegação contínua e percursos de busca eficientes. |
| **Lista Duplamente Encadeada** | Vendas | Garante integridade no rastro de transações e flexibilidade de navegação. |
| **Fila (FIFO)** | Clientes | Respeita a ordem de chegada (*First-In, First-Out*). |
| **Pilha (LIFO)** | Log de Ações | Permite que as ações mais recentes sejam visualizadas primeiro. |
| **Arrays Estáticos** | Relatório de Metas | Ideal para dados constantes e pré-definidos. |

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter um compilador C (como o `gcc`) instalado em sua máquina.

### Passo a Passo

1. **Clone o repositório:**
     ```bash
     git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
2. **Navegue até a pasta do projeto:**
    ```bash
     cd nome-do-repositorio
2. **Compile o código:**
    ```bash
    gcc main.c -o concessionaria
3. **Execute o programa:**
    ```bash
    ./concessionaria
## 🎓 Créditos
Este projeto é uma atividade acadêmica vinculada ao Departamento de Computação (DCOMP) da Universidade Federal de Sergipe (UFS).
Orientador: Prof. Dr. Gilton José Ferreira da Silva.
