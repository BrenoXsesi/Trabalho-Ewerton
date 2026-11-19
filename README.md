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



## Fontes consultadas
Site da CBV: (https://cbv.com.br/)
Site da Netshoes: (https://www.netshoes.com.br/especiais/volei/praticas-de-volei-vol/regras-volei-vol-prat/como-jogar-volei-guia-completo-para-aprender-a-praticar-o-esporte?srsltid=AYCX9vLSBsovL43Vsm_LVk8IJLGxAjHc-YKgZ5wHTCgvlWkuqXxp3Vol)

Site da historia do volei: (https://www.todamateria.com.br/historia-do-voleibol/)

Dados de titulos: (https://www.netshoes.com.br/especiais/volei/competicoes-internacionais-vol/jogos-olimpicos-volei-praia-vol-com/volei-masculino-nas-olimpiadas?srsltid=AYCX9vIGh19r067BnXGhnHjDlCw7zh7KyrNG556jq7Ea9yKKrbysbbTS)



## Decisões de semântica

- `<section>`: blocos temáticos da página, cada um com seu `<h2>` (ex.: fundamentos, equipamentos, glossário).
- `<article>`: conteúdos que fazem sentido sozinhos — "História do vôlei" e "Posições em quadra".
- `<aside>`: a curiosidade sobre a altura da rede, que complementa o texto sem fazer parte dele.

## Dificuldades encontradas

Nas tabelas e em campos de preencher
