# 04 · Documentação Doxygen

**Objetivo:** documentar arquivos de cabeçalho (.h) em C no padrão Doxygen, de forma consistente e sem alterar o código.
**Quando uso:** ao finalizar um módulo de firmware, antes de compartilhar com a equipe.

## Prompt

```
Você é um engenheiro de firmware que escreve documentação técnica clara.
Documente o arquivo de cabeçalho C abaixo no padrão Doxygen.

Projeto: {nome do projeto}
Idioma da documentação: {português ou inglês}
Arquivo:
"""
{cole o .h aqui}
"""

Regras:
1. Bloco @file no topo com @brief, descrição do módulo e @author {seu nome}.
2. Para cada função: @brief, @param[in]/@param[out]/@param[in,out] para cada parâmetro,
   @return com os valores possíveis e @note quando houver restrição (ex.: "não chamar dentro de ISR").
3. Para structs e enums: comentário em cada campo com ///<.
4. Para macros: @brief e unidade física quando houver (ex.: mV, ms, °C).
5. NÃO altere nenhuma linha de código, apenas acrescente comentários.
6. Se o propósito de algo não estiver claro pelo código, escreva "TODO: confirmar" em vez de adivinhar.

Entregue o arquivo completo documentado.
```

## Resultado

<!-- Adicione um print da página HTML gerada pelo Doxygen (de um módulo que possa ser mostrado). -->
