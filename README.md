# Prompts de Engenharia

Biblioteca de prompts que uso no dia a dia como estudante de Engenharia Elétrica e pesquisador de firmware embarcado.
Cada prompt resolve uma tarefa real e repetitiva, e está escrito para ser reaproveitado: basta preencher as variáveis entre `{chaves}`.

## Por que este repositório existe

Percebi que repetia as mesmas instruções para a IA toda vez que precisava estudar um tema, escrever um relatório ou revisar código C.
Organizar esses prompts em modelos me fez gastar menos tempo explicando o contexto e obter respostas mais consistentes.

## Prompts

| # | Prompt | Para que serve |
|---|---|---|
| 01 | [Ferramenta de estudo interativa](prompts/01-ferramenta-estudo-interativa.md) | Gerar uma página HTML interativa que explica um tema de engenharia com simulação visual |
| 02 | [Relatório técnico em LaTeX (ABNT)](prompts/02-relatorio-latex-abnt.md) | Transformar dados e anotações de laboratório em um relatório LaTeX formatado |
| 03 | [Depuração de firmware embarcado](prompts/03-depuracao-firmware-c.md) | Investigar bugs em firmware C para STM32 de forma metódica, camada por camada |
| 04 | [Documentação Doxygen](prompts/04-documentacao-doxygen.md) | Documentar arquivos de cabeçalho C no padrão Doxygen |
| 05 | [Triagem de vagas de estágio](prompts/05-triagem-vagas.md) | Avaliar se uma vaga é compatível com o meu perfil e preparar a candidatura |

## Técnicas usadas

- **Papel e contexto:** cada prompt define quem a IA deve ser e qual é o meu nível de conhecimento.
- **Variáveis:** campos `{assim}` deixam o prompt reaproveitável.
- **Formato de saída explícito:** digo exatamente como quero a resposta (tabela, código, seções).
- **Restrições:** limites do que a IA não deve fazer (inventar dados, mudar o que funciona, etc.).
- **Raciocínio em etapas:** nos prompts de análise, peço hipóteses antes da conclusão.

## Como usar

1. Abra o prompt desejado.
2. Copie o bloco do prompt e substitua as variáveis `{...}`.
3. Cole no Claude, ChatGPT ou Gemini.
