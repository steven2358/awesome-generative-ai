# Awesome Generative AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[English](README.md)/[繁體中文](README_zh_TW.md)
/Español

> Una lista curada de los proyectos y servicios más innovadores de Inteligencia Artificial Generativa.

La Inteligencia Artificial Generativa es una tecnología que crea contenido original como imágenes, sonidos y textos
mediante el uso de algoritmos de aprendizaje automático entrenados con grandes cantidades de datos. A diferencia de
otras formas de IA, es capaz de generar resultados únicos y nunca antes vistos, como imágenes fotorrealistas, arte
digital, música y escritura. Estos resultados suelen tener un estilo propio y, a veces, son difíciles de distinguir de
las obras humanas. La IA Generativa tiene una amplia gama de aplicaciones en campos como el arte, el entretenimiento, el
marketing, la academia y la informática.

Se invita a contribuir a esta lista. Antes de enviar sus sugerencias, revise
las [Pautas de Contribución](CONTRIBUTING.md) para asegurarse de que sus entradas cumplan con los criterios. Añada
enlaces mediante [pull requests](https://github.com/steven2358/awesome-generative-ai/pulls) o cree
un [issue](https://github.com/steven2358/awesome-generative-ai/issues) para iniciar una discusión. Se pueden encontrar
más proyectos en la [Lista de Descubrimientos](DISCOVERIES.md), donde mostramos una amplia gama de proyectos novedosos
de IA Generativa.

## Contenidos

- [Lecturas sugeridas](#lecturas-sugeridas)
- [Texto](#texto)
- [Programación](#programación)
- [Agentes](#agentes)
- [Imagen](#imagen)
- [Video](#video)
- [Audio](#audio)
- [Otros](#otros)
- [Materiales de aprendizaje](#materiales-de-aprendizaje)
- [Otras listas](#otras-listas)

## Lecturas sugeridas

- [Cómo los Modelos de Lenguaje de Gran Escala Transformarán la Ciencia, la Sociedad y la IA](https://hai.stanford.edu/news/how-large-language-models-will-transform-science-society-and-ai) -
  Artículo que resume las capacidades y limitaciones del modelo GPT-3, y su impacto potencial en la sociedad. Por Alex
  Tamkin y Deep Ganguli, 5 de febrero de 2021.
- [IA Generativa: Un Nuevo Mundo Creativo](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/) - Un
  examen exhaustivo de la industria de la IA generativa, ofreciendo una perspectiva histórica y un análisis profundo del
  ecosistema de la industria. Por Sonya Huang, Pat Grady y GPT-3, 19 de septiembre de 2022.
- [Una Fiesta de Presentación para la IA Generativa, la Nueva Locura de Silicon Valley](https://www.nytimes.com/2022/10/21/technology/generative-ai.html) -
  Artículo sobre el auge de la IA generativa, particularmente el éxito del generador de imágenes Stable Diffusion, y las
  controversias asociadas. New York Times, 21 de octubre de 2022.
- [La Nueva Racha Creativa de la IA Desata una Fiebre del Oro en Silicon Valley](https://www.wired.com/story/ais-new-creative-streak-sparks-a-silicon-valley-gold-rush/) -
  Artículo sobre el creciente entusiasmo e inversión en startups de IA generativa, con varias industrias explorando sus
  aplicaciones potenciales. Wired, 27 de octubre de 2022.
- [ChatGPT Anuncia una Revolución Intelectual](https://www.wsj.com/articles/artificial-intelligence-generative-ai-chatgpt-kissinger-84512912) -
  Un artículo de opinión por Henry Kissinger, Eric Schmidt y Daniel Huttenlocher. Wall Street Journal, 24 de febrero de
    2023.

### Avances destacados

- [API de OpenAI](https://openai.com/blog/openai-api/) - Anuncio de la API de OpenAI para modelos de IA de propósito
  general basados en texto a texto con GPT-3. Blog de OpenAI, 11 de junio de 2020.
- [GitHub Copilot](https://github.blog/2021-06-29-introducing-github-copilot-ai-pair-programmer/) - Anuncio de Copilot,
  un nuevo programador asistente de IA que te ayuda a escribir mejor código. Blog de GitHub, 29 de junio de 2021.
- [DALL·E 2](https://openai.com/blog/dall-e-2/) - Anuncio del lanzamiento de DALL·E 2, un sistema avanzado de generación
  de imágenes con mejor resolución, capacidades ampliadas de creación de imágenes y varias medidas de seguridad. Blog de
  OpenAI, 6 de abril de 2022.
- [Lanzamiento Público de Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release) - Anuncio del
  lanzamiento público de Stable Diffusion, un modelo de generación de imágenes basado en IA entrenado con un amplio
  scrapeo de internet y licenciado bajo una licencia Creative ML OpenRAIL-M. Blog de Stable Diffusion, 22 de agosto de
    2022.
- [ChatGPT](https://openai.com/blog/chatgpt/) - Anuncio de ChatGPT, un modelo conversacional entrenado para responder
  preguntas de seguimiento, admitir errores, desafiar premisas incorrectas y rechazar solicitudes inapropiadas. Blog de
  OpenAI, 30 de noviembre de 2022.
- [Búsqueda de Bing](https://blogs.microsoft.com/blog/2023/02/07/reinventing-search-with-a-new-ai-powered-microsoft-bing-and-edge-your-copilot-for-the-web/) -
  Microsoft anuncia una nueva versión de su motor de búsqueda Bing, impulsado por un modelo de OpenAI de próxima
  generación. Blog de Microsoft, 7 de febrero de 2023.
- [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) - Llama LLM, un modelo de lenguaje de gran
  escala con 65 mil millones de parámetros desarrollado por Meta. Meta, 23 de febrero de 2023. #opensource
- [GPT-4](https://openai.com/research/gpt-4) - Anuncio de GPT-4, un modelo multimodal de gran escala. Blog de OpenAI, 14
  de marzo de 2023.
- [DALL·E 3](https://openai.com/index/dall-e-3/) - Anuncio del generador de imágenes DALL·E 3. Blog de OpenAI, 20 de
  septiembre de 2023.
- [Sora](https://openai.com/research/video-generation-models-as-world-simulators) - Presentación de Sora, un modelo de
  generación de video a gran escala. OpenAI, 15 de febrero de 2024.

## Texto

### Modelos

- [API de OpenAI](https://openai.com/api/) - La API de OpenAI proporciona acceso a los modelos GPT-3 y GPT-4, que
  realizan una amplia variedad de tareas de lenguaje natural, y Codex, que traduce lenguaje natural a código.
- [Gopher](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) -
  Gopher de DeepMind es un modelo de lenguaje con 280 mil millones de parámetros.
- [OPT](https://huggingface.co/facebook/opt-350m) - Open Pretrained Transformers (OPT) de Facebook es una suite de
  transformadores preentrenados solo para
  decodificación. [Anuncio](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/). [Generación de texto OPT-175B](https://opt.alpa.ai/)
  alojado por Alpa.
- [Bloom](https://huggingface.co/docs/transformers/model_doc/bloom) - BLOOM de Hugging Face es un modelo similar a GPT-3
  que ha sido entrenado en 46 idiomas diferentes y 13 lenguajes de programación. #opensource
- [Llama](https://www.llama.com/) - Modelo de lenguaje de gran escala de código abierto de Meta. #opensource
- [Claude](https://claude.ai/) - Habla con Claude, un asistente de IA de Anthropic.
- [Vicuna-13B](https://lmsys.org/blog/2023-03-30-vicuna/) - Un chatbot de código abierto entrenado afinando LLaMA con
  conversaciones compartidas por usuarios recopiladas de ShareGPT. #opensource
- [Mistral](https://mistral.ai/en/models) - Modelos LLM de código abierto de última generación por Mistral AI.
  #opensource
- [Grok](https://grok.x.ai/) - Un LLM de xAI con [código abierto](https://github.com/xai-org/grok-1) y pesos abiertos.
  #opensource
- [Qwen](https://qwenlm.github.io/) - Una serie de LLMs desarrollados de forma independiente por Alibaba
  Cloud. [#opensource](https://github.com/QwenLM/Qwen)

### Chatbots

- [ChatGPT](https://chatgpt.com/) - ChatGPT de OpenAI es un modelo de lenguaje de gran escala que interactúa de manera
  conversacional.
- [Copilot](https://copilot.microsoft.com/) - Un compañero de IA diario de Microsoft.
- [Gemini](https://gemini.google.com/) - Una familia de modelos de lenguaje de gran escala multimodal desarrollados por
  Google Deepmind.
- [Meta AI](https://www.meta.ai/) - Asistente de IA de Meta para realizar tareas, crear imágenes generadas por IA,
  obtener respuestas. Construido sobre Llama LLM.
- [DeepSeek](https://www.deepseek.com/) - LLMs de última generación para aplicaciones empresariales, de consumo y
  científicas. #opensource
- [GPTBots.ai](https://www.gptbots.ai/es_ES/) - GPTBots ayuda a las empresas a aprovechar la IA con agentes inteligentes para
  servicio al cliente, búsqueda empresarial y análisis de datos, haciendo que la IA trabaje para usted.
- [Character.AI](https://character.ai/) - Character.AI te permite crear personajes y chatear con ellos.
- [Pi](https://pi.ai) - Una plataforma de IA personalizada disponible como asistente digital.
- [Qwen](https://chat.qwenlm.ai/) - Chatbot Qwen con generación de imágenes, procesamiento de documentos, integración de
  búsqueda web, comprensión de videos, etc.
- [Le Chat](https://chat.mistral.ai/) - Chatea con los modelos de lenguaje de última generación de Mistral AI.

### Interfaz personalizada

- [LibreChat](https://librechat.ai/) - LibreChat es una interfaz de chat gratuita y de código abierto para asistentes de
  IA. [#opensource](https://github.com/danny-avila/LibreChat).
- [Chatbot UI](https://www.chatbotui.com/) - Una interfaz de ChatGPT de código
  abierto. [#opensource](https://github.com/mckaywrigley/chatbot-ui).

### Motores de búsqueda

- [Perplexity AI](https://www.perplexity.ai/) - Herramientas de búsqueda impulsadas por IA.
- [Metaphor](https://metaphor.systems/) - Búsqueda impulsada por modelos de lenguaje.
- [Phind](https://phind.com/) - Motor de búsqueda basado en IA.
- [You.com](https://you.com/) - Un motor de búsqueda construido sobre IA que proporciona a los usuarios una experiencia
  de búsqueda personalizada mientras mantiene sus datos 100% privados.
- [Komo](https://komo.ai/) - Un motor de búsqueda impulsado por IA.

### Motores de búsqueda locales

- [privateGPT](https://github.com/imartinez/privateGPT) - Haz preguntas a tus documentos sin conexión a internet,
  utilizando el poder de los LLMs.
- [quivr](https://github.com/StanGirard/quivr) - Vuelca todos tus archivos y chatea con ellos usando tu segundo cerebro
  de IA generativa utilizando LLMs y embeddings.

### Herramientas de escritura asistida

- [Jasper](https://www.jasper.ai/) - Crea contenido más rápido con inteligencia artificial.
- [Compose AI](https://www.compose.ai/) - Compose AI es una extensión gratuita de Chrome que reduce tu tiempo de
  escritura en un 40% con autocompletado impulsado por IA.
- [Rytr](https://rytr.me/) - Rytr es un asistente de escritura de IA que te ayuda a crear contenido de alta calidad.
- [wordtune](https://www.wordtune.com/) - Asistente personal de escritura.
- [HyperWrite](https://hyperwriteai.com/) - HyperWrite te ayuda a escribir con confianza y a terminar tu trabajo más
  rápido desde la idea hasta el borrador final.
- [Moonbeam](https://www.gomoonbeam.com/) - Mejores blogs en una fracción del tiempo.
- [copy.ai](https://www.copy.ai/) - Escribe mejores copias de marketing y contenido con IA.
- [ChatSonic](https://writesonic.com/chat) - Un asistente impulsado por IA que permite la creación de texto e imágenes.
- [Anyword](https://anyword.com/) - El asistente de escritura de IA de Anyword genera copias efectivas para cualquier
  persona.
- [Hypotenuse AI](https://www.hypotenuse.ai/) - Convierte unas pocas palabras clave en artículos originales,
  descripciones de productos y copias para redes sociales.
- [Lavender](https://www.lavender.ai/) - El asistente de correos electrónicos de Lavender te ayuda a obtener más
  respuestas en menos tiempo.
- [Lex](https://lex.page/) - Un procesador de texto con inteligencia artificial integrada, para que escribas más rápido.
- [Jenni](https://jenni.ai/) - Jenni es el asistente de escritura definitivo que te ahorra horas de ideación y tiempo de
  escritura.
- [LAIKA](https://www.writewithlaika.com/) - LAIKA entrena una inteligencia artificial en tu propia escritura para crear
  un socio creativo personalizado.
- [QuillBot](https://quillbot.com) - Herramienta de parafraseo impulsada por IA.
- [Postwise](https://postwise.ai/) - Escribe tweets, programa publicaciones y haz crecer tu audiencia usando IA.
- [Copysmith](https://copysmith.ai/) - Solución de creación de contenido con IA para empresas y comercio electrónico.

### Complementos para ChatGPT

- [WebChatGPT](https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn) -
  Aumenta tus indicaciones de ChatGPT con resultados relevantes de la web.
- [GPT para Sheets y Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654) -
  Extensión de ChatGPT para Google Sheets y Google Docs.
- [Resumen de YouTube con ChatGPT](https://chrome.google.com/webstore/detail/youtube-summary-with-chat/nmmicjeknamkfloonkhhcjmomieiodli) -
  Usa ChatGPT para resumir videos de YouTube.
- [ChatGPT Prompt Genius](https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo) -
  Descubre, comparte, importa y utiliza las mejores indicaciones para ChatGPT y guarda tu historial de chat localmente.
- [ChatGPT para Motores de Búsqueda](https://chrome.google.com/webstore/detail/chatgpt-for-search-engine/feeonheemodpkdckaljcjogdncpiiban) -
  Muestra la respuesta de ChatGPT junto a los resultados de búsqueda de Google, Bing y DuckDuckGo.
- [ShareGPT](https://sharegpt.com/) - Comparte tus conversaciones de ChatGPT y explora conversaciones compartidas por
  otros.
- [Merlin](https://merlin.foyer.work/) - Extensión de ChatGPT Plus en todos los sitios web.
- [ChatGPT Writer](https://chatgptwriter.ai/) - Genera correos electrónicos y mensajes completos usando ChatGPT AI.
- [ChatGPT para Jupyter](https://github.com/TiesdeKok/chat-gpt-jupyter-extension) - Agrega varias funciones de ayuda en
  Jupyter Notebooks y Jupyter Lab, impulsadas por ChatGPT.
- [editGPT](https://www.editgpt.app/) - Revisa, edita y realiza un seguimiento de los cambios en tu contenido en ChatGPT
  fácilmente.
- [Forefront](https://www.forefront.ai/) - Una mejor experiencia de ChatGPT.

### Herramientas de productividad

- [ChatPDF](https://www.chatpdf.com/) - Chatea con cualquier PDF.
- [Mem](https://mem.ai/) - Mem es el primer espacio de trabajo impulsado por IA del mundo que está personalizado para
  ti. Amplifica tu creatividad, automatiza lo mundano y mantente organizado automáticamente.
- [Taskade](https://www.taskade.com/) - Esquematiza tareas, notas, listas estructuradas generadas y mapas mentales con
  Taskade AI.
- [Notion AI](https://www.notion.so/product/ai) - Escribe mejores notas y documentos de manera más eficiente.
- [Nekton AI](https://nekton.ai) - Automatiza tus flujos de trabajo con IA. Describe tus flujos de trabajo paso a paso
  en lenguaje sencillo.
- [Rewind](https://www.rewind.ai/) - Rewind es una IA personalizada impulsada por todo lo que has visto, dicho o
  escuchado.
- [NotebookLM](https://notebooklm.google/) - Una herramienta de investigación y toma de notas en línea para interactuar
  con documentos, impulsada por Google Gemini.

### Herramientas para reuniones

- [Otter.ai](https://otter.ai/) - Un asistente de reuniones que graba audio, escribe notas, captura diapositivas
  automáticamente y genera resúmenes.
- [Cogram](https://www.cogram.com/) - Cogram toma notas automáticas en reuniones virtuales e identifica elementos de
  acción.
- [Sybill](https://www.sybill.ai/) - Sybill genera resúmenes de llamadas de ventas, incluidos próximos pasos, puntos de
  dolor y áreas de interés, combinando transcripciones e ideas basadas en emociones.
- [Loopin AI](https://www.loopinhq.com/) - Loopin es un espacio de trabajo colaborativo para reuniones que no solo te
  permite grabar, transcribir y resumir reuniones usando IA, sino que también organiza automáticamente las notas de las
  reuniones sobre tu calendario.
- [Fireflies.ai](https://fireflies.ai/) - Fireflies.ai ayuda a tu equipo a transcribir, resumir, buscar y analizar
  conversaciones de voz.
- [Read AI](https://www.read.ai/) - Un copiloto de IA para donde sea que trabajes, haciendo tus reuniones, correos
  electrónicos y mensajes más productivos con resúmenes, descubrimiento de contenido y recomendaciones.

### Academia

- [Elicit](https://elicit.org/) - Elicit utiliza modelos de lenguaje para automatizar flujos de trabajo de
  investigación, como en la revisión de literatura.
- [genei](https://www.genei.io/) - Resume artículos académicos en segundos y ahorra hasta un 80 % de tiempo en tu
  investigación.
- [Explainpaper](https://www.explainpaper.com/) - Una forma más eficiente de leer artículos académicos. Carga un
  artículo, selecciona texto confuso y recibe una explicación.
- [Galactica](https://galactica.org/) - Un modelo de lenguaje grande para la ciencia. Puede resumir literatura
  académica, resolver problemas matemáticos, generar artículos de Wiki, escribir código científico, anotar moléculas y
  proteínas, y más. [Model API](https://github.com/paperswithcode/galai).
- [Consensus](https://consensus.app/search/) - Consensus es una plataforma de búsqueda que utiliza IA para encontrar
  respuestas en investigaciones científicas.
- [Synthical](https://synthical.com) - Entorno colaborativo de investigación con IA.
- [scite](https://scite.ai/) - Una plataforma para descubrir y evaluar artículos científicos.
- [SciSpace](https://typeset.io/) - Un asistente de investigación con IA para comprender literatura científica.

### Tablas de clasificación

- [Chatbot Arena](https://lmarena.ai/) - Una plataforma abierta para la evaluación colaborativa de IA, organizada por
  investigadores de UC Berkeley SkyLab y LMArena.
- [Artificial Analysis](https://artificialanalysis.ai/) - Artificial Analysis proporciona puntos de referencia objetivos
  e información para ayudar a elegir modelos de IA y proveedores de alojamiento.

### Otros generadores de texto

- [EmailTriager](https://www.emailtriager.com/) - Usa IA para redactar automáticamente respuestas a correos electrónicos
  en segundo plano.
- [AI Poem Generator](https://www.aipoemgenerator.org) - El Generador de Poemas con IA crea poemas rimados y hermosos
  sobre cualquier tema a partir de un texto inicial.

## Programación

### Asistentes de programación

- [GitHub Copilot](https://github.com/features/copilot) - GitHub Copilot utiliza OpenAI Codex para sugerir código y
  funciones completas en tiempo real, directamente desde tu editor.
- [OpenAI Codex](https://platform.openai.com/docs/guides/code/) - Un sistema de IA de OpenAI que traduce lenguaje
  natural a código.
- [Ghostwriter](https://blog.replit.com/ai) - Un compañero de programación impulsado por IA de Replit.
- [Amazon Q](https://aws.amazon.com/q/) - El asistente de AWS impulsado por IA generativa que ayuda a responder
  preguntas, escribir código y automatizar tareas.
- [tabnine](https://www.tabnine.com/) - Programa más rápido con autocompletado de líneas completas y funciones completas
  de código.
- [Stenography](https://stenography.dev/) - Documentación automática de código.
- [Mintlify](https://mintlify.com/) - Generador de documentación impulsado por IA.
- [Debuild](https://debuild.app/) - Herramienta de bajo código impulsada por IA para aplicaciones web.
- [AI2sql](https://www.ai2sql.io/) - Con AI2sql, ingenieros y no ingenieros pueden escribir fácilmente consultas SQL
  eficientes y sin errores sin conocer SQL.
- [CodiumAI](https://www.codium.ai/) - Con CodiumAI, obtienes pruebas no triviales sugeridas directamente en tu IDE,
  para que tengas confianza al realizar cambios.
- [PR-Agent](https://github.com/Codium-ai/pr-agent) - Herramienta impulsada por IA para análisis automatizado de PR,
  comentarios, sugerencias y más.
- [MutableAI](https://mutable.ai/) - Desarrollo de software acelerado por IA.
- [TurboPilot](https://github.com/ravenscroftj/turbopilot) - Un clon de copiloto autoalojado que utiliza la biblioteca
  detrás de llama.cpp para ejecutar el modelo Salesforce Codegen de 6 mil millones de parámetros en 4 GB de RAM.
- [GPT-Code UI](https://github.com/ricklamers/gpt-code-ui) - Una implementación de código abierto del intérprete de
  código de ChatGPT de OpenAI. #opensource
- [MetaGPT](https://github.com/geekan/MetaGPT) - El Marco Multi-Agente: Dada una línea de requisitos, devuelve PRD,
  diseño, tareas, repositorio.
- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - Intérprete de código de OpenAI en tu terminal,
  ejecutándose localmente.
- [Continue](https://www.continue.dev/) - Asistente de código de IA de código abierto. Conecta cualquier modelo y
  cualquier contexto para crear experiencias personalizadas de autocompletado y chat dentro del
  IDE. [#opensource](https://github.com/continuedev/continue)

### Herramientas para desarrolladores

- [co:here](https://cohere.ai/) - Cohere proporciona acceso a modelos avanzados de lenguaje grande y herramientas de
  NLP.
- [Haystack](https://haystack.deepset.ai/) - Un marco para construir aplicaciones de NLP (por ejemplo, agentes, búsqueda
  semántica, preguntas y respuestas) con modelos de lenguaje.
- [LangChain](https://langchain.com/) - Un marco para desarrollar aplicaciones impulsadas por modelos de lenguaje.
- [gpt4all](https://github.com/nomic-ai/gpt4all) - Un chatbot entrenado en una colección masiva de datos limpios de
  asistente, incluyendo código, historias y diálogos.
- [LLM App](https://github.com/pathwaycom/llm-app) - Biblioteca de Python de código abierto para construir
  canalizaciones de datos habilitadas para LLM en tiempo real.
- [LMQL](https://lmql.ai/) - LMQL es un lenguaje de consulta para modelos de lenguaje grande.
- [LlamaIndex](https://www.llamaindex.ai/) - Un marco de datos para construir aplicaciones LLM sobre datos externos.
- [Phoenix](https://phoenix.arize.com/) - Herramienta de código abierto para la observabilidad de ML que se ejecuta en
  tu entorno de cuaderno, por Arize. Monitorea y ajusta modelos LLM, CV y tabulares.
- [Cursor](https://www.cursor.so/) - Cursor es el IDE del futuro, diseñado para la programación en pareja con IA
  poderosa.
- [SymbolicAI](https://github.com/Xpitfire/symbolicai) - Un marco neuro-simbólico para construir aplicaciones con LLMs
  en el núcleo.
- [Vanna.ai](https://vanna.ai/) - Un marco RAG de Python de código abierto para generación de SQL y funcionalidad
  relacionada. [#opensource](https://github.com/vanna-ai/vanna)
- [Portkey](https://portkey.ai/) - Una plataforma completa de LLMOps para monitoreo, almacenamiento en caché y gestión
  de LLM.
- [agenta](https://github.com/agenta-ai/agenta) - Una plataforma de LLMOps de extremo a extremo de código abierto para
  ingeniería de prompts, evaluación y despliegue. #opensource
- [Together AI](https://www.together.ai/) - Entrena, ajusta y ejecuta inferencias en modelos de IA de manera rápida,
  económica y a escala de producción.
- [Gitingest](https://gitingest.com/) - Convierte cualquier repositorio Git en un resumen de texto simple de su base de
  código para que pueda ser alimentado a cualquier LLM. [#opensource](https://github.com/cyclotruc/gitingest)
- [Repomix](https://repomix.com/) - Empaqueta tu base de código en formatos amigables para
  IA. [#opensource](https://github.com/yamadashy/repomix)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Inferencia del modelo LLaMA de Meta (y otros) en C/C++ puro.
  #opensource
- [bitnet.cpp](https://github.com/microsoft/BitNet) - Marco oficial de inferencia para LLMs de 1-bit, por Microsoft.
  #opensource

### Playgrounds

- [OpenAI Playground](https://platform.openai.com/playground) - Explora recursos, tutoriales, documentación de API y
  ejemplos dinámicos.
- [Google AI Studio](https://aistudio.google.com/) - Una herramienta basada en la web para prototipar con Gemini y
  modelos experimentales.
- [GitHub Models](https://github.com/marketplace/models) - Encuentra y experimenta con modelos de IA para desarrollar
  una aplicación de IA generativa.

### Implementación local de LLM

- [Ollama](https://github.com/ollama/ollama) - Configura y ejecuta modelos de lenguaje grande localmente.
- [Open WebUI](https://github.com/open-webui/open-webui) - Una plataforma de IA autoalojada extensible, rica en
  funciones y fácil de usar, diseñada para operar completamente sin conexión. #opensource
- [Jan](https://jan.ai/) - Ejecuta LLMs como Mistral o Llama2 localmente y sin conexión en tu computadora, o conéctate a
  APIs de IA remotas. [#opensource](https://github.com/janhq/jan)
- [Msty](https://msty.app/) - Una interfaz sencilla y poderosa para modelos de IA locales y en línea.
- [PyGPT](https://pygpt.net/) - Asistente de IA personal de escritorio con chat, visión, agentes, generación de
  imágenes, herramientas y comandos, control por voz y más. #opensource
- [LLM](https://llm.datasette.io/) - Una utilidad CLI y biblioteca de Python para interactuar con Modelos de Lenguaje
  Grande, remotos y locales. [#opensource](https://github.com/simonw/llm)

## Agentes

### Agentes autónomos

- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - Un intento experimental de código abierto para hacer que GPT-4
  sea completamente autónomo.
- [babyagi](https://github.com/yoheinakajima/babyagi) - Un sistema de gestión de tareas impulsado por IA.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Ensambla, configura y despliega agentes de IA autónomos en tu
  navegador.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Especifica lo que quieres construir, la IA pide
  aclaraciones y luego lo construye.
- [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer) - Ingeniería de prompts automatizada. Genera,
  prueba y clasifica prompts para encontrar los mejores.
- [MetaGPT](https://github.com/geekan/MetaGPT) - El Marco Multi-Agente: Dada una línea de requisitos, devuelve PRD,
  diseño, tareas, repositorio.
- [AutoGen](https://github.com/microsoft/autogen) - AutoGen es un marco que permite el desarrollo de aplicaciones LLM
  utilizando múltiples agentes que pueden conversar entre sí para resolver tareas.
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) - Herramienta de desarrollo que escribe aplicaciones escalables
  desde cero mientras el desarrollador supervisa la implementación.
- [Devin](https://devin.ai/) - Un ingeniero de software autónomo impulsado por IA de Cognition Labs.
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - Un agente autónomo diseñado para navegar por las complejidades
  de la ingeniería de software. #opensource
- [Davika](https://github.com/stitionai/devika) - Un ingeniero de software impulsado por IA. #opensource

### Asistentes personalizados

- [Poe](https://poe.com/) - Poe da acceso a una variedad de bots.
- [GPT Builder](https://chat.openai.com/gpts/editor) - Asistente para crear asistentes basados en GPT.
- [GPTStore](https://gptstore.ai/) - Encuentra GPTs útiles. Comparte tus propios GPTs.

## Imágenes

### Modelos

- [DALL·E 2](https://openai.com/dall-e-2/) - DALL·E 2 de OpenAI es un nuevo sistema de IA que puede crear imágenes y
  arte realistas a partir de una descripción en lenguaje natural.
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) - Stable Diffusion de Stability AI es un
  modelo de texto a imagen de última generación que genera imágenes a partir de texto. #opensource
- [Midjourney](https://www.midjourney.com/) - Midjourney es un laboratorio de investigación independiente que explora
  nuevos medios de pensamiento y expande los poderes imaginativos de la especie humana.
- [Imagen](https://imagen.research.google/) - Imagen de Google es un modelo de difusión de texto a imagen con un grado
  sin precedentes de fotorealismo y un profundo nivel de comprensión del lenguaje.
- [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/) - Make-A-Scene de Meta
  es un método generativo de IA multimodal que pone el control creativo en manos de las personas que lo usan,
  permitiéndoles describir e ilustrar su visión tanto a través de descripciones textuales como de bocetos libres.
- [DragGAN](https://github.com/XingangPan/DragGAN) - Arrastra tu GAN: Manipulación interactiva basada en puntos en el
  Manifold Generativo de Imágenes.

### Servicios

- [Craiyon](https://www.craiyon.com/) - Craiyon, anteriormente DALL-E mini, es un modelo de IA que puede dibujar
  imágenes a partir de cualquier texto inicial.
- [DreamStudio](https://beta.dreamstudio.ai/) - DreamStudio es una interfaz fácil de usar para crear imágenes utilizando
  el modelo de generación de imágenes Stable Diffusion.
- [Artbreeder](https://www.artbreeder.com/) - Artbreeder es un nuevo tipo de herramienta creativa que potencia la
  creatividad de los usuarios al facilitar la colaboración y la exploración.
- [GauGAN2](http://gaugan.org/gaugan2/) - GauGAN2 es una herramienta robusta para crear arte fotorrealista utilizando
  una combinación de palabras y dibujos, ya que integra mapeo de segmentación, inpainting y producción de texto a imagen
  en un solo modelo.
- [Magic Eraser](https://www.magiceraser.io/) - Elimina elementos no deseados de imágenes en segundos.
- [Imagine by Magic Studio](https://magicstudio.com/imagine) - Una herramienta de Magic Studio que te permite expresarte
  simplemente describiendo lo que tienes en mente.
- [Alpaca](https://www.getalpaca.io/) - Complemento de Photoshop para Stable Diffusion.
- [Patience.ai](https://www.patience.ai/) - Patience.ai es una aplicación para crear imágenes con Stable Diffusion, una
  IA de vanguardia desarrollada por Stability.AI.
- [GenShare](https://www.genshare.io/) - Genera arte en segundos de forma gratuita. Posee y comparte lo que creas. Un
  estudio generativo multimedia que democratiza el diseño y la creatividad.
- [Playground](https://playground.com/) - Playground es un creador de imágenes con IA en línea gratuito. Úsalo para
  crear arte, publicaciones en redes sociales, presentaciones, carteles, videos, logotipos y más.
- [Pixelz AI Art Generator](https://pixelz.ai/) - Pixelz AI Art Generator te permite crear arte increíble a partir de
  texto. Algoritmos realistas de Stable Diffusion, CLIP Guided Diffusion y PXL·E disponibles.
- [modyfi](https://www.modyfi.io/) - El editor de imágenes que siempre quisiste. Herramientas creativas impulsadas por
  IA en tu navegador. Colaboración en tiempo real.
- [Ponzu](https://www.ponzu.ai/) - Ponzu es tu generador de logotipos con IA gratuito. Construye tu marca con logotipos
  diseñados creativamente en segundos, usando solo tu imaginación.
- [PhotoRoom](https://www.photoroom.com/) - Crea fotos de productos y retratos usando solo tu teléfono. Elimina el
  fondo, cambia el fondo y muestra productos.
- [Avatar AI](https://avatarai.me/) - Crea tus propios avatares generados por IA.
- [ClipDrop](https://clipdrop.co/) - Crea imágenes profesionales sin un estudio fotográfico, impulsado
  por [stability.ai](https://stability.ai/).
- [Lensa](https://prisma-ai.com/lensa) - Una aplicación de edición de imágenes todo en uno que incluye la generación de
  avatares personalizados utilizando Stable Diffusion.
- [RunDiffusion](https://rundiffusion.com/) - Espacio de trabajo basado en la nube para crear arte generado por IA.
- [Ideogram](https://ideogram.ai/) - Una plataforma de texto a imagen para hacer que la expresión creativa sea más
  accesible.
- [Bing Image Creator](https://www.bing.com/images/create) - Generador de texto a imagen basado en DALLE·3 con
  características de seguridad.
- [KREA](https://www.krea.ai/) - Genera visuales de alta calidad con una IA que conoce tus estilos, conceptos o
  productos.
- [Nightcafe](https://creator.nightcafe.studio/) - NightCafe Creator es una aplicación generadora de arte con IA con
  múltiples métodos de generación de arte con IA.
- [Leonardo AI](https://leonardo.ai/) - Crea activos visuales de calidad de producción para tus proyectos con calidad,
  velocidad y estilo sin precedentes.
- [Recraft](https://www.recraft.ai/) - Una herramienta de IA que permite a los creadores generar e iterar fácilmente
  imágenes originales, arte vectorial, ilustraciones, íconos y gráficos 3D.

### Diseño gráfico

- [Brandmark](https://brandmark.io/) - Herramienta de diseño de logotipos basada en IA.
- [Gamma](https://gamma.app/) - Crea presentaciones y páginas web hermosas sin necesidad de formatear ni diseñar.
- [Microsoft Designer](https://designer.microsoft.com/) - Herramienta de diseño gráfico con IA para crear diseños
  impresionantes en un instante.

### Bibliotecas de imágenes

- [Lexica](https://lexica.art/) - Motor de búsqueda de Stable Diffusion.
- [OpenArt](https://openart.ai/) - Busca entre más de 10 millones de indicaciones y genera arte con IA mediante Stable
  Diffusion, DALL·E 2.
- [PromptHero](https://prompthero.com/) - Encuentra indicaciones optimizadas para modelos de IA como Stable Diffusion,
  ChatGPT, Midjourney, etc.
- [PromptBase](https://promptbase.com/) - Busca y vende indicaciones de los mejores especialistas en prompts.

### Bibliotecas de modelos

- [Civitai](https://civitai.com/) - Herramienta de intercambio de modelos de IA impulsada por la comunidad.
- [Stable Diffusion Models](https://rentry.org/sdmodels) - Una lista completa de checkpoints de Stable Diffusion en
  rentry.org.

### Recursos de Stable Diffusion

- [Stable Horde](https://stablehorde.net/) - Un clúster distribuido de trabajadores de Stable Diffusion basado en
  crowdsourcing.
- [DiffusionDB](https://diffusiondb.com/) - Una lista de todas las aplicaciones públicas, herramientas de desarrollo,
  guías y plugins para Stable Diffusion. [Versión Airtable](https://airtable.com/shr0HlBwbw3nZ8Ht3/tblxOCylXV8ynh7ti).
- [PublicPrompts](https://publicprompts.art/) - Una colección de indicaciones gratuitas para Stable Diffusion.
- [Stableboost](https://stableboost.ai/) - Interfaz web de Stable Diffusion que te permite generar rápidamente múltiples
  imágenes para encontrar la ideal.
- [Hugging Face Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - Materiales en Python
  para el curso en línea sobre modelos de difusión de imágenes por [@huggingface](https://github.com/huggingface).

## Video

- [Runway](https://runwayml.com/) - Herramientas innovadoras de IA, colaboración en tiempo real, edición precisa y más.
  Tu suite de creación de contenido de próxima generación.
- [Synthesia](https://www.synthesia.io/) - Crea videos a partir de texto en minutos.
- [Rephrase AI](https://www.rephrase.ai/) - Tecnología que permite la creación de videos hiperpersonalizados a escala,
  impulsando el compromiso y la eficiencia empresarial.
- [Hour One](https://hourone.ai/) - Convierte texto en video con presentadores virtuales automáticamente.
- [Colossyan](https://www.colossyan.com/) - Creador de videos enfocado en aprendizaje y desarrollo. Usa avatares de IA
  para crear videos educativos en múltiples idiomas.
- [Fliki](https://fliki.ai/) - Crea contenido de texto a video y texto a voz con voces impulsadas por IA en minutos.
- [Pictory](https://pictory.ai/) - La poderosa IA de Pictory te permite crear y editar videos de calidad profesional
  usando texto.
- [Pika](https://pika.art/) - Una plataforma de idea a video que da vida a tu creatividad.
- [Sora](https://openai.com/sora) - Un modelo de IA que puede crear escenas realistas e imaginativas a partir de
  instrucciones de texto.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - Un modelo de IA que crea videos de alta calidad y realistas
  rápidamente a partir de texto e imágenes.
- [Infinity AI](https://infinity.ai/) - Modelo base de video que te permite crear personajes y darles vida.
- [KLING AI](https://klingai.com/) - Herramientas para crear imágenes y videos imaginativos.
- [Hailuo AI](https://hailuoai.video/) - Generador de texto a video impulsado por IA.

### Avatares

- [D-ID](https://www.d-id.com/) - Crea e interactúa con avatares parlantes con solo tocar un botón.
- [HeyGen](https://app.heygen.com/) - Convierte guiones en videos parlantes con avatares de IA personalizables en
  minutos.
- [RenderNet](https://rendernet.ai/) - Herramienta para generar imágenes y videos, ofreciendo control sobre el diseño de
  personajes, la composición y el estilo.

### Animación

- [Wonder Dynamics](https://wonderdynamics.com/) - Anima, ilumina y compone personajes CG en escenas reales sin
  esfuerzo.

## Audio

### Texto a voz

- [Eleven Labs](https://beta.elevenlabs.io/) - Generador de voz impulsado por IA.
- [Resemble AI](https://www.resemble.ai/) - Generador de voz con IA y clonación de voz para texto a voz.
- [WellSaid](https://wellsaidlabs.com/) - Convierte texto en voz en tiempo real.
- [Play.ht](https://play.ht/) - Generador de voz impulsado por IA. Convierte texto en audio realista en línea.
- [podcast.ai](https://podcast.ai/) - Un podcast generado completamente por inteligencia artificial, impulsado por
  Play.ht texto a voz IA.
- [VALL-E X](https://vallex-demo.github.io/) - Modelo de lenguaje neural de códec para síntesis de voz multilingüe.
- [TorToiSe](https://github.com/neonbjb/tortoise-tts) - Sistema de texto a voz multivocal entrenado con énfasis en la
  calidad. #opensource
- [Bark](https://github.com/suno-ai/bark) - Modelo de texto a audio basado en transformadores. #opensource

### Voz a texto

- [Whisper](https://openai.com/index/whisper/) - Reconocimiento de voz robusto mediante supervisión débil a gran
  escala. [#opensource](https://github.com/openai/whisper)
- [Wispr Flow](https://wisprflow.ai/) - Dictado de voz fluido para cualquier aplicación en tu computadora.
- [Vibe Transcribe](https://thewh1teagle.github.io/vibe/) - Solución integral para transcripción de audio y video sin
  esfuerzo. [#opensource](https://github.com/thewh1teagle/vibe)
- [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Port del modelo Whisper de OpenAI en C/C++. #opensource

### Música

- [Harmonai](https://www.harmonai.org/) - Organización impulsada por la comunidad que lanza herramientas de audio
  generativo de código abierto para hacer la producción musical más accesible y divertida.
- [Mubert](https://mubert.com/) - Ecosistema de música libre de regalías para creadores de contenido, marcas y
  desarrolladores.
- [MusicLM](https://google-research.github.io/seanet/musiclm/examples/) - Modelo de Google Research para generar música
  de alta fidelidad a partir de descripciones de texto.
- [AudioCraft](https://audiocraft.metademolab.com/) - Base de código única para necesidades de audio generativo, por
  Meta. Incluye MusicGen para música y AudioGen para sonidos. #opensource
- [Stable Audio](https://stability.ai/stable-audio) - Primer producto de Stability AI para generación de música y
  efectos de sonido.
- [AIVA](https://www.aiva.ai/) - Asistente de generación musical basado en IA. Elige entre más de 250 estilos.
- [Suno AI](https://www.suno.ai/) - Cualquiera puede hacer música genial. No necesitas instrumentos, solo imaginación.
  De tu mente a la música.
- [Udio](https://www.udio.com/) - Descubre, crea y comparte música con el mundo.

## Otros

- [Diagram](https://diagram.com/) - Nuevas formas innovadoras de diseñar productos.
- [PromptBase](https://promptbase.com/) - Mercado para comprar y vender indicaciones de calidad para DALL·E, GPT-3,
  Midjourney, Stable Diffusion.
- [This Image Does Not Exist](https://thisimagedoesnotexist.com/) - Pon a prueba tu habilidad para distinguir si una
  imagen es humana o generada por computadora.
- [Have I Been Trained?](https://haveibeentrained.com/) - Verifica si tu imagen ha sido utilizada para entrenar modelos
  de arte de IA populares.
- [AI Dungeon](https://aidungeon.io/) - Un juego de aventuras narrativas en el que tú diriges y protagonizas la historia
  mientras la IA la desarrolla.
- [Clickable](https://www.clickable.so/) - Genera anuncios en segundos con IA. Anuncios hermosos, consistentes con la
  marca y altamente efectivos para todos los canales de marketing.
- [Scale Spellbook](https://scale.com/spellbook) - Crea, compara y despliega aplicaciones de modelos de lenguaje grande
  con Scale Spellbook.
- [Scenario](https://www.scenario.com/) - Activos de juegos generados por IA.
- [Teleprompter](https://github.com/danielgross/teleprompter) - IA en tu dispositivo para reuniones que escucha y
  sugiere citas carismáticas.
- [FinChat](https://finchat.io/) - Genera respuestas a preguntas sobre empresas públicas e inversores usando IA.
- [Morpher AI](https://morpher.com/ai) - Ofrece análisis e insights en tiempo real para cualquier mercado.
- [Whimsical AI](https://whimsical.com/ai/) - Mapas mentales, diagramas de flujo y herramientas visuales impulsadas por
  GPT para desarrollo rápido de ideas y organización de procesos.

## Recursos de aprendizaje

- [Learn Prompting](https://learnprompting.org/) - Curso gratuito y de código abierto sobre cómo comunicarse con
  inteligencia artificial.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Guía y recursos para ingeniería de
  prompts.
- [ChatGPT prompt engineering for developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) -
  Curso corto por Isa Fulford (OpenAI) y Andrew Ng (DeepLearning.AI).
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Ejemplos y guías para usar la API de OpenAI.
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - Estrategias y tácticas
  para obtener mejores resultados de modelos de lenguaje grande.
- [PromptPerfect](https://promptperfect.jina.ai/) - Herramienta para ingeniería de prompts.
- [Anthropic courses](https://github.com/anthropics/courses) - Cursos educativos de Anthropic.

## Más listas

- [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) - Gran lista de cuadernos de Google Colab
  para IA generativa, por [@pharmapsychotic](https://twitter.com/pharmapsychotic).
- [The Generative AI Application Landscape](https://twitter.com/sonyatweetybird/status/1584580362339962880) - Infografía
  que mapea el ecosistema de IA generativa, por [Sonya Huang](https://twitter.com/sonyatweetybird) de Sequioa Capital.
- [Startups - @builtwithgenai](https://airtable.com/shr6nfE9FOHp17IjG/tblL3ekHZfkm3p6YT) - Lista en Airtable
  por [@builtwithgenai](https://twitter.com/builtwithgenai).
- [The Generative AI Index](https://airtable.com/shrH4REIgddv8SzUo/tbl5dsXdD1P859QLO) - Lista en Airtable
  por [Scale Venture Partners](https://www.scalevp.com/generative-ai).
- [Generative AI for Games](https://twitter.com/gwertz/status/1593268767269670912) - Mapa de mercado de empresas que
  trabajan en IA generativa para juegos, por [a16z](https://a16z.com/).
- [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art) - Lista curada de herramientas,
  obras, modelos, etc. de aprendizaje profundo generativo para usos artísticos,
  por [@filipecalegario](https://github.com/filipecalegario/).
- [GPT-3 Demo](https://gpt3demo.com/) - Demostraciones, aplicaciones, ejemplos y casos de uso de GPT-3.
- [GPT-4 Demo](https://gpt4demo.com/) - Aplicaciones y casos de uso de GPT-4.
- [The Generative AI Landscape](https://github.com/ai-collection/ai-collection) - Colección de aplicaciones de IA
  generativa impresionantes.
- [Molecular design](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) - Lista de diseño molecular
  utilizando IA generativa y aprendizaje profundo.
- [Open LLMs](https://github.com/eugeneyan/open-llms) - Lista de LLMs abiertos disponibles para uso comercial.

### Listas sobre ChatGPT

- [Awesome ChatGPT](https://github.com/humanloop/awesome-chatgpt) - Lista curada de herramientas, demostraciones y
  documentación para ChatGPT y GPT-3, por [@jordn](https://github.com/jordn).
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - Colección de ejemplos de indicaciones para
  usar con el modelo ChatGPT.
- [FlowGPT](https://flowgpt.com/) - Amplifica tu flujo de trabajo con las mejores indicaciones.
- [ChatGPT Prompts for Data Science](https://github.com/travistangvh/ChatGPT-Data-Science-Prompts) - Repositorio de
  indicaciones útiles para ciencia de datos con ChatGPT.
- [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt) - Otra lista impresionante para ChatGPT.