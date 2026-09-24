# Semana 05 · P3 — AAA + assertThrows: el nivel de 15 %

Continúa sobre **el mismo repositorio de la Semana 04** (P1 + P2 ya resueltas).
No crees un proyecto nuevo. Este ZIP trae únicamente los dos archivos que
cambian esta semana; el resto de tu repo se queda igual.

**Las instrucciones completas, las preguntas de diagnóstico y el formato de
entrega están en el documento `S05_P1_Practica.docx`** que viene en este
mismo ZIP. Este README es sólo el mapa del proyecto.

## Qué traes de este ZIP a tu repositorio

| Archivo de este ZIP | Dónde va en tu repositorio | Qué hace |
|---|---|---|
| `Descuento.java` | `src/main/java/mx/itson/devops/descuento/` (reemplaza el tuyo) | Agrega el nivel de 15 % — con un defecto a propósito |
| `DescuentoNivelesTest.java` | `src/test/java/mx/itson/devops/descuento/` | Pruebas AAA; 3 completas, 2 con TODO |

## Mapa del proyecto (después de copiar)

```
descuento-volumen/
|-- pom.xml
|-- .gitignore
`-- src/
    |-- main/java/mx/itson/devops/descuento/
    |   `-- Descuento.java                   <-- nuevo nivel, con un defecto
    `-- test/java/mx/itson/devops/descuento/
        |-- DescuentoSmokeTest.java          (Semana 04, sin cambios)
        |-- DescuentoFronteraTest.java        (Semana 04, sin cambios)
        `-- DescuentoNivelesTest.java         <-- completa los TODO
```

## Comandos de la práctica

```bash
mvn -B test
```

## Entrega

Repositorio actualizado + el .docx llenado.
Fecha límite: **sábado, 5:00 a.m.**
