# Entrelinhas - Baralho de Sentimentos e Necessidades

Um baralho digital, mobile-first e acessível para apoiar a nomeação de sentimentos e necessidades a partir da Comunicação Não Violenta (CNV).

O projeto convida a pessoa a pausar, perceber o que está vivo e encontrar palavras para seguir com mais cuidado. Não substitui apoio profissional, terapia ou atendimento em situação de crise.

## O que já existe

- 202 cartas de sentimentos e necessidades organizadas a partir do vocabulário-base do material de referência enviado pelo Instituto CNV Brasil.
- Busca, filtros por tipo e sorteio de carta.
- Detalhe de cada carta com definição, contextos possíveis e pergunta de reflexão.
- Interface responsiva, em modo escuro, com sentimentos em vermelho e necessidades em verde.
- Sem dependências, build ou servidor: o projeto roda em um único arquivo HTML.

## Rodar localmente

Baixe ou clone o repositório e abra `baralho-cnv.html` em qualquer navegador moderno.

Para desenvolver com recarregamento local, use um servidor estático simples:

```bash
python3 -m http.server 4173
```

Depois, acesse `http://localhost:4173/baralho-cnv.html`.

## Estrutura

```text
baralho-cnv.html       # Aplicação inteira: HTML, CSS, conteúdo e JavaScript
README.md              # Visão do projeto
CONTRIBUTING.md        # Como propor alterações
TRANSLATIONS.md        # Processo para novos idiomas
CODE_OF_CONDUCT.md     # Acordos de convivência
```

## Visão do projeto

Queremos que este seja um recurso livre, gentil e útil para conversas consigo, em grupo, em práticas de CNV e em contextos educativos. A tecnologia deve continuar simples: leve, legível no celular, navegável por teclado e possível de adaptar por pessoas não técnicas.

Princípios de produto:

- **Humanidade antes de prescrição:** cartas são pistas, não rótulos ou diagnósticos.
- **Acesso antes de complexidade:** uma página, sem conta, sem rastreamento e sem dependências.
- **Escuta antes de certeza:** definições e exemplos usam linguagem de possibilidade.
- **Colaboração responsável:** mudanças de conteúdo devem respeitar a CNV, o contexto cultural e a origem das fontes.

## Próximos passos bem-vindos

- Revisar definições e exemplos de contexto com pessoas facilitadoras de CNV.
- Criar uma arquitetura de idiomas sem perder o formato single-file.
- Melhorar contraste, leitores de tela e navegação por teclado.
- Incluir modos de uso em grupos, favoritos locais e impressão de cartas.
- Adicionar testes leves para busca, filtros, modal e dados das cartas.

## Conteúdo e atribuição

O vocabulário-base foi organizado a partir de material do Instituto CNV Brasil fornecido como referência para este protótipo. Antes de redistribuir, publicar traduções ou licenciar o conteúdo das cartas, confira permissões, atribuição e eventuais limites de uso da fonte.

O código do projeto e o conteúdo das cartas podem ter licenças diferentes. A escolha de licença ainda deve ser registrada no repositório antes da primeira publicação pública.

## Como colaborar

Leia [CONTRIBUTING.md](CONTRIBUTING.md) para propor correções, novas cartas, melhorias visuais ou recursos. Para colaborar com outro idioma, siga [TRANSLATIONS.md](TRANSLATIONS.md).

Ao participar, você concorda com o [Código de Conduta](CODE_OF_CONDUCT.md).
