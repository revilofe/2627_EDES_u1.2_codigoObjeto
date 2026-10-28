# EDES U1 P13 - Código fuente, objeto y ejecutable

Plantilla de entrega para la práctica [EDES-U1.-Practica013](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica013/).

Completa este `README.md`, conserva el archivo `programa.c` y añade las
evidencias solicitadas. No subas normalmente los archivos generados `programa.o`
ni `programa`/`programa.exe`, salvo que se indique expresamente: documenta su
existencia mediante una tabla, un listado o una captura.

## 1. Identificación

| Dato | Valor |
|---|---|
| Nombre y apellidos | <!-- Completa este dato. --> |
| Módulo | Entornos de desarrollo |
| Unidad | 1 |
| Práctica | P13 - Del código fuente al código ejecutable |
| Fecha | <!-- Completa este dato. --> |

## 2. Entorno de trabajo

| Dato | Valor |
|---|---|
| Sistema operativo | <!-- Linux, macOS o Windows. --> |
| Arquitectura | <!-- Por ejemplo, x86_64 o arm64. --> |
| Versión de GCC | <!-- Pega la salida relevante de `gcc --version`. --> |
| Terminal utilizada | <!-- Bash, PowerShell, otra. --> |

## 3. Código fuente

Crea y conserva el archivo `programa.c` con este contenido inicial:

```c
#include <stdio.h>

int main(void) {
    int num1 = 5;
    int num2 = 3;
    int resultado = num1 + num2;

    printf("El resultado es: %d\n", resultado);
    return 0;
}
```

Explica brevemente qué parte del archivo es código fuente y qué resultado
esperas obtener antes de compilarlo.

**Respuesta:**

<!-- Escribe aquí tu explicación. -->

## 4. Archivos y etapas del proceso

Completa la tabla con los archivos generados en tu entorno. Usa `programa.exe`
si trabajas en Windows.

| Archivo | Herramienta que lo produce | Etapa | Qué representa | ¿Se puede ejecutar directamente? |
|---|---|---|---|---|
| `programa.c` |  |  |  |  |
| `programa.o` |  |  |  |  |
| `programa` o `programa.exe` |  |  |  |  |

Comandos utilizados para generar los archivos:

```text
<!-- Escribe aquí los comandos ejecutados y su resultado resumido. -->
```

## 5. Preguntas sobre compilación y enlazado

### 5.1. Código fuente

¿Por qué el código fuente no se ejecuta directamente?

**Respuesta:**

<!-- Completa la respuesta. -->

### 5.2. Compilación

¿Qué hace el paso de compilación? Relaciona la respuesta con el comando que
incluye la opción `-c`.

**Respuesta:**

<!-- Completa la respuesta. -->

### 5.3. Enlazado

¿Qué resuelve el enlazador y qué elementos combina para preparar el ejecutable?

**Respuesta:**

<!-- Completa la respuesta. -->

### 5.4. Omisión de una etapa

¿Qué fallaría si se omitiera la generación del objeto o el enlazado?

**Respuesta:**

<!-- Completa la respuesta. -->

### 5.5. Objeto frente a ejecutable

¿Por qué no se debe confundir un archivo objeto con un ejecutable aunque ambos
contengan datos binarios?

**Respuesta:**

<!-- Completa la respuesta. -->

## 6. Modificación a 17 y 25

Cambia los valores iniciales de `programa.c` a `17` y `25`.

### 6.1. Predicción

- Resultado esperado antes de ejecutar: <!-- Completa la predicción. -->
- Motivo por el que hay que volver a compilar y enlazar:
  <!-- Completa la explicación. -->

### 6.2. Comandos y resultado observado

```text
<!-- Escribe los comandos separados de compilación, enlazado y ejecución. -->
```

Resultado de la segunda ejecución:

```text
<!-- Pega aquí la salida: debería incluir «El resultado es: 42». -->
```

## 7. Buenas prácticas reutilizables

Identifica al menos cuatro buenas prácticas observadas en la actividad y explica
brevemente cómo ayudan a evitar errores o a hacer reproducible el trabajo.

| Buena práctica | Justificación |
|---|---|
|  |  |
|  |  |
|  |  |
|  |  |

## 8. Evidencias

Incluye una captura o un listado que permita comprobar los archivos generados.
Si incorporas imágenes, guárdalas en una carpeta `evidencias/` y enlázalas desde
este documento.

```text
<!-- Añade aquí el listado, los comandos o los enlaces a las capturas. -->
```

## 9. Reflexión final

Explica qué has aprendido sobre la relación entre el código fuente, el archivo
objeto, el enlazador, las bibliotecas y el ejecutable. Indica también por qué un
ejecutable puede depender del sistema operativo y de la arquitectura donde se
construye.

<!-- Escribe aquí tu reflexión. -->

## 10. Lista de comprobación

- [ ] He completado la identificación y el entorno de trabajo.
- [ ] He incluido `programa.c` con el código solicitado.
- [ ] He documentado `programa.o` y el ejecutable generado.
- [ ] He respondido las preguntas sobre compilación y enlazado.
- [ ] He repetido el proceso con `17` y `25` y he obtenido `42`.
- [ ] He identificado al menos cuatro buenas prácticas.
- [ ] He añadido las evidencias solicitadas.
- [ ] He escrito la reflexión final.
