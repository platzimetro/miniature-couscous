#### ¿Cuál es la diferencia entre un campo de tipo objeto y un campo de tipo anidado?
- **Que el campo de tipo objeto guarda un sólo objeto individual, mientras que el campo de tipo anidado guarda una lista de objetos.**

#### minimum_should_match permite 
- **X: El número mínimo de consultas tipo Match que Should permite para retornar valores.**

#### La URI para manipular las propiedades del mapeo de un índice es...
- **_mapping**

#### Para un campo sobre el cual queramos buscar valores de texto exacto, usamos el siguiente tipo de dato:
- **X: text**

#### Si queremos obtener solo el documento sin toda la metadata usamos la URI:
- **_source**

#### Si tenemos campo de tipo texto, para hacer búsquedas de texto completo sobre él usamos la consulta:
- **match**

#### ¿Cuáles de las siguientes cláusulas no influyen en el puntaje?
- **Must Not y Filter**

#### ¿Cuáles de las siguientes cláusulas representan el & lógico (AND)?
- **Filter y Must**

#### Para obtener solamente el campo edad de un usuario en vez de todo el documento, indicamos en el cuerpo de la consulta:
- **_source: ["edad"]**

#### ¿Cuál de los siguientes tipos de datos representa una fecha?
- **date**

#### Si queremos indicar un valor por defecto para calcular agregaciones en documentos que no tienen valor, usamos:
- **missing**

#### Si tenemos campo de tipo keyword, y queremos hacer una consulta sobre su valor exacto, usamos...
- **term**

#### Si una búsqueda anidada encuentra un objeto anidado, la búsqueda retorna:
- **Todo el documento raíz que contiene al objeto anidado.**

#### ¿Qué no se puede hacer con el verbo GET?
- **Manipular el mapeo de un índice.**

#### Dentro de un documento tenemos un campo de tipo objeto llamado vehículo, y dentro de este objeto existe el campo modelo. Para acceder a él usamos:
- **vehículo.modelo**

#### ¿Cuál cláusula representa el OR lógico?
- **Should**

#### Para realizar consultas de text simples usamos:
- **simple_query_string**

#### Las réplicas de los shard primarios se almacenan en:
- **Un nodo distinto al shard primario.**

#### ¿Cuál de las siguientes afirmaciones es falsa?
- **La indexación de documentos se hace en tiempo real.**

#### De las siguientes consultas, indica cuál actualiza parcialmente un documento.
- **POST /usuarios/_update/1**

#### ¿Cuál es el nombre que usamos para crear agregaciones?
- **aggs**

#### El tipo de dato para crear objetos anidados es:
- **nested**

#### ¿Cuál de las siguientes consultas crea un documento con el ID autogenerado?
- **POST /usuarios/_doc**

#### ¿Cuál de los siguientes tipos de datos representa un número flotante (con decimales)?
- **double**

#### Las consultas de rango aplican a:
- **Números y fechas**

#### ¿Qué caso de uso no está contemplado para Elasticsearch?
- **Usar la herramienta como una base de datos relacional.**

#### Indica la URI para hacer una búsqueda sobre los documentos existentes.
- **_search**

#### En una búsqueda los documentos retornados vienen ordenados por defecto usando:
- **El puntaje**

#### ¿Cuál es la URI para acceder a los documentos?
- **_doc**

#### Los siguientes operadores son válidos para las consultas de rango
- **gte, gt, lte, lt**
