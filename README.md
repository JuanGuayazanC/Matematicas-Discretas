# Matemáticas Discretas (MATD)

Repositorio general del curso Matemáticas Discretas (ISIS MATD), que agrupa —mediante submódulos de git— los talleres del curso.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para clonar este repositorio junto con todo su contenido, ver [Cómo clonar](#cómo-clonar).

## Estructura del proyecto

```
Matematicas-Discretas/
└── Talleres/
    └── Secuencias-y-Listas-en-Haskell-MATD/
```

## Temas del curso

El curso recorre los fundamentos de la lógica formal y las matemáticas discretas usadas en ciencias de la computación:

- **Demostraciones formales**: estilo calculacional (Dijkstra-Scholten) para probar propiedades algebraicas paso a paso, con justificación explícita de cada transformación.
- **Teoría de conjuntos**: inclusión y operaciones entre conjuntos.
- **Aritmética aditiva y multiplicativa**: dominios de integridad, monotonía y cancelación, inverso aditivo, identidad.
- **Dominios ordenados**: propiedades de las relaciones de orden, desigualdad entera.
- **Operadores de comparación**: máximo (↑) y mínimo (↓), sus propiedades algebraicas y de distributividad.
- **Funciones piso y techo, y valor absoluto**: propiedades y teoremas asociados.
- **Teoría de secuencias**: programación funcional en Haskell sobre listas (recursión, funciones sobre secuencias).
- **Lenguajes formales, gramáticas y autómatas**: teoría de la computación aplicada al reconocimiento de lenguajes.

## Cosas a tener en cuenta

- El taller de Haskell (`Secuencias-y-Listas-en-Haskell-MATD`) aplica la teoría de secuencias vista en el curso mediante programación funcional.
- El repositorio `MATD1` de este curso se dejó vacío intencionalmente, reservado para contenido futuro.

## Herramientas

- Haskell (GHCi)
- Lógica calculacional / demostraciones formales

## Cómo clonar

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Matematicas-Discretas.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
