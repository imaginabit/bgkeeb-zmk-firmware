# zmk-bgkeeb

Fork personal de [ezxzeng/zmk-bgkeeb](https://github.com/ezxzeng/zmk-bgkeeb) para compilar el firmware ZMK del **bgkeeb** con microcontroladores **nice!nano v2** (nRF52840).

## Estado

Primera build en curso via GitHub Actions. Los artefactos `bgkeeb_left-nice_nano-zmk.uf2` y `bgkeeb_right-nice_nano-zmk.uf2` se descargan desde la pestaña Actions.

> Nota: el repo upstream `ezxzeng/zmk-bgkeeb` usaba `board: nice_nano_v2` que ya no existe en ZMK actual. Cambiado a `nice_nano` en `build.yaml`.

## Uso

- Mitad izquierda al PC por USB (cerebro + conexión al host)
- Mitad derecha a un puerto USB del PC o a un cargador (comunica con la izquierda por BLE alimentada por USB)
- Sin baterías instaladas
