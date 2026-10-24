# Aulas Fullstack

Exercícios de JavaScript no navegador feitos nas aulas da disciplina de Programação Web Fullstack. Cada exercício é uma página HTML independente, com o CSS e o JavaScript no próprio arquivo.

## Conteúdo

### Aula 01

- `dom.html` - manipulação do DOM: altera título e cabeçalho, calcula dias desde 1º de maio, mostra elementos ocultos, transforma a lista de disciplinas (minúsculas, cores por período, aulas por semana), soma a carga horária e gera listas em ordem alfabética, decrescente e só com disciplinas de programação
- `eventos.html` - dez exercícios de eventos: cliques que mudam cor, visibilidade, posição e texto de elementos, criação de itens de lista, leitura de inputs com `alert`, atualização com `keyup` e movimentação de um quadrado com as setas do teclado (`tabindex` + `keydown`)
- `viacep.html` - formulário de endereço com Bootstrap que preenche rua, bairro, cidade, UF e código IBGE ao sair do campo de CEP, consultando a API ViaCEP

### Aula 02

- `index.html` - formulário de registro de aluno com quatro notas e cálculo da média em tempo real; ao enviar, salva nome e média no `localStorage`
- `resultado.html` - lê os dados salvos e mostra a situação: aprovado (média >= 6), exame (média >= 2) ou reprovado, com botão para voltar e limpar os dados

## Tecnologias

- HTML5 e CSS3
- JavaScript puro (DOM, eventos, `fetch`, `localStorage`)
- Bootstrap 5 via CDN (apenas no exercício do ViaCEP)
- API ViaCEP

## Como rodar

Não há dependências nem etapa de build: abra o arquivo HTML desejado no navegador. Na aula 02, comece pelo `index.html`. O exercício do ViaCEP precisa de conexão com a internet.

## Contexto

Atividades da disciplina de Programação Web Fullstack da faculdade (UTFPR).
