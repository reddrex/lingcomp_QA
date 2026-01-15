# Dataset Card de Lingcomp_QA

Este es un dataset creado a partir de blogs de internet y páginas en abierto sobre lingüística computacional. Contiene algunos temas de estadística, lingüística e informática 
(especialmente cuestiones relacionadas con Python, el principal lenguaje de programación para el procesamiento del lenguaje natural).

## Detalles del dataset

### Descripción del dataset

Este dataset tiene la intención de ser educativo, explicando ciertos conceptos o respondiendo preguntas relacionadas con la evolución de la disciplina o de las funciones y aspectos
básicos de Python y algunos paquetes como Wordnet o NLTK. También responde algunas cuestiones de lingüística de corpus y, por tanto, de estadística, especialmente cuestiones
de explicación de conceptos.

- **Recogido por:** @reddrex (Jorge Zamora Rey), @issyinthesky (Isabel Moyano Moreno), @MCMiguel (Mario Crespo Miguel)
- **Language(s) (NLP):** Spanish
  
## Creación del dataset
Para este dataset hemos empleado los apuntes de la asignatura de Lingüística computacional del grado de Lingüística y lenguas aplicadas de la universidad de Cádiz, y algunas
cuestiones de la asignatura de Ingeniería del lenguaje. Además, hemos añadido la información que ha aparecido en páginas web en español, especialmente blogs, encontradas a través de Bootcat
al realizar una búsqueda de términos de la lingüística computacional. Estos términos los hemos elegido de los principales temas tratados en libros específicos como el de Jurafsky y Martin de Speech and Language Processing.

Herramientas: Bootcat para la extracción de .txt de webs, Sublime text para la organización en preguntas y respuestas en JSON y la limpieza con regex.

## Links del dataset
HuggingFace: https://huggingface.co/datasets/somosnlp/LingComp_QA

Zenodo: https://zenodo.org/records/18262332

