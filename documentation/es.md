<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · es · no clinical/professional/rights approval -->

# Riesgo de síndrome de Down según edad materna

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/risco-de-trissomia-21-pela-idade-materna)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Edad materna en la fecha probable de parto

`idade`

años · intervalo: 15–50

## Edición del método

Morris–Mutton–Alberman 2002: modelo logístico de nacidos vivos inglés/galés 1989–1998; no riesgo gestacional universal

## Fórmula documentada

Morris, Mutton, Alberman (2002): riesgo = 1 ÷ \[1 + e(7,330 − 4,211 ÷ (1 + e−0,282 × (edad − 37,23)))\]

Modelo logístico de registro nacional de Down de Inglaterra/Gales (1989 a 1998), corregido para ausencia de cribado e interrupción.

## Límites y población

Esta fórmula describe la prevalencia de síndrome de Down en nacidos vivos según edad materna, a partir de datos de Inglaterra y Gales de 1989–1998, estimando la ausencia de cribado y de interrupción selectiva del embarazo. No proporciona riesgo a cualquier edad gestacional ni sustituye el cribado o el diagnóstico individual.

## Referencias

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

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
