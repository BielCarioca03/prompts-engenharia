# 02 · Relatório técnico em LaTeX (ABNT)

**Objetivo:** transformar anotações, dados e resultados de uma prática de laboratório em um relatório LaTeX organizado e no padrão ABNT.
**Quando uso:** relatórios das disciplinas de Controle e Instalações Prediais e memoriais de cálculo.

## Prompt

```
Você é um engenheiro eletricista experiente em redação técnica e LaTeX.
Vou te passar as anotações de uma prática de laboratório. Monte o relatório em LaTeX.

Disciplina: {disciplina}
Título da prática: {título}
Objetivo da prática: {objetivo}
Anotações, dados e resultados (podem estar desorganizados):
"""
{cole aqui}
"""

Estrutura obrigatória:
1. Introdução (contexto teórico breve, com as equações relevantes)
2. Objetivos
3. Materiais e métodos
4. Resultados (tabelas com \begin{table} e figuras com \begin{figure} e legenda)
5. Discussão (compare resultados obtidos e teóricos e explique as diferenças)
6. Conclusão
7. Referências no padrão ABNT

Regras:
- Use apenas os dados que eu forneci. Se faltar algum dado, deixe um comentário % TODO no lugar, não invente.
- Equações numeradas com \begin{equation} e referenciadas no texto com \eqref.
- Escreva em português formal, na terceira pessoa.
- Entregue um único arquivo .tex que compile no Overleaf.
```

## Resultado

<!-- Adicione aqui um print do PDF compilado (pode borrar dados que não quiser mostrar). -->
