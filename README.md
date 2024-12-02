
# Cálculo do Primeiro Dígito Verificador do CPF em Python

Este é um script simples em Python que calcula o primeiro dígito verificador de um número de CPF de nove dígitos.

## Funcionalidade

- O script utiliza o algoritmo definido pela Receita Federal do Brasil para calcular o primeiro dígito verificador de um CPF.

## Como Funciona

- Extração dos Nove Primeiros Dígitos: O CPF fornecido é dividido em duas partes: os nove primeiros dígitos (os dígitos originais do CPF). Cálculo do Dígito Verificador: Cada um dos nove dígitos é multiplicado por um peso, que varia de 10 a 2, respectivamente. Os resultados dessas multiplicações são somados. Obtenção do Resto da Divisão: O total da soma é dividido por 11, e é obtido o resto da divisão. Verificação do Dígito Calculado: Se o resto da divisão for menor ou igual a 9, esse valor se torna o primeiro dígito verificador. Caso contrário, o primeiro dígito verificador é 0.
## Como Utilizar

- Para utilizar o script, basta fornecer um CPF válido no formato de nove dígitos. O script calculará o primeiro dígito verificador correspondente

## Observações
- Este script é uma implementação do algoritmo de validação de CPF e calcula apenas o primeiro dígito verificador. Para validar um CPF completamente, é necessário calcular também o segundo dígito verificador.
