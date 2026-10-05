<!-- ELUCENIA technical documentation · pressao-arterial-media · en · no clinical/professional/rights approval -->

# Mean arterial pressure and pulse pressure

[conditions, sources and permissions](https://elucenia.org/en/tools/pressao-arterial-media)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Systolic blood pressure

`pas`

mmHg · range: 50–300

### Diastolic pressure

`pad`

mmHg · range: 20–200

## Method edition

MAP=(SBP+2 DBP)/3; pulse pressure SBP−DBP; adult approximation at conventional rhythm; Brazilian guideline 2020

## Documented formula

MAP = diastolic BP + (systolic BP − diastolic BP) ÷ 3

Pulse pressure = systolic BP − diastolic BP

## Limits and population

The approximation of diastolic pressure plus one third of pulse pressure assumes a normal heart rate, according to the AHA 2019 statement; it is not direct integration of the pressure waveform. Use systolic and diastolic values in mmHg obtained with an appropriate technique and device, and document measurement conditions. Systolic minus diastolic pressure is pulse pressure, not pulse rate. The result alone does not establish a hypertension diagnosis or a universal target for critically ill patients.

## References

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
