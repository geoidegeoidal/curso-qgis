<h1 align="center">Taller QGIS · Del dato al mapa</h1>

<p align="center">
  <strong>Convierte planillas y otras fuentes en evidencia geoespacial clara.</strong><br>
  Cuatro sesiones prácticas para preparar datos, analizarlos y comunicar resultados.
</p>

<p align="center">
  <a href="Syllabus-Curso-QGIS.pdf"><strong>Consultar el programa PDF</strong></a>
  · <a href="#programa">Programa</a>
  · <a href="#vista-previa-local">Vista previa local</a>
  · <a href="https://julloa.space">Contacto y convocatorias</a>
</p>

---

## A quién está dirigido

Personas que comienzan a trabajar con sistemas de información geográfica (SIG) o que necesitan ordenar y comunicar datos territoriales. El taller conecta el trabajo con tablas, el análisis espacial y la composición de mapas para apoyar la toma de decisiones.

Para participar se recomienda tener **QGIS instalado**, un mouse y una conexión estable cuando la modalidad sea en línea.

## Programa

| Sesión | Enfoque | Contenidos |
| --- | --- | --- |
| **01** | Fundamentos y calidad del dato | Entorno QGIS, formatos vectoriales, sistemas de referencia y carga de capas. |
| **02** | Tablas y cruces | Limpieza de datos, uniones espaciales, integración de planillas y validación de tipos. |
| **03** | Análisis | Consultas, campos calculados, filtros y selección de zonas de interés. |
| **04** | Comunicación | Simbología, composición cartográfica y exportación para impresión o medios digitales. |

Consulta el [syllabus completo](Syllabus-Curso-QGIS.pdf) para revisar el detalle del programa.

## Instructor

**Jorge Ulloa Roa**, geógrafo y fundador de ConMapas. Su trabajo combina análisis espacial, gestión de evidencia geográfica y visualización territorial.

[Conocer su trabajo y contactar →](https://julloa.space)

## Convocatorias

**Fechas, cupos, modalidad y valores dependen de cada edición.** Consulta la información vigente y el contacto en el [portafolio](https://julloa.space). Este README no fija una convocatoria; los valores o formularios de ediciones anteriores pueden haber cambiado.

## Este repositorio

Contiene la presentación web del taller y su programa en PDF.

| Archivo | Contenido |
| --- | --- |
| [`index.html`](index.html) | Página de presentación del taller. |
| [`Syllabus-Curso-QGIS.pdf`](Syllabus-Curso-QGIS.pdf) | Programa descargable. |

## Vista previa local

Para revisar la página necesitas **Git**, **Python 3** y un navegador. Estos requisitos son para servir el sitio, no para ejecutar QGIS.

```sh
git clone https://github.com/geoidegeoidal/curso-qgis.git
cd curso-qgis
python -m http.server 8000 --bind 127.0.0.1
```

Abre [http://localhost:8000/](http://localhost:8000/). Si tu sistema usa el comando `python3`, úsalo en lugar de `python` en la última línea. Detén el servidor con **Ctrl+C**.

No hay un proceso de compilación ni dependencias de aplicación que instalar para esta vista previa. Las fuentes web externas necesitan conexión a Internet.
