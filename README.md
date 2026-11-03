
# Projeto Final: Carteira de Investimentos Digitais

## 1. Descrição do Projeto

O projeto consiste no desenvolvimento de um sistema de controle de carteira de investimentos, executado diretamente no terminal. A aplicação tem como objetivo permitir que os usuários cadastrem, organizem e acompanhem seus investimentos, oferecendo funcionalidades como consulta de ativos, cálculo de rentabilidade, ordenação dos investimentos por desempenho e armazenamento dos dados em arquivos de texto. Além disso, o sistema contará com um modo educativo, buscando facilitar a compreensão de conceitos básicos do mercado financeiro e incentivar a inclusão financeira. O objetivo é oferecer uma ferramenta simples e acessível para pessoas que desejam conhecer melhor o funcionamento dos investimentos, alinhando-se ao **Objetivo de Desenvolvimento Sustentável** (ODS 8.10) da ONU.

## 2. Público-alvo

O sistema é destinado principalmente a pessoas que desejam começar a investir, mas possuem pouco conhecimento sobre o mercado financeiro e suas possibilidades. O público-alvo inclui estudantes, jovens adultos e investidores iniciantes que buscam compreender conceitos como rentabilidade, organização de ativos e acompanhamento de investimentos. Por meio de uma interface simples, a aplicação pretende facilitar o aprendizado e oferecer um ambiente de simulação acessível, permitindo que os usuários desenvolvam maior familiaridade com o mercado financeiro sem a barreira inicial do mercado financeiro.

## 3. Funcionalidades

O sistema contará com funcionalidades voltadas ao controle e acompanhamento de uma carteira de investimentos, buscando oferecer uma experiência simples e acessível aos usuários. Entre as principais funcionalidades previstas, estão:

* **Cadastro de investimentos**: Permitir que o usuário registre diferentes ativos financeiros, informando seus respectivos valores e dados necessários para o acompanhamento.

* **Consulta de investimentos**: Possibilitar a visualização dos ativos cadastrados, apresentando suas informações de maneira organizada.

* **Cálculo de rentabilidade**: Calcular e apresentar o rendimento dos investimentos, permitindo que o usuário acompanhe o desempenho de sua carteira.

* **Ordenação por rentabilidade**: Organizar os ativos de acordo com seus resultados, facilitando a identificação e comparação dos investimentos mais rentáveis.

* **Armazenamento de dados**: Salvar e recuperar as informações da carteira por meio de arquivos de texto, permitindo que os dados sejam mantidos entre diferentes execuções do programa.

* **Modo educativo**: Disponibilizar explicações sobre conceitos básicos do mercado financeiro, auxiliando usuários iniciantes na compreensão dos investimentos e de seus principais indicadores.

## 4. Tecnologias Utilizadas

* Linguagem C: Utilizada para o desenvolvimento do sistema, empregando estruturas de dados (_struct_), algoritmos de ordenação (_Bubble Sort_) e funções de manipulação de arquivos .txt para garantir a persistência dos dados.

* Visual Studio Code: Ambiente de desenvolvimento utilizado para a escrita, organização e manutenção do código-fonte do projeto.

## 5. Requisitos Mínimos

Para executar o sistema, é necessário possuir um computador com um **compilador de linguagem C** instalado, como o GCC, permitindo a compilação e execução do código-fonte diretamente pelo terminal.

## 6. Instruções para Execução

Para executar o projeto, certifique-se de possuir um compilador C, como o GCC, instalado e configurado em seu computador.

1. Clone o repositório:

    git clone https://github.com/bagsharu/projeto-carteira-digital

2. Acesse a pasta do projeto:

    cd projeto-carteira-digital

3. Compile os arquivos utilizando o GCC:

    gcc src/main.c src/funcoes.c src/modulo.c -Iinclude -o carteira.exe

4. Execute o programa pelo terminal:

    .\carteira.exe

## 7. Desenvolvedores

Bruna da Silva Sant'Ana e Gabriel Ortega Vieira
