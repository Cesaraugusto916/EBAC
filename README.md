# Curso de Análise de Dados - EBAC

Este repositório reúne os projetos desenvolvidos durante os módulos do curso **Profissão: Analista de Dados** da EBAC.

## 📌 Projeto 1: Calculadora em Python

### 📝 Descrição Geral e Funcionalidades

O script `proj01EBAC.py` implementa uma **calculadora simples** que demonstra conceitos fundamentais de entrada e saída de dados, controle de fluxo e validação de operações em Python.

### 🔹 Funcionalidades Principais

- **Entrada de Dados pelo Usuário:** Solicita o nome do usuário e dois números inteiros.
- **Escolha da Operação Matemática:** Permite ao usuário selecionar entre **adição, subtração, multiplicação e divisão**.
- **Processamento da Operação:** Realiza o cálculo e exibe o resultado, tratando erros como **divisão por zero**.
- **Encerramento da Execução:** Aguarda interação do usuário antes de finalizar o programa.

### 🔹 Características Técnicas

- **Interação com o Usuário:** Utiliza `input()` para entrada de dados e `print()` para exibição dos resultados.
- **Controle de Fluxo:** Estruturado com `if`, `elif` e `else` para tomada de decisão baseada na entrada do usuário.
- **Tratamento de Erros:** Implementa verificação para **evitar divisão por zero** e operações inválidas.
- **Código Simples e Intuitivo:** Estruturado para **fácil compreensão e manutenção**.

---

## 📌 Projeto 2: Script para Execução da Calculadora

### 📝 Descrição Geral

Este projeto complementa o **Projeto 1**, fornecendo um método automatizado para executar a calculadora via **Shell Script**.

### 📂 Estrutura de Arquivos

- **`comandos.txt`** – Contém instruções sobre permissões e execução do script.
- **`calculadora.sh`** – Script em Shell que inicia a execução do código Python.

### ⚙️ Configuração e Execução

#### 1️⃣ **Seguir as instruções do `comandos.txt`**
   - Abra o terminal e navegue até a pasta do projeto:  
     ```bash
     cd caminho/para/proj02
     ```
   - Leia as instruções contidas no arquivo:  
     ```bash
     cat comandos.txt
     ```
   - Siga os passos descritos para conceder as permissões necessárias.

#### 2️⃣ **Executar o `calculadora.sh`**
   - Após configurar as permissões, execute o script com:  
     ```bash
     ./calculadora.sh
     ```
   - Se todas as etapas forem seguidas corretamente, o script **iniciará a calculadora Python** e exibirá o status da execução no terminal.

---

Este **README** foi elaborado para documentar os projetos de forma clara e organizada, demonstrando o aprendizado adquirido.  

Se tiver dúvidas ou sugestões, fique à vontade para contribuir!  

Atenciosamente,  
**César Augusto**
