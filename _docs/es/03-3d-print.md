---
title: "3D print"
permalink: /3d-print/es
header:
  teaser: /assets/docs/3d-print/base_rear.png
toc: true
toc_label: "Tabla de Contenido"
toc_icon: "cog"
toc_sticky: true
base_front:
  - url: /assets/docs/3d-print/base_front_A.png
    image_path: /assets/docs/3d-print/base_front_A.png
    alt: "Orientación de base_front.stl"
    title: "Orientación de base_front.stl"
  - url: /assets/docs/3d-print/base_front_B.png
    image_path: /assets/docs/3d-print/base_front_B.png
    alt: "Soporte del Slicer de tipo arbol para base_front.stl"
    title: "Soporte del Slicer de tipo arbol para base_front.stl"
flaps_pb_holder:
  - url: /assets/docs/3d-print/flap_pb_holder_A.png
    image_path: /assets/docs/3d-print/flap_pb_holder_A.png
    alt: "Orientación de la Solapa y el portador de la Power Bank"
    title: "Orientación de la Solapa y el portador de la Power Bank"
  - url: /assets/docs/3d-print/flap_pb_holder_B.png
    image_path: /assets/docs/3d-print/flap_pb_holder_B.png
    alt: "Soporte del Slicer de tipo árbol para la Solapa y el portador de la power bank"
    title: "Soporte del Slicer de tipo árbol para la Solapa y el portador de la power bank"
---

Si estás aquí, entonces quieres imprimir tu nanosaur, es simple, pero podría tomar algo de tiempo.

El **diseño Nanosaur** está bajo la licencia [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
{: .notice}

Yo uso [Cura slicer](https://ultimaker.com/software/ultimaker-cura), pero todos los demás slicers deberían funcionan bien. 
Siguiendo esta guía, el tiempo total para imprimir un nanosaur será:

| Partes | Tiempo |
|-------|------|
| [Base trasera](#base-trasera) | **5h** |
| [Base frontal](#base-frontal) | **1h** y **30min** |
| [Ruedas y ruedas de espigas](#ruedas-y-ruedas-de-espigas) | **2h** |
| [Deslizadores](#deslizadores) | **2h** |
| [Cubierta](#cubierta) | **1h** and **45min** |
| [Solapa y sujetador de power bank](#solapa-y-sujetador-de-power-bank) | **1h** y **45min** |
| [Orugas](#orugas) | 2x **1h** y **30min** |
| **Total** | **17h** |

**:floppy_disk: Descarga** puedes obtener todas las partes de Nanosaur solamente con descargar este archivo zip [**nanosaur_stl.zip**](https://github.com/rnanosaur/nanosaur/releases/latest/download/nanosaur_stl.zip)
{: .notice--success}

**:bulb: Pista** En el archivo nanosaur_stl.zip puedes encontrar una carpeta llamada **025in** para rodamientos de tamaño *ID 1/4in x 0D 1/2in*
{: .notice--info}

{% include video id="5cVNXbF6HzI" provider="youtube" %}

# Imprime las partes en PLA

You can split all parts following this guideline and setup the printer using this profile:
* **Layer height**: 0.2mm
* **Print speed**: 50mm/s
* **Infill**: 15%

Puedes dividir todas las partes siguiendo esta guía y configurando tu impresora para usar este perfil:
* **Altura de la capa**: 0.2mm
* **Velocidad de impresión**: 50mm/s
* **Relleno**: 15%

## Base Trasera

Para imprimir las siguientes partes, vas a necesitar **PLA verde**. El tiempo promedio va a ser de: **5h**

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 1        | [base_rear.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_rear.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/base_rear.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Desactivar

{% include figure image_path="/assets/docs/3d-print/base_rear.png" alt="base_rear.stl slicer" caption="base_rear.stl slicer" %}

## Base frontal

Para imprimir estas partes, necesesitas **PLA verde**. El tiempo promedio será de: **1h** y **30min**.

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 1        | [base_front.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_front.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/base_front.stl?height=320&width=320"></script> |

Sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Activar
* **Estructuras de soporte**: Árbol

{% include gallery id="base_front" caption="base_front.stl slicer" %}

## Ruedas y ruedas de espigas

**:bulb: Pista** En el archivo nanosaur_stl.zip puedes encontrar una carpeta llamada **025in** para rodamientos de tamaño *ID 1/4in x 0D 1/2in*
{: .notice--info}

Para imprimir estas partes, necesitas **PLA verde/negro**. El tiempo promedio será: **2h**. 

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 2        | [sprocket.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/sprocket.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/sprocket.stl?height=320&width=320"></script> |
| 2        | [wheel.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/wheel.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/wheel.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Desactivar

{% include figure image_path="/assets/docs/3d-print/wheel_sprocket.png" alt="ruedas y ruedas de espigas slicer" caption="ruedas and ruedas de espigas slicer" %}

## Deslizadores

Para imprimir estas partes, necesitas **PLA verde**. El tiempo en promedio va a ser: **2h**.

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 2        | [slider.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/slider.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/slider.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Desactivar
* **Desplazamiento**:
  * **Izquierda**: x=0 y=15
  * **Derecha**: x=0 y=-15

{% include figure image_path="/assets/docs/3d-print/sliders.png" alt="sliders slicer" caption="sliders slicer" %}

## Cubierta

Para imprimir estas partes, necesitas **PLA verde**. El tiempo en promedio va a ser: **1h** y **45min**.

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 1        | [cover.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/cover.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Desactivar

{% include figure image_path="/assets/docs/3d-print/cover.png" alt="cover.stl slicer" caption="cover.stl slicer" %}

## Solapa y sujetador de Power bank

Para imprimir estas partes, necesitas **PLA verde**. El tiempo en promedio va a ser: **1h** y **45min**.

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 1        | [flap_top.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_top.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/flap_top.stl?height=320&width=320"></script> |
| 1        | [flap_bottom.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_bottom.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/flap_bottom.stl?height=320&width=320"></script> |
| 1        | [pb_holder.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/pb_holder.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/pb_holder.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Soportes**: Activar
* **Estructura de soportes**: Árbol
* **Desplazamiento**:
  * **flap_bottom.stl**: x=20 y=0
  * **flat_top.stl**: x=-20 y=0
  * **pb_holder.stl**: x=-55 y=0

{% include gallery id="flaps_pb_holder" caption="flap and pb_holder slicer" %}

# Orugas

Las orugas de nanosaur son las partes más dificiles de imprimir. Necesitas una buena impresora, mejor aún si tu impresora es de extrusión directa. De otra forma te sugiero usar TPU Ninjatek, que es suficientemente elastico para hacer esas orugas.

El tiempo promedio va a ser: **1h** y **30min** para cada oruga

| Cantidad | Parte            | Vista 3D |
|:--------:|-----------------|:-------:|
| 2        | [track_print.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/track_print.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/track_print.stl?height=320&width=320"></script> |

Te sugiero orientar el STL de acuerdo con la imagen y la siguiente configuración:
* **Altura de la capa**: 0.2mm
* **Velocidad de impresión**: 30mm/s
* **Relleno**: 10%
* **Soportes**: Desactivar
* **Retracción**: Desactivar

{% include figure image_path="/assets/docs/3d-print/track_print.png" alt="track_print.stl slicer" caption="track_print.stl slicer" %}

# LICENCIA

El **diseño de Nanosaur** esta bajo licencia [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg