# COTA — Documentación

La documentación de [COTA](https://usacota.app), publicada en **https://docs.usacota.app** con [Mintlify](https://mintlify.com). Cada push a `main` se publica solo.

## Ver los cambios en local

```bash
npm i -g mint
mint dev
```

Antes de pushear: `mint validate` y `mint broken-links`.

## Reglas

- Una página = una pregunta (va en el `description` del frontmatter).
- Voseo y el tono de la app. Los nombres de botones y pantallas, tal cual aparecen en COTA.
- Montos con `\$` (si no, Mintlify los toma como fórmulas) y nada de llaves `{}` sueltas en el texto.

## Capturas

Las imágenes de `images/` salen de la cuenta demo (Estudio Rivas) con el script `docs-capturas/` del repo de la app. Cuando cambia la UI, se vuelven a sacar todas.
