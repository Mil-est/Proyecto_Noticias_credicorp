# Proyecto_Noticias_credicorp

1. Conceptos
Se crea un df con una lista de conceptos relacionados al grupo credicorp:
- BCP (para estás siglas se pide también la palabra "Perú" para no confundirlo)
- Credicorp
- YAPE
- Mibanco
- Tarjeta IO
- Banco de Crédito
- Grupo Romero
- Tenpo
- Krealo

2. Búsqueda de noticias
Se hace uso de RSS de Google News, para ello se usa el paquete **feedparser**
https://feedparser.readthedocs.io/en/latest/
Es una de las herramientas más populares y robustas en Python para descargar y procesar fuentes de contenido web, como canales RSS, Atom y RDF.

3. Transformar Link

se usa el paquete **googlenewsdecoder** que está diseñada específicamente para descifrar o decodificar enlaces internos generados por Google News y convertirlos a sus URL originales

4. La información se presenta de forma simple ne Power BI para su revisión:

![alt text](image.png)

Incluso si se realiza una búsqueda del contenido de la noticia (CARPETA:WEB SCRAPPING) se puede tener una ventana emergente que muestre parte de ella como previsualización antes de decidir ingresar al URL:
![alt text](image-1.png)
