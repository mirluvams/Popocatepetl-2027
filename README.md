# Popocatepetl-2027
El volcán Popocatépetl es uno de los sistemas volcánicos más activos y
monitoreados de México debido a su proximidad a zonas densamente pobladas
y a su historial eruptivo altamente explosivo. El monitoreo visual constituye
una herramienta fundamental para la evaluación de su actividad superficial; sin
embargo, la revisión manual de imágenes representa un proceso lento y demandante
especialmente durante periodos de alta actividad. En este trabajo se desarrolla un
sistema de clasificación automática de imágenes del Popocatépetl utilizando modelos
de aprendizaje profundo basados en la arquitectura Swin Transformer V2, con el
objetivo de complementar el monitoreo visual realizado por el CENAPRED.
Para ello, se construyó un conjunto de datos sin precedentes compuesto por
240,392 imágenes obtenidas mediante web scraping de reportes técnicos y capturas
de transmisiones en vivo. Se diseñó una herramienta propia de etiquetado manual y
se estableció una clasificación visual operativa en cuatro categorías: emisión de vapor
y gas, emisión con ceniza, sin emisión visible y no visible. El modelo fue entrenado
mediante aprendizaje por transferencia, incorporando técnicas de balanceo de clases,
aumentación de datos y normalización.
Los resultados muestran un desempeño sólido en la clasificación multiclase,
destacando la capacidad del modelo para distinguir emisiones con ceniza, relevantes
para la gestión del riesgo volcánico. Este trabajo sienta las bases para futuros
sistemas de alerta temprana basados en visión computacional aplicados al monitoreo
volcánico en México.
