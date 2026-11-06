# Infraestructura vial y ferroviaria en Colombia

Proyecto del Grupo 1 de EAFIT. Compara la distribución de la carga movilizada y la inversión pública entre carretera y ferrocarril en Colombia entre 2016 y 2024.

**Autores:** Sebastián Quintana, Samuel Moreno y Matías Marino.

| Archivo o carpeta | Contenido |
| --- | --- |
| [`Proyecto_con_adiciones.qmd`](Proyecto_con_adiciones.qmd) | Documento fuente de Quarto |
| `datos/` | Libro de Excel Transporte en cifras 2016–2024 |
| [`Proyecto_con_adiciones.pdf`](documentos/Proyecto_con_adiciones.pdf) | Informe ampliado en PDF |
| `documentos/Proyecto.pdf` | Versión inicial del proyecto |
| `documentos/referencias.pdf` | Documento de referencias |
| `figuras/` | Tres gráficas y una tabla extraídas del PDF ampliado |

## Consultar el informe

La entrega incluye el archivo fuente de Quarto y el PDF del informe completo. El PDF permite consultar el texto, las referencias, las figuras, la declaración de uso de IA y los aportes de cada integrante.

## Generar el informe

Con Quarto instalado, ejecuta este comando desde la raíz del repositorio:

```bash
quarto render Proyecto_con_adiciones.qmd --to html
```

Para generar un PDF, usa `--to pdf` y ten disponible una distribución de LaTeX. El documento usa las imágenes de `figuras/` como archivos estáticos.
