# Teorema del mono infinito

Un mono que pulse teclas al azar durante el tiempo suficiente acabará escribiendo cualquier texto.

- En producción: https://ricardverges.com/teorema/
- GitHub Pages: https://hunter138.github.io/teoremaMono/

Pulsa **Espacio** (o toca la tecla) para que el mono escriba una letra al azar. El botón **Mono automático** (o la tecla **A**) lo hace solo.

## Desarrollo

Es una sola página estática (`index.html`) con las fuentes alojadas en `fonts/`.

```sh
npm install
npm run deploy   # copia a dist/teorema/ y despliega el Worker "teorema" (ruta ricardverges.com/teorema*)
```
