# Como contribuir

Obrigada por querer melhorar o Entrelinhas. São bem-vindas contribuições de conteúdo, acessibilidade, design, código, revisão linguística e tradução.

## Antes de abrir uma proposta

1. Confira se já existe uma issue ou pull request sobre o tema.
2. Em mudanças maiores, abra uma issue curta explicando o problema, a ideia e quem se beneficia.
3. Para alterações nas cartas, cite a fonte ou explique a experiência e o critério usados.

## Tipos de contribuição

- **Conteúdo:** definições, exemplos, perguntas de cuidado e organização das cartas.
- **Interface:** contraste, legibilidade, responsividade, movimentos e acessibilidade.
- **Código:** desempenho, busca, filtros, persistência local e testes.
- **Idiomas:** tradução e adaptação cultural. Veja `TRANSLATIONS.md`.
- **Documentação:** melhoria de guias, exemplos e instruções de uso.

## Alterando o baralho

O app inteiro está em `baralho-cnv.html`.

- `groups`: lista de cartas, por tipo e tema.
- `descriptions`: definições que merecem texto específico.
- `examples`: contextos possíveis para cada tema.
- `prompt`: pergunta de reflexão exibida no final da carta.
- CSS no início do arquivo: visual, responsividade e contraste.

Ao editar conteúdo, use linguagem de possibilidade: prefira “pode surgir quando” a afirmações universais sobre a experiência de uma pessoa.

## Checklist para um pull request

- [ ] A mudança tem uma descrição simples e objetiva.
- [ ] O site ainda funciona em tela estreita, especialmente perto de 390 px.
- [ ] Busca, filtros, sorteio e abertura/fechamento da carta continuam funcionando.
- [ ] O conteúdo evita julgamento, diagnóstico ou prescrição.
- [ ] A alteração respeita atribuições e permissões das fontes usadas.
- [ ] Se houver texto novo, a ortografia e a acessibilidade foram revisadas.

## Decisões de design

O modo escuro é intencional: reduz brilho no celular e sustenta a metáfora de olhar para o interior. A cor comunica o tipo de carta, não sua intensidade ou valor:

- vermelho: sentimentos;
- verde: necessidades;
- amarelo: foco, ação e navegação;
- preto e creme: fundo e leitura.

Evite introduzir cores sem função ou transformar a interface em um sistema de pontuação emocional.

## Licença e autoria

Não envie material de terceiros sem autorização. O repositório ainda precisa registrar uma licença para o código e definir, separadamente, como o conteúdo derivado de fontes de CNV pode ser reutilizado.
