# Semana 05 · P4 — De pruebas repetidas a @ParameterizedTest + gate de CI

Continúa sobre **el mismo repositorio** (Semana 04 + Práctica 3 ya resueltas).
No crees un proyecto nuevo.

**Las instrucciones completas están en `S05_P2_Practica.docx`**, en este
mismo ZIP. Aquí sólo va el archivo que debes copiar a tu repositorio.

## Qué traes de este ZIP a tu repositorio

| Archivo de este ZIP | Dónde va en tu repositorio |
|---|---|
| `DescuentoParametrizadoTest.java` | `src/test/java/mx/itson/devops/descuento/` |

No necesitas tocar `ci.yml`: es el mismo que instalaste en la Práctica 2 de
Semana 04 y ya corre `mvn -B verify` en cada push / Pull Request.

## Resumen del ciclo que debes evidenciar

1. Copia el archivo y corre `mvn -B test` → todo verde (son los niveles que
   ya tenías: 0 %, 10 %, 15 %).
2. El área comercial pide un nivel más: **1000+ unidades → 20 %**. Agrega
   las dos filas nuevas al `@CsvSource` ANTES de tocar `Descuento.java` y
   vuelve a correr `mvn -B test` → rojo informativo, con el nombre exacto de
   la combinación que falló.
3. Corrige `Descuento.java` (recuerda el orden de condiciones de la P3).
4. `mvn -B test` → verde.
5. Push (rama + Pull Request, o directo a `main` según tu flujo) →
   **guarda el run ROJO y el run VERDE de GitHub Actions**.

## Entrega

Link al repositorio/Pull Request con los dos runs + el .docx llenado.
Fecha límite: **sábado, 5:00 a.m.**
