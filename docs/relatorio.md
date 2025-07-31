# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo

* Nome do projeto: receitas-grupoX
* Integrantes:

1. Miguel Gaspar

* Repositório: \[https://github.com/miguelgaspar17/receitas-grupoX]

## Branches Criadas

* Descreva as branches criadas e o objetivo de cada uma.

1. "main": branch principal
2. "miguel": branch criada por Miguel para realizar as atividades localmente
3. "receita": utilizada para criar e versionar o ficheiro "receita1.md"


* Informe como os merges foram realizados (com PR? Revisão?).

1. A branch "miguel" será integrada à "main" através de um Pull Request.
2. Todo o trabalho foi feito na branch "miguel", com commits claros e organizados.

## Histórico de Commits

* Exemplo de boas mensagens de commit.

1. "Adiciona ficheiro index.html com HTML básico"
2. "Adiciona ficheiro teste.txt com conteúdo de teste"
3. "Remove ficheiro teste.txt"
4. "Corrige submódulo: adiciona projeto-teste como pasta normal"

* Print ou link do gráfico de contribuições.

1. https://github.com/miguelgaspar17/receitas-grupoX/graphs/contributors

## Issues Criadas

Liste as issues criadas e quem ficou responsável por cada uma.

- Issue #1: Criar uma receita simples em Markdown
  - Resolvida pelo Pull Request #8

## Pull Requests

Um Pull Request foi criado para integrar a branch "miguel" na "main", com descrição detalhada das mudanças.

Este processo simula o fluxo de colaboração com revisão entre colegas.

## Conflitos e Resoluções

Não houve conflitos de merge, mas houve um problema técnico com um \*\*sub-repositório Git aninhado\*\*, que foi resolvido com:

```bash

rm -rf projeto-teste/.git

git rm --cached projeto-teste

git add projeto-teste

git commit -m "Corrige submódulo: adiciona projeto-teste como pasta normal"

## Dificuldades Enfrentadas

Dúvidas ou problemas que surgiram.

1. Mensagens estranhas no terminal Git Bash ao usar !DOCTYPE, resolvidas com aspas simples.
2. Criação acidental de um repositório Git dentro de outro (projeto-teste), resolvida como descrito acima.
3. Aprendizado prático sobre submódulos e estrutura de repositórios.

## Principais Comandos Git Utilizados

Liste e comente comandos importantes usados no projeto.

\* git init — inicializar repositório local
\* git add — adicionar ficheiros ao staging
\* git commit -m — guardar alterações com mensagem
\* git status — verificar o estado dos ficheiros
\* git diff — comparar mudanças
\* git log — consultar histórico de commits
\* git restore — desfazer alterações
\* git checkout -b — criar nova branch
\* git push origin <branch> — enviar branch para o GitHub
\* git rm --cached — remover ficheiro do index sem apagar localmente

## Conclusão

Aprendizados principais do grupo com a atividade.

\* A atividade permitiu compreender e aplicar os fundamentos de Git, incluindo staging, commits, branches, merges, resolução de problemas técnicos e uso do GitHub.
\* Mesmo em trabalho individual, foram simuladas práticas reais de colaboração.

