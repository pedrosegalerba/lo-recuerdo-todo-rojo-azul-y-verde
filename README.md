# Lo recuerdo todo rojo, azul y verde

Nueve videos de un archivo familiar.

Nueve videos de baja resolución (176 × 144) encontrados en el disco rígido de mi papá, convertidos en nubes de puntos que se pueden recorrer en 3D. La profundidad de cada cuadro se calculó con Video Depth Anything; el sitio está hecho con three.js.

Es la parte web de un proyecto transmedia que también incluye un libro de artista.

Pedro Segalerba, 2026 · Diseño de Imagen y Sonido, FADU-UBA · ACDT, cátedra Szlifman

## Cómo se usa

**En la computadora**
- Pasá el mouse por la nube para escuchar cada video y hacé clic para abrirlo.
- Arrastrar: girar.
- Rueda del mouse: acercar o alejar.
- Shift + arrastrar: mover el punto de giro.
- Barra espaciadora: pausa.

**En el celular**
- Un toque marca un video y otro toque lo abre.
- Un dedo: girar.
- Pellizcar: acercar o alejar.
- Dos dedos: mover.
- Tocá la pantalla para ver los controles.

## Qué hay en la carpeta

```
index.html   el sitio completo (estilos y código adentro)
lib/         three.js y OrbitControls
fonts/       tipografía Redaction 50
videos/      cada video en .mp4 y .webm: a la izquierda el color, a la derecha la profundidad
audio/       el sonido de cada video, para el murmullo del inicio en el celular
.nojekyll    le indica a GitHub Pages que publique los archivos tal cual
```

## Verlo en la computadora antes de publicar

El sitio tiene que abrirse desde un servidor, no con doble clic. En esta carpeta, abrí una terminal y escribí:

```
py -m http.server 8000
```

En Mac o Linux es `python3 -m http.server 8000`. Después entrá a http://localhost:8000.



## Créditos y licencias

- Videos, imágenes y textos: © Pedro Segalerba. Todos los derechos reservados.
- [three.js](https://threejs.org): licencia MIT.
- Tipografía Redaction 50, © 2019 MCKL Inc.: licencia SIL Open Font License 1.1. Ver `fonts/OFL_Redaction.txt`.
- Profundidad: [Video Depth Anything](https://github.com/DepthAnything/Video-Depth-Anything).
