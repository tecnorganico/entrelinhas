# Traduções e adaptação cultural

O objetivo é tornar o baralho útil em diferentes idiomas sem tratar tradução como simples troca de palavras. Sentimentos e necessidades carregam contexto cultural, ritmo e nuances próprias.

## Propondo um idioma

1. Abra uma issue com o idioma e a variante desejada, por exemplo `es-AR`, `en-US` ou `pt-PT`.
2. Indique uma pessoa revisora com fluência no idioma e, idealmente, familiaridade com CNV.
3. Combine o escopo da primeira versão: interface, cartas, exemplos, documentação ou tudo.
4. Faça a tradução em uma branch ou pull request separada das mudanças de layout.

## Critérios de qualidade

- Preserve intenção e tom acolhedor, em vez de traduzir palavra por palavra.
- Mantenha a diferença entre sentimento, necessidade, estratégia e julgamento.
- Considere termos que não tenham equivalente direto; inclua uma nota de decisão quando necessário.
- Traduza também botão, busca, mensagens vazias, modal, perguntas e documentação visível.
- Não altere a lista em português ao traduzir; cada idioma deve poder ser revisado separadamente.

## Arquitetura sugerida

Hoje, o conteúdo está concentrado em `baralho-cnv.html`. A primeira contribuição de idioma pode extrair textos para uma estrutura como esta, ainda no mesmo arquivo:

```js
const locales = {
  'pt-BR': { ui: {}, cards: {} },
  'es': { ui: {}, cards: {} }
};
```

O seletor de idioma deve funcionar sem rede e guardar a escolha somente no navegador da pessoa, se houver consentimento para isso.

## Créditos

Todo pull request de tradução deve incluir créditos de tradução e revisão no texto da proposta. Não publique dados pessoais sem consentimento.
