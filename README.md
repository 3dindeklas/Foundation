# 3Dindeklas Foundation

De centrale design- en contentreferentie voor digitale producten, lesmateriaal en communicatie van 3Dindeklas.

## Gebruik

- [Bekijk de stijlguide](https://3dindeklas.github.io/Foundation/)
- [Machineleesbare stijltokens (JSON)](https://raw.githubusercontent.com/3dindeklas/Foundation/main/brand.json)
- [CSS-tokens](https://3dindeklas.github.io/Foundation/foundation.css)
- [Volledige regels in Markdown](https://raw.githubusercontent.com/3dindeklas/Foundation/main/style-guide.md)

Voor nieuwe AI- of codeprojecten:

```text
Gebruik de 3Dindeklas Foundation als visuele en inhoudelijke bron:
https://raw.githubusercontent.com/3dindeklas/Foundation/main/style-guide.md
Gebruik de actuele tokens:
https://raw.githubusercontent.com/3dindeklas/Foundation/main/brand.json
```

In een website kun je de CSS laden met:

```css
@import url("https://3dindeklas.github.io/Foundation/foundation.css");
```

De JSON is de bron voor machineleesbare waarden. De Markdown beschrijft hoe je die toepast. De webpagina maakt de regels visueel en scanbaar.

## Bijdragen

Werk tokens eerst in `brand.json` bij, synchroniseer `foundation.css` en pas voorbeelden en uitleg aan. Houd versie en wijzigingsdatum bij. De GitHub Pages workflow publiceert wijzigingen vanaf `main`.
