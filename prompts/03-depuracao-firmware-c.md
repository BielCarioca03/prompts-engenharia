# 03 · Depuração de firmware embarcado

**Objetivo:** investigar um bug em firmware C para microcontroladores STM32 de forma metódica, levantando hipóteses em várias camadas antes de propor uma correção.
**Quando uso:** quando um comportamento do firmware diverge do esperado e a causa não é óbvia (ISR travando, clock errado, quadro de comunicação inconsistente).

## Prompt

```
Você é um engenheiro sênior de firmware embarcado, especialista em STM32 e HAL.
Preciso depurar um problema. Não proponha a correção logo de cara: primeiro raciocine em etapas.

Microcontrolador: {ex.: STM32F411CE}
Periféricos envolvidos: {ex.: SPI1 em modo mestre, ADC1 com DMA, EXTI}
Comportamento esperado: {o que deveria acontecer}
Comportamento observado: {o que acontece, com mensagens, valores lidos, frequências}
O que já tentei: {lista}
Código relevante:
"""
{cole aqui}
"""

Responda nesta ordem:
1. Hipóteses: liste de 3 a 6 causas possíveis, separadas por camada
   (hardware/clock, configuração de periférico, interrupções/concorrência, lógica, protocolo).
2. Para cada hipótese: como confirmar ou descartar (o que medir, o que imprimir, qual breakpoint).
3. A hipótese mais provável, com justificativa baseada no código.
4. Correção proposta, mostrando só o trecho alterado e explicando a mudança.

Restrições:
- Não reescreva partes do código que não têm relação com o problema.
- Se precisar de uma informação que não dei (ex.: configuração do clock tree), pergunte em vez de supor.
```

## Resultado

<!-- Descreva um caso real resolvido com esse prompt, sem expor código do laboratório.
     Ex.: "Identificou que uma rotina bloqueante dentro da ISR travava a comunicação SPI." -->
