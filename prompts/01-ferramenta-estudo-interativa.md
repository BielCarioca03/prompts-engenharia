# 01 · Ferramenta de estudo interativa

**Objetivo:** gerar uma página HTML única e interativa que explica um tema de engenharia com visualizações que respondem a parâmetros ajustáveis.
**Quando uso:** ao estudar temas abstratos (Transformada de Laplace, Transformada Z, sistemas lineares, fluxo de carga), em que mexer nos parâmetros e ver o efeito ajuda mais que ler.

## Prompt

```
Você é um professor de Engenharia Elétrica e desenvolvedor front-end.
Crie uma página HTML única (HTML, CSS e JavaScript no mesmo arquivo, sem dependências externas)
que me ensine o tema: {tema}.

Meu nível: {ex.: aluno do 6º semestre, já vi a teoria mas não tenho intuição}.

A página deve ter:
1. Uma explicação curta do conceito (no máximo 3 parágrafos).
2. Uma simulação interativa com controles deslizantes para {parâmetros, ex.: posição dos polos, frequência de amostragem}
   e um gráfico que se atualiza em tempo real.
3. Uma seção "O que observar" com 3 experimentos guiados ("arraste X até Y e repare em Z").
4. Um quiz de 3 perguntas com correção imediata.

Estilo visual: tema escuro inspirado em osciloscópio (fundo preto, traços âmbar e verdes, fonte monoespaçada).

Restrições:
- As fórmulas e os resultados numéricos precisam estar corretos; se houver aproximação, avise na página.
- Não use bibliotecas externas nem CDN.
- Comente o JavaScript explicando o cálculo principal.
```

## Variáveis

| Variável | Exemplo |
|---|---|
| `{tema}` | Transformada Z e estabilidade de sistemas discretos |
| `{parâmetros}` | posição dos polos no plano z, período de amostragem |

## Resultado

<!-- Adicione aqui um print da página gerada e, se publicar, o link. -->
