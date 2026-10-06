<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · en · no clinical/professional/rights approval -->

# Down syndrome risk by maternal age

[conditions, sources and permissions](https://elucenia.org/en/tools/risco-de-trissomia-21-pela-idade-materna)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Maternal age on the estimated due date

`idade`

years · range: 15–50

## Method edition

Morris–Mutton–Alberman 2002: England/Wales live-birth logistic model 1989–1998; not universal gestational risk

## Documented formula

Morris, Mutton, Alberman (2002): risk = 1 ÷ \[1 + e(7.330 − 4.211 ÷ (1 + e−0.282 × (age − 37.23)))\]

Logistic model fitted to England/Wales national Down syndrome register data (1989 to 1998), corrected for absence of screening and termination.

## Limits and population

This formula describes Down syndrome prevalence in live births by maternal age, using England and Wales data from 1989–1998 and estimating the absence of screening and selective termination. It does not provide risk at every gestational age or replace individual screening or diagnosis.

## References

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

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

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Baseline risk (a priori) at 35 years: 0.28%

| Result details | |
| --- | --- |
| Probability | 0.283% |

This is the starting risk: combined screening or NIPT modify it upward or downward.


### 2

Baseline risk (a priori) at 40 years: 1.16%

| Result details | |
| --- | --- |
| Probability | 1.164% |

This is the starting risk: combined screening or NIPT modify it upward or downward.


### 3

Baseline risk (a priori) at 25 years: 0.07%

| Result details | |
| --- | --- |
| Probability | 0.075% |

This is the starting risk: combined screening or NIPT modify it upward or downward.

