# Netos - Arvernus SCSS Library

Netos ist eine SCSS Library, die dinge wie das Gridsystem oder die Breakpoints von Arvernus beinhaltet. Alles basierend auf Variablen und flexibel anpassbar. 

## Installation 

### `NPM` 
`npm install https://github.com/Arvernus/netos --save-dev`
als nächstes gilt es sicher zustellen, dass der SASS/SCSS PreProcessor den Pfad `node_modules/netos/` in der Pipeline beachtet. Im fall von GulpSASS:
```js
.pipe(sass({
  includePaths: ['node_modules/netos/']
}))
```
nun muss die Library nur noch in das Projekt eingebunden werden:
``scss
@import 'netos'; // Arvernus SCSS Library
```
