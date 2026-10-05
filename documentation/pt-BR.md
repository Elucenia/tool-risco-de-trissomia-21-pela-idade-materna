<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · pt-BR · no clinical/professional/rights approval -->

# Risco de síndrome de Down pela idade materna

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/risco-de-trissomia-21-pela-idade-materna)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Idade materna na data provável do parto

`idade`

anos · intervalo: 15–50

## Edição do método

Morris Mutton Alberman 2002:logístico inglês/galêsnascimentovivo 1989–1998; semrisco gestacional universal

## Fórmula documentada

Morris, Mutton e Alberman (2002): risco = 1 ÷ \[1 + e(7,330 − 4,211 ÷ (1 + e−0,282 × (idade − 37,23)))\]

Modelo logístico ajustado aos dados do registro nacional de síndrome de Down da Inglaterra e do País de Gales (1989 a 1998), corrigidos para a ausência de rastreamento e interrupção.

## Limites e população

Esta fórmula descreve prevalência de síndrome de Down em nascidos vivos, por idade materna, a partir de dados de Inglaterra e Gales de 1989–1998, estimando ausência de rastreio e interrupção seletiva. Não fornece risco em qualquer idade gestacional nem substitui rastreio ou diagnóstico individual.

## Referências

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
