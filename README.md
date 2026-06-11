# DIGITEM-MX Salud — Production V1.2

Landing page de producción para la vertical **DIGITEM-MX Salud**.

## Cambios V1.1

- La raíz `/` carga la landing directamente, sin pantalla visible de redirección.
- `/salud` se mantiene como URL principal de campaña.
- Hero mobile optimizado con una sola imagen visual full-width y chips compactos integrados.
- Se mantiene el hero desktop con composición amplia.

## Rutas

- `/`
- `/salud`
- `/salud/dentista`
- `/salud/psicologia`
- `/demo/dentista`
- `/demo/psicologia`

## Comandos

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```


## Production V1.2

- Se elimina la imagen del hero en mobile para evitar saturación visual.
- Se mantiene el hero desktop sin cambios.
- La experiencia mobile prioriza H1, copy, CTAs y prueba social.
