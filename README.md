# Analisador e Reparador de CPF

Uma ferramenta web leve, segura e responsiva desenvolvida para validação, geração e recuperação de dígitos faltantes em números de CPF (Cadastro de Pessoas Físicas). 

O projeto foi concebido para oferecer uma interface moderna e funcional, processando todas as operações matemáticas diretamente no navegador do usuário, o que garante total privacidade e rapidez.

## 🚀 Acesse Agora
A aplicação está disponível para uso imediato via GitHub Pages:
**[https://marciliobr.github.io/reparador-cpf/](https://marciliobr.github.io/reparador-cpf/)**

## Principais Funcionalidades

* **Validação Algorítmica:** Verifica a autenticidade matemática de um CPF com base no cálculo oficial de dígitos verificadores (Módulo 11).
* **Recuperação de Dados (Curingas):** Permite a inserção do caractere `?` em posições desconhecidas do documento. O sistema calcula e exibe todas as combinações numericamente válidas.
* **Sugestão de Correção Automática:** Caso um CPF inválido seja inserido, a ferramenta analisa variações próximas (alterando um dígito por vez) para sugerir a correção mais provável.
* **Gerador para Testes:** Funcionalidade de geração de números de CPF válidos para auxiliar desenvolvedores e testadores de software.
* **Interface Adaptável:** Suporte nativo a temas claro e escuro (Dark Mode), respeitando a preferência do sistema operacional ou escolha manual do usuário através da interface.

## Segurança e Privacidade

Este projeto prioriza a segurança e o anonimato dos dados:
* **Processamento Local (Client-side):** Nenhuma informação digitada é enviada a servidores externos ou armazenada em bancos de dados. Todo o cálculo é feito pelo motor de JavaScript do seu navegador.
* **Zero Dependências:** Construído inteiramente em Vanilla JavaScript, HTML5 e CSS3, sem o uso de bibliotecas de terceiros, frameworks pesados ou rastreadores.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível.
* **CSS3:** Design responsivo com uso de CSS Variables para gerenciamento dinâmico de temas.
* **JavaScript (ES6+):** Lógica de processamento para análise de combinações e manipulação eficiente do DOM.

## Como rodar o projeto localmente

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/marciliobr/reparador-cpf.git](https://github.com/marciliobr/reparador-cpf.git)
