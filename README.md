# Kursmaterial für das "Forschungsorientierte Praktikum I – Grundlagen der Forschung" im BSc Psychologie der LMU

This is the source code. See the rendered website at [https://nicebread.github.io/Empra1/](https://nicebread.github.io/Empra1/).

*Note: The material will (initially) be a crude mixture of German and English. Your mileage may vary.*


## Compilation / dependencies

You need:

- quarto > 1.3.45
- [Font Awesome Extension for Quarto](https://github.com/quarto-ext/fontawesome)
- [Attribution Extension](https://github.com/quarto-ext/attribution)
- The [FOMO theme](https://github.com/nicebread/quarto-FS), which is based on the [Quarto clean theme](https://github.com/grantmcdermott/quarto-revealjs-clean/tree/main)

Run the following commands in the project's root directory to install some add-ons and the theme:

```
quarto add quarto-ext/attribution
quarto add quarto-ext/fontawesome
quarto install extension nicebread/quarto-FS
```

## Notes to self:

- The default presentation size is 1050 x 700.
- To publish online, run `quarto publish gh-pages` locally.
- Right arrow (→): `&rarr;`
- Double headed arrow (↔): `&harr;`
- Full processing:

```
quarto render
quarto publish gh-pages
```