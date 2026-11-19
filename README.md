# Mundo do voleibol

- **Tema:** Vôlei (posições, história, fundamentos e escolinha)
- **Estudante:** Breno Ricardo Salles Lopes
- **Turma:** DS25 M3
- **Unidade curricular:** Programação de Aplicativos — Curso Técnico em Desenvolvimento de Sistemas (Integrado ao Ensino Médio)

## Descrição

Site de cinco páginas sobre vôlei, feito apenas com HTML (sem CSS). Apresenta o esporte, as posições em quadra (levantador, central, ponteiro, oposto e líbero), uma tabela de dados com as finais olímpicas do Brasil, um formulário de inscrição em uma escolinha fictícia e uma página de contato.

## Como abrir o projeto

1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` em qualquer navegador (duplo clique).
3. Navegue pelo menu entre as páginas.

## Páginas

| Arquivo | Descrição |
|---|---|
| `index.html` | Início: apresenta o esporte, fundamentos, equipamentos e galeria. |
| `sobre.html` | Sobre: história, posições em quadra, curiosidade, glossário e fontes externas. |
| `dados.html` | Dados: tabela das finais olímpicas do Brasil no vôlei de quadra. |
| `cadastro.html` | Cadastro: formulário de pré-inscrição na escolinha de vôlei. |
| `contato.html` | Contato: endereço fictício, horários, mapa e formulário de mensagem. |

## Acessibilidade

- Idioma `pt-BR` declarado em todas as páginas.
- Link "Pular para o conteúdo" como primeiro elemento do `<body>`.
- `aria-current="page"` no menu da página atual e `aria-label` no `<nav>`.
- Texto alternativo descritivo nas imagens informativas e `alt=""` na decorativa.
- Todos os campos de formulário com `<label>` associado, `fieldset` e `legend`.
- Hierarquia de títulos sem saltos de nível.

### Teste de teclado (Tab)




## Fontes consultadas

> PREENCHER com as páginas que você realmente consultou para conferir os textos e os dados (ex.: site da CBV, Volleyball World, COI, MDN Web Docs), com nome e endereço.

## Decisões de semântica

- `<section>`: blocos temáticos da página, cada um com seu `<h2>` (ex.: fundamentos, equipamentos, glossário).
- `<article>`: conteúdos que fazem sentido sozinhos — "História do vôlei" e "Posições em quadra".
- `<aside>`: a curiosidade sobre a altura da rede, que complementa o texto sem fazer parte dele.

## Dificuldades encontradas

> PREENCHER com as dificuldades que você teve e como resolveu (ex.: validação do formulário, tabela com scope, etc.).
