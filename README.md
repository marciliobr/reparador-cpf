# Analisador e Reparador de CPF

Uma ferramenta web leve e segura desenvolvida para validação, geração e recuperação de dígitos faltantes em números de CPF (Cadastro de Pessoas Físicas). 

O projeto foi concebido para oferecer uma interface moderna e funcional, processando todas as operações matematicas diretamente no navegador do usuário, o que garante total privacidade e rapidez.

## Principais Funcionalidades

* **Validação Algorítmica:** Verifica a autenticidade matemática de um CPF com base no cálculo de dígitos verificadores (Módulo 11).
* **Recuperação de Dados (Curingas):** Permite a inserção do caractere `?` em posições desconhecidas do documento. O sistema calcula e exibe todas as combinações numericamente válidas.
* **Sugestão de Correção Automática:** Caso um CPF inválido seja inserido, a ferramenta analisa variações próximas (alterando um dígito por vez) para sugerir a correção mais provável.
* **Gerador para Testes:** Funcionalidade de geração de números de CPF válidos para auxiliar desenvolvedores em testes de software.
* **Interface Adaptável:** Suporte nativo a temas claro e escuro (Dark Mode), respeitando a preferência do sistema operacional ou escolha manual do usuário.

## Segurança e Privacidade

Este projeto prioriza a segurança dos dados do usuário:
* **Processamento Local:** Nenhuma informação digitada é enviada a servidores externos ou armazenada em bancos de dados.
* **Zero Dependências:** Construído inteiramente em Vanilla JavaScript, HTML5 e CSS3, sem o uso de bibliotecas de terceiros ou rastreadores.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da aplicação.
* **CSS3:** Design responsivo com uso de CSS Variables para gerenciamento de temas.
* **JavaScript (ES6+):** Lógica de processamento assíncrono para análise de combinações e manipulação de DOM.

## Como Utilizar

1. Faça o clone deste repositório:
   ```bash
https://github.com/marciliobr/reparador-cpf.git
