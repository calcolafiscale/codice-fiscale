# CalcolaFiscale — Codice Fiscale Documentation

This repository is the documentation for the free **CalcolaFiscale** tool at https://calcolafiscale.it/. CalcolaFiscale lets you calculate, decode and verify the Italian codice fiscale, with guides for foreigners, newborns, and an explanation of how the 16-character code is structured.

## The 16-character structure

The Italian codice fiscale is made of 16 characters, structured as follows:

| Positions | Meaning |
| --------- | ------- |
| 1–3       | First three letters of the surname |
| 4–6       | First three letters of the name |
| 7–8       | Last two digits of the birth year |
| 9         | Letter of the birth month |
| 10–11     | Day of birth, plus 40 if female |
| 12–15     | Birthplace code |
| 16        | Control character |

## Useful links

- Free tool: https://calcolafiscale.it/
- Decode a code: https://calcolafiscale.it/inverso/

## Important

Only the Agenzia delle Entrate issues the official codice fiscale. CalcolaFiscale is an independent tool, not official, and does not replace official sources. This tool does not recover a full name from a code: a codice fiscale alone cannot be used to reconstruct a person's complete name.
