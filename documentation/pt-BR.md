<!-- ELUCENIA technical documentation · pressao-arterial-media · pt-BR · no clinical/professional/rights approval -->

# Pressão arterial média e de pulso

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/pressao-arterial-media)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Pressão sistólica

`pas`

mmHg · intervalo: 50–300

### Pressão diastólica

`pad`

mmHg · intervalo: 20–200

## Edição do método

PAM=(PAS+2 PAD)/3 epressãopulso PAS−PAD; aproximação adulta ritmo convencional; DBHA 2020

## Fórmula documentada

PAM = PAD + (PAS − PAD) ÷ 3

Pressão de pulso = PAS − PAD

## Limites e população

A média aproximada por pressão diastólica mais um terço da pressão de pulso pressupõe frequência cardíaca normal, conforme a declaração AHA 2019; não é a integração direta da curva de pressão. Use sistólica e diastólica em mmHg, obtidas com técnica e aparelho apropriados, e documente as condições da medida. A diferença sistólica menos diastólica é pressão de pulso, não frequência do pulso. O resultado isolado não estabelece diagnóstico de hipertensão nem um alvo universal para pacientes críticos.

## Referências

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

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
