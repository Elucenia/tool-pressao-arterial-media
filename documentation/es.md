<!-- ELUCENIA technical documentation · pressao-arterial-media · es · no clinical/professional/rights approval -->

# Presión arterial media y presión de pulso

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/pressao-arterial-media)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Presión sistólica

`pas`

mmHg · intervalo: 50–300

### Presión diastólica

`pad`

mmHg · intervalo: 20–200

## Edición del método

PAM=(PAS+2 PAD)/3; presión de pulso PAS−PAD; aproximación adulta en ritmo convencional; guía brasileña 2020

## Fórmula documentada

PAM = PA diastólica + (PA sistólica − PA diastólica) ÷ 3

Presión de pulso = PA sistólica − PA diastólica

## Límites y población

La aproximación de presión diastólica más un tercio de la presión de pulso presupone frecuencia cardíaca normal, según la declaración AHA 2019; no es la integración directa de la curva de presión. Use valores sistólico y diastólico en mmHg obtenidos con técnica y dispositivo apropiados, y documente las condiciones de medición. La diferencia sistólica menos diastólica es presión de pulso, no frecuencia del pulso. El resultado aislado no establece diagnóstico de hipertensión ni un objetivo universal para pacientes críticos.

## Referencias

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Hipertensión estadio 1 (DBHA 2020)

| Detalles del resultado | |
| --- | --- |
| Presión de pulso | 50 mmHg |


### 2

Hipertensión estadio 3 (DBHA 2020)

| Detalles del resultado | |
| --- | --- |
| Presión de pulso | 90 mmHg |

Presión de pulso > 60 mmHg: en los adultos mayores, sugiere rigidez arterial.


### 3

PA óptima (DBHA 2020)

| Detalles del resultado | |
| --- | --- |
| Presión de pulso | 40 mmHg |

