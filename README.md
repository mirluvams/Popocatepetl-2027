
# Popocatepetl-2027

## Descripción del proyecto

El volcán Popocatépetl es el volcán más activo y monitoreado de México. Su monitoreo visual constituye una herramienta fundamental para la evaluación de su actividad superficial; sin embargo, la revisión manual de imágenes representa un proceso lento y demandante, especialmente durante periodos de alta actividad.

En este trabajo se desarrolla un **sistema de clasificación automática de imágenes del Popocatépetl**, utilizando modelos de aprendizaje profundo basados en la arquitectura **`Swin Transformer V2`**, con el objetivo de complementar el monitoreo visual realizado por el CENAPRED.

---

## Conjunto de datos

Se construyó un conjunto de datos compuesto por **240,392 imágenes**, obtenidas mediante:

- **Web scraping** de reportes técnicos.
- **Capturas de transmisiones en vivo** en YouTube.

---

## Etiquetado y clasificación

Se diseñó una **herramienta propia de etiquetado manual** mediante una interfaz gráfica.

Se estableció una clasificación visual operativa en **cuatro categorías**:

| Categoría | Clasificación |
|:---:|---|
| 1 | Emisión de vapor y gas |
| 2 | Emisión con ceniza |
| 3 | Sin emisión visible |
| 4 | No visible |

---

## Entrenamiento del modelo

El modelo fue entrenado mediante **aprendizaje por transferencia (`fine-tuning`)**, incorporando las siguientes técnicas:

- **Balanceo de clases**
- **Aumentación de datos**
- **Normalización**
...
---

## Resultados

Los resultados muestran un **buen desempeño en la clasificación multiclase**, destacando la capacidad del modelo para distinguir **emisiones con ceniza**, relevantes para la gestión del riesgo volcánico.

---

## Proyección

Este trabajo sienta las bases para futuros **sistemas de alerta temprana basados en visión computacional**, aplicados al monitoreo volcánico en México.

