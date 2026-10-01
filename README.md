# Gerador de Crachá Virtual

## Objetivo

O programa pede ao utilizador o nome, o sobrenome, o ano de nascimento e se é aluno ativo da instituição. Com esses dados, gera um "crachá virtual" no console do navegador.

## Como funciona

1. prompt() recolhe o nome, o sobrenome e o ano de nascimento.
2. confirm() pergunta se o utilizador é aluno ativo.
3. Number() converte o ano de nascimento (texto) para número.
4. A idade estimada é calculada subtraindo o ano de nascimento ao ano atual.
5. .toUpperCase() coloca o sobrenome em maiúsculas.
6. .length conta as letras do primeiro nome.
7. console.log() apresenta o resultado final.

## Exemplo de saída na consola


CRACHÁ VIRTUAL: SILVA, Ana
Idade estimada: 26 anos.
O seu primeiro nome tem 3 letras.
Estatuto de aluno ativo: true


## Como executar

1. Clonar o repositório: git clone <URL-do-repositório>
2. Abrir o ficheiro index.html no navegador.
3. Responder às caixas de diálogo.
4. Abrir o console (**F12 → Console**) para ver o crachá.

## Fluxo de trabalho (Git e GitHub)

O projeto foi desenvolvido em grupo, com duas duplas e 2 Pull Requests:

- **Dupla A:** branch feature-coleta-dados, com a estrutura HTML5 e a recolha de dados.
- **Dupla B:** branch feature-geracao-cracha, com o processamento dos dados e a saída na consola.

## Autores

- Dupla A: Pedro Nazar e Bernardo Gurgel
- Dupla B: Lucas Matias e João Pedro
