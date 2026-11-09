# BioinfoPlus

Material de bioinformática para estudiantes: análisis de cinética de
crecimiento celular. A partir de datos de absorbancia y número de
células, se construye la curva de crecimiento por fases (latencia,
exponencial y estacionaria), se correlaciona la absorbancia con la
densidad celular y se ajusta el modelo de Gompertz.

## Contenido

- **Cinéticas:** análisis de cinética de crecimiento celular —
  correlación entre absorbancia y densidad celular, curva de crecimiento
  por fases y ajuste al modelo de Gompertz. El archivo trae
  instrucciones para que el estudiante rellene sus propios datos y
  ajuste los límites de las fases.

### Lecciones de bioinformática

- **01-taxonomia-clasificacion-por-secuencias:** clasificación de un
  aislado por su secuencia 18S: identidad de secuencia con cinco
  especies de referencia de GenBank y asignación al género Chlorella.
- **02-filogenetica-arbol-por-distancias:** árbol filogenético por
  neighbor-joining a partir de distancias genéticas p y de Jukes-Cantor
  entre seis microalgas verdes.
- **03-genomica-composicion-de-un-genoma:** composición del genoma del
  cloroplasto de Chlorella vulgaris (GenBank AB001684): conteo de bases,
  contenido GC y sesgo GC en ventanas, y comparación con el cloroplasto
  de Chlamydomonas reinhardtii.
- **04-proteomica-abundancia-de-proteinas:** abundancia de 12 proteínas
  de Chlorella vulgaris bajo luz azul y roja: cambio log2, prueba t de
  Welch y gráfico de volcán. Datos de ejemplo generados con fines
  didácticos.
- **05-metabolomica-perfiles-de-metabolitos:** perfiles de 10
  metabolitos de Chlorella vulgaris bajo luz azul, blanca y roja:
  análisis de componentes principales (PCA) y mapa de qué mide cada
  ómica. Datos de ejemplo generados con fines didácticos.

## Cómo usarlo

Abre el archivo en R o RStudio, rellena tus datos en el paso indicado y
ejecuta el script completo. Necesitas R y los paquetes `tidyverse`,
`nls.multstart`, `ggpmisc` y `scales`, que se indican al inicio del
archivo.

Las lecciones de bioinformática (01 a 05) se ejecutan completas: los
datos van dentro de cada archivo y no hay que rellenar nada. Necesitan R
y los paquetes `tidyverse`, `Biostrings` (Bioconductor) y `ape` (lección
02), que se indican al inicio de cada archivo. Cada lección exporta sus
gráficos en PNG (300 dpi) al final. Los archivos de las lecciones no
llevan extensión, igual que el archivo de cinéticas.

## Autoría

- **Autora del material original:** La Carmen (19 de octubre de 2025).
- **Repositorio y curaduría:** Dr. José Juan Torres Martínez, Docente de
  Ciencias Químicas, Universidad Autónoma de San Luis Potosí (UASLP),
  México.

Material académico para estudiantes.
