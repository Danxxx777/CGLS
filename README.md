# CGLS · Cooperativa Ahorro Futuro

**Actividad:** GA-TL-01 · Escenario 4: Sistema bancario.

## Integrantes

- CORONEL GOMEZ KHRIZ ALEXANDER
- GIRALDO CAGUA DIEGO JOSE
- LOOR MENDOZA BYRON DANIEL
- SILVA TRIVIÑO JOHN JAIRO

## Instrucciones de compilación

El documento fuente es `Notas-conjuntas-bloques-A-B-C-D.tex`.

### Compilación local

1. Instalar una distribución LaTeX, como **TeX Live** o **MiKTeX**, con pdfLaTeX y los paquetes `inputenc`, `fontenc`, `lmodern`, `babel` con español, `geometry`, `enumitem` e `hyperref`. El documento utiliza `microtype` si está disponible.
2. Abrir una terminal en la carpeta raíz del repositorio.
3. Ejecutar los siguientes comandos. La segunda ejecución resuelve las citas y referencias:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Notas-conjuntas-bloques-A-B-C-D.tex
pdflatex -interaction=nonstopmode -halt-on-error Notas-conjuntas-bloques-A-B-C-D.tex
```

El resultado es `Notas-conjuntas-bloques-A-B-C-D.pdf`, en la misma carpeta. Las referencias se encuentran en el propio archivo `.tex` mediante `thebibliography`; no se necesita ejecutar BibTeX ni Biber.

### Compilación en Overleaf

1. Crear un proyecto y subir `Notas-conjuntas-bloques-A-B-C-D.tex`.
2. Seleccionarlo como documento principal y utilizar el compilador **pdfLaTeX**.
3. Pulsar **Recompilar** y descargar el PDF generado.
