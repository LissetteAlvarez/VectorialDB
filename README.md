# Bases de datos vectoriales

Una base de datos vectorial (_vector database_) es un tipo especializado de base de datos que indexa y almacena 'embeddings' vectoriales. Estas BD están específicamente diseñadas para gestionar la complejidad y la escala de los datos vectoriales (_embeddings_).  Proporcionan **capacidades optimizadas de almacenamiento y consulta** y facilitan la extracción de información a alta velocidad y la realización de análisis eficades de los _embeddings_.   

Los _embeddings vectoriales_ son generados por modelos de IA y contienen información semántica esencial para comprender y ejecutar tareas complejas. Las bases de datos vectoriales permiten liberar todo el potencial de los datos vectoriales para aplicaciones como sistemas de recomendación, reconocimiento de imágenes, detección de anomalías, etc.  

Las bases de datos vectoriales ofrecen una amplia gama de funciones de gestión de datos:
* **Operaciones CRUD**: creación, lectura, actualización y eliminación de datos vectoriales. Suelen admitir actualizaciones en tiempo real, lo que permite introducir cambios dinámicos en los datos.
* **Almacenamiento y filtrado de metadatos** asociados a cada entrada vectorial: las búsquedas son más precisas y específicas, mejorando la eficacia general de la recuperación de datos.
* **Escalado horizontal**: la escalabilidad es una ventaja clave de las bases de datos vectoriales. Están diseñadas para manejar volúmenes de datos y demandas de usuarios cada vez mayores, garantizando un rendimiento óptimo y proporcionando soporte para el procesamiento distribuido y paralelo.
* **Seguridad de los datos y el control de acceso**: progeten la información sensible a través de funciones integradas para salvaguardar los datos de accesos no autorizados.

<img src="https://thedataquarry.com/posts/vector-db-4/vector-db-hosting-2.png" width=800 height=500>
  

## Set de ejemplos básicos  

1. **Pinecone** http://www.pinecone.io  
Pinecone es una base de datos vectorial en la nube gestionada a través de una sencilla API y que no requiere configuración de infraestructura.
Pinecone procesa los datos con rapidez y permite a los usuarios emplear filtros de metadatos y compatibilidad con índices dispersos y densos, lo que garantiza resultados precisos y rápidos en los distintos requisitos de búsqueda.  
[Pinecone demo](pineconedemo_vectordatabases.ipynb)  

2. **Chroma** (https://www.trychroma.com/)  
Chroma es una base de datos de incrustación de código abierto diseñada para simplificar el desarrollo de aplicaciones LLM (Large Language Model).  Su principal objetivo es facilitar la integración de conocimientos, hechos y habilidades para los LLM.  
[Código de ejemplo]  

3. **Weaviate** (https://weaviate.io)  
Weaviate es una base de datos vectorial de código abierto que se adapta a la perfección para gestionar miles de millones de objetos de datos sin problemas.  Realiza rápidamente una búsqueda 10-NN (10-Nearest Neighbors) en milisegundos entre millones de elementos.  
[Código de ejemplo]  

4. **Qdrant** (https://qdrant.tech/)  
Qdrant funciona como una base de datos vectorial que permite realizar búsquedas de similitud vectorial con facilidad. Funciona a través de un servicio API que facilita la búsqueda de los vectores de alta dimensión más estrechamente relacionados.    
[Código de ejemplo]  

5. **Faiss** (https://python.langchain.com/docs/integrations/vectorstores/faiss)  
Faiss es una biblioteca de código abierto que resuelve el reto de la búsqueda y agrupación rápida y densa de similitudes vectoriales. Ofrece métodos de búsqueda en conjuntos de vectores de distintos tamaños, incluidos los que pueden superar la capacidad de la memoria RAM. También ofrece códigos de evaluación y asistencia para el ajuste de parámetros.  
[Código de ejemplo]

