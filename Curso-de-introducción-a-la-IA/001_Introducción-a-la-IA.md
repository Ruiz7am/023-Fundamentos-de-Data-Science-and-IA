# Introducción a la Inteligencia Artificial.

<br>

## Perfiles de personas que trabajan con IA.

- Quienes **investigan** modelos, algoritmos y arquitecturas de la IA.
- Equipos que **usan** los modelos creados y con estos **construyen aplicaciones** para otras personas.
- Las personas que **usan aplicaciones** de IA en su día a día.

Aprender esto es útil para entender la IA y las herramientas que vayamos a utlizar en nuestro trabajo.

## ¿Cómo funciona?

La **inteligencia artificial** es el campo de teorías para **crear sistemas computacionales** que **realicen tareas** consideradas **propias del intelecto humano**, para esto se necesitan datos con los cuales se le entrena a la computadora en como debería "pensar", este proceso se llama entrenamiento, y si lo hacemos bien, la computadora podrá realizar relaciones entre los datos para así clasificar o hacer predicciones.

Dentro del aprendizaje automático, existe el **aprendizaje supervisado** y **no supervizado**.

- **Aprendizaje Supervisado**: Aprende de datos que han sido etiquetados para ayudarle a la computadora a encontrar patrones.
- **Aprendizaje no supervisado**: Aprende de datos sin etiquetar.

Alguanas veces queremos aprender cosas mas complejas de los datos, pero los modelos tradicionales de machine learning no lo logran. Afortunadamente dentro del aprendizaje automático, también existe un campo que utiliza Datos Supervisados + Datos no supervisados junto a **algoritmos** muy especiales llamados **redes neuronales**.

Las **redes neuronales** dan pie a un subcampo de machine learning llamado **aprendizaje profundo (deep learning)**, estas redes simulan cómo funcionan las neuronas de nuestro cerebro, cada neurona se activa, se desactiva y pasa información a otras neuronas de acuerdo a los datos que le enviemos, así se entrena el modelo.

Dentro del **deep learning** encontramos uno de los campos más revolucionarios de la inteligencia artificial, el **Procesamiento de Lenguaje Natural**, su objetivo es investigar cómo las computadoras, **pueden analizar, simular y resolver problemas propios del lenguaje humano**; es un campo muy interesante con muchos retos por resolver, uno de los mas importantes, era lograr que una computadora entendiera el contexto de una misma palabra en distintas oraciones o en textos muy largos.  
Para resolver este desafío, en 2017 se publicó un artículo que explicaba que podían mejorar el desempeño de estas redes neuronales si utlizaban funciones propias de la cognición humana, como la Atención. Por ejemplo, la palabra "reina" tiene significados muy disitintos si hablamos de abejas, un juego de cartas o la monarquía de un país.

Gracias a la **función de atención** una computadora puede analizar como otras palabras tienen probabilidades mayores o menores de influir en el significado total de la oración. La función de atención y las redes neuronales dieron pie a los **Transformers**, una nueva arquitectura para crear modelos de inteligencia artificial y la pieza fundamental en herramientas como **ChatGPT**, de hecho, GPT significa **Generative Pretrained Transformer** (Transformer Generativo Preentrenado) su gran logro es ser excelente determinando cual es la siguiente palabra más probable en un texto sin olvidar miles y miles de palabras anteriores, así es como mantiene consistencia en el mensaje.

## ¿Cómo se construyen estas herrmanientas? como ChatGPT

Todos estos modelos anteriores son la base para desarrollar múltiples herramientas y se conocen como m**odelos fundacionales**, éstos son grandes modelos de inteligencia artificial que se entrenan en una amplia gama de datos y luego se pueden ajustar para realizar tareas especificas.

En el caso del **procesamiento del lenuaje natural** estos grandes modelos fundacionales se llaman **LLM (Large Language Models)** y son como cerebros digitales que aprenden de una gran cantidad de información y luego usan ese conocimiento para hacer muchas cosas diferentes, en este caso generar texto.  
Expertos en ciencias de datos, machine learning, desarrollo backend, cloud engineering, investigan qué modelos fundacionales se han creado y los adaptan para implementar en productos que nos ayuden a resolver problemas en el día a día.

GPT es un tipo de **IA llamada Generativa**, porque es capaz de generar de lo que ha aprendido en el pasado. Estos modelos generativos son una gran ayuda para crear contenido en nuestro día a día.  
Por ejemplo podemos utlilizar ia generativa en aplicaciones como ChatGPT o Google Gemini para trabajar con texto; Midjourney, Dall-E o Stable Diffusion para trabajar con imagen, y MusicLM u Otter para trabajar con audio.

## ¿Cómo utilizamos estas herramientas de IA Generativa?

Aquí es donde entran los **prompts**  
Un prompt es una i**nstrucción o frase de máximo 400 caracteres** (según la recomendación de OpenAI) para describir lo que queremos lograr con la computadora, saber hacer **prompts de calidad** es la clave para tener resultados útiles y confiables; un buen prompt debe ser claro, escribir especificamente lo que queremos lograr, y entregar contexto o datos relevantes cuando sea necesario.  
Por ejemplo:

Un mal prompt seria:

```
Enseñame de Física
```

En cambio un buen prompt seria:

```
Eres profesor de Astrofísica en una universidad. 
Vas a dar una clase a personas sin experiencia sobre la 
Teoria de la relatividad de Einstein. 
Explica el concepto y para qué sirve esa teoría en 
términos simples y con analogías adecuadas 
para niños de 10 años. Limita tu respuesta a 4 parrafos.
```
