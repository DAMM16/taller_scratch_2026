# Animaciones de UCMITO

Los fotogramas son archivos PNG de **640 × 680 px**, con fondo transparente y el mismo encuadre. Reprodúcelos en orden numérico a **20 fotogramas por segundo** (50 ms por cuadro). Puedes mantener la pose de reposo visible el tiempo que necesites.

## Archivos

| Secuencia | Ubicación al descomprimir | Fotogramas |
|---|---|---|
| Caminata | Carpeta `UCEMITO_fotogramas` | `UCEMITO_01.png` a `UCEMITO_36.png` |
| Salto desde el reposo | Carpeta `UCMITO_salto_desde_reposo/`| `UCMITO_01.png` a `UCMITO_35.png` |
| Salto durante la caminata | Carpeta `UCMITO_salto_en_caminata/`| `UCMITO_01.png` a `UCMITO_61.png` |

Las carpetas de salto usan los mismos nombres de PNG. Consérvalas separadas al importar los fotogramas.

## Caminar desde el reposo

1. Muestra el cuadro **01 de la caminata** mientras UCMITO esté quieto.
2. Al comenzar a caminar, reproduce los cuadros **02–12** una sola vez.
3. Repite los cuadros **13–36** mientras siga caminando.

## Saltar mientras camina

| Orden | Secuencia | Cuadros |
|---|---|---|
| 1 | Caminata | Hasta mostrar el **36** |
| 2 | `UCMITO_salto_en_caminata/` | **25–43** |
| 3 | Caminata | **19–36** para retomar el paso y luego **13–36** en bucle |

El cuadro **24 del salto** es idéntico al **36 de la caminata**. El **44 del salto** es idéntico al **19 de la caminata**. Los rangos de la tabla muestran cada pose de empalme una sola vez.

Si el salto se activa con un botón, guarda la solicitud y empieza el salto después de mostrar el **36 de la caminata**.

## Saltar desde el reposo

Desde el cuadro **01 de la caminata**, reproduce los cuadros **02–35** de `UCMITO_salto_desde_reposo/`. El cuadro **35** coincide con la pose de pie. Puedes mantenerlo en pantalla o continuar directamente con el cuadro **02 de la caminata** para empezar a andar.
