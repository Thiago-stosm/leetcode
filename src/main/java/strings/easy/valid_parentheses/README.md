# Valid Parentheses

## Descrição do Problema
Dado uma string `s` contendo apenas os caracteres `'('`, `')'`, `'{'`, `'}'`, `'['` e `']'`, determine se a string é válida.

Uma string é considerada **válida** se:

1. Todos os parênteses abertos forem fechados pelo mesmo tipo de parênteses.
2. Os parênteses forem fechados na ordem correta.
3. Cada parêntese fechado tiver um correspondente parêntese aberto do mesmo tipo.

**Exemplos:**
```text
Input: s = "()"
Output: true

Input: s = "()[]{}"
Output: true

Input: s = "(]"
Output: false
