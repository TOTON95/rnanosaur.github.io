---
title: "Lista de materiales"
permalink: /bill-of-materials/es
toc: true
toc_label: "Tabla de Contenido"
toc_icon: "cog"
toc_sticky: true
---

Si quieres hacer tu nanosaur, es simple y lo puedes hacer directamente en tu hogar, lo único que necesitas son algunas herramientas e imprimir algunas partes y comprar otras.

Si no quieres imprimir o no tienes acceso a una impresora 3D, puedes comprar todas las partes que necesites, simplemente dirígete a la página de [compras](/buy/es).

# BOM (Lista de Materiales)

En esta tabla encontrarás lo necesario para hacer tu nanosaur. Son pocas partes, empezando por la NVIDIA Jetson, la cámara PI, motores y el control de motores.

Si te encuentras comprando desde otros países, sigue esta lista

* [:us: USA](/extra/bom-countries#us-usa)
* [:it: Italy](/extra/bom-countries#it-italy)
* [:uk: United Kingdom](/extra/bom-countries#uk-united-kingdom)

## Set de tornillos

nanosaur usa un pequeño set de tornillos M2, puedes comprar un set con

| Cantidad | Parte       | Notas |
| :------: | ----------- | ----- |
|    6     | M2 tuercas  |       |
|    6     | Hex M2 20mm |       |
|    1     | Hex M2 14mm |       |
|    8     | Hex M2 6mm  |       |
|    20    | Hex M2 4mm  |       |

## Placa de Expansión

Esta última tabla es para construir la placa de expansión para conectar la NVIDIA Jetson a la placa de control de los motores y las dos pantallas OLED.

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

Para construir la placa de expansión sigue [esta página](/expansion-board/es)

## Partes 3D 

Si quieres imprimir a nanosaur, debes comprar estos filamentos. Te sugiero el filamento TPU de Ninjatek si usas una impresora 3D bowden. De otra forma, puedes usar cualquier otro tipo de TPU.

| Cantidad | Parte              | Costo (USD) | URL  | Notas |
| :------: | ------------------ | ----------- | ---- | ----- |
|    1     | PLA verde          | $15         |      |       |
|    1     | PLA negro          | $15         |      |       |
|    1     | TPU NinjaTek negro | $40         |      |       |

Las partes a imprimir se encuentran más [abajo](#componentes-a-imprimir).

## Opcionales

Estas partes no son realmente necesarias, pero son sugeridas si quieres elevar la velocidad de tu NVIDIA Jetson o el ensamblaje del robot.

| Cantidad | Parte              | Costo (USD) | URL | Notas |
|:--------:|---------------------|------|-----|-------|
| 1        | Ventilador Noctua 4x4cm    | $15  |  |       |
| 1        | Destornillador M2       | $5   |     |       |

# Componentes a imprimir

Bien, ahora tienes todos los componentes, ahora necesitas impirmir al robot en 3D. Todas las partes son simples de imprimir pero, necesitan tiempo para estar listas, más abajo tienes una pequeña tabla con el tiempo promedio para cada una de las partes.

Yo recomiendo imprimir todas las partes STL con:
* **Altura de la capa**: 0.2mm
* **Velocidad de impresión**: 50mm/s

A continuación, la lista de todas las partes, el tiempo requerido y color sugerido por cada una: 

| Cantidad | Parte           | Material        | Tiempo | Notas |
|:--------:|-----------------|-----------------|:-----:|-------|
| 1        | base_rear.stl   | PLA verde       | 5h    |       |
| 1        | base_front.stl  | PLA verde       | 1:30h |       |
| 1        | cover.stl       | PLA verde       | 1:45h |       |
| 2        | slider.stl      | PLA verde       | 1h    |       |
| 1        | pb_holder.stl   | PLA verde       | 20min |       |
| 1        | flap_top.stl    | PLA verde       | 45min |       |
| 1        | flap_bottom.stl | PLA verde       | 45min |       |
| 2        | sprocket.stl    | PLA verde/negro | 1h    |       |
| 2        | wheel.stl       | PLA verde/negro | 1h    |       |
| 2        | track_print.stl | TPU negro/gris  | 1:30h | **Velocidad de impresión**: 30mm/s |

Puedes reducir el tiempo para imprimir tu nanosaur, imprimiendo algunas partes juntas al mismo tiempo, Para más detalles ve a la [siguiente página](/3d-print/es) de esta guía para configurar e imprimir con tu impresora 3D.