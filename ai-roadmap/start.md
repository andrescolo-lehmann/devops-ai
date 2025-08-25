# Phase 1: AI Fundamentals & Large Language Models

*A comprehensive technical guide to understanding AI foundations for DevOps professionals*

# Fase 1: Fundamentos de IA y LLMs

*Guía técnica para entender los fundamentos de IA orientada a profesionales DevOps
## 🎯 **Objetivos de aprendizaje**

Al finalizar esta guía podrás:
- Entender los conceptos básicos de IA, ML y arquitecturas de Deep Learning
- Comprender las bases técnicas de los LLMs
- Evaluar características de rendimiento y criterios de selección de modelos
- Aplicar conceptos de IA de forma efectiva en contextos de DevOps e infraestructura
- Tomar decisiones informadas sobre integración de herramientas de IA en tus flujos de trabajo

---


## 📚 **Secciones del Tutorial**

### **Sección 1: Arquitectura de Sistemas de IA**

#### **Inteligencia Artificial vs Machine Learning vs Deep Learning**

**Marco Conceptual:**
Inteligencia Artificial (Conjunto principal)
├── Machine Learning (Subconjunto)
└── Deep Learning (Subconjunto especializado)


**Definiciones Técnicas:**

- **Inteligencia Artificial**: Sistemas computacionales diseñados para realizar tareas que normalmente requieren habilidades cognitivas humanas, incluyendo razonamiento, aprendizaje y toma de decisiones
- **Machine Learning**: Enfoques algorítmicos que permiten a los sistemas mejorar automáticamente su rendimiento a partir de la experiencia y el análisis de datos
- **Deep Learning**: Arquitecturas de redes neuronales con múltiples capas capaces de modelar patrones complejos en grandes conjuntos de datos

**Contexto de Implementación:**
En entornos empresariales, estas tecnologías forman una jerarquía donde los modelos de Deep Learning (como los LLMs) aplican principios de ML dentro de arquitecturas más amplias de IA.

**Ejercicio Práctico:**
- [ ] Experimentar con [OpenAI Playground](https://platform.openai.com/playground) para observar el comportamiento del modelo
- [ ] Revisar: [Fundamentos de Redes Neuronales](https://www.youtube.com/watch?v=aircAruvnKk) para obtener la base técnica

---

#### **Procesamiento de Texto y Tokenización**

**Resumen Técnico:**
El procesamiento de lenguaje natural requiere convertir texto humano en representaciones numéricas que los sistemas computacionales puedan procesar de manera efectiva.

**Proceso de Tokenización:**
'''''
Texto de entrada: "Hola, ingeniero DevOps!"
Tokenización: ["Hola", ",", "ingeniero", "Dev", "Ops", "!"]
Codificación Numérica: [7595, 11, 11618, 6768, 40004, 0]
'''''


**Conceptos Clave:**
- **Tokens**: Unidades discretas de texto (palabras, subpalabras o caracteres) usadas como entrada del modelo
- **Embeddings**: Representaciones vectoriales de alta dimensión que capturan el significado semántico
- **Espacio Vectorial**: Espacio matemático donde conceptos similares se agrupan

**Detalles de Implementación:**
Los LLM modernos usan algoritmos de tokenización por subpalabras (como Byte-Pair Encoding) para manejar vocabulario de manera eficiente sin perder coherencia semántica.

**Ejercicio Práctico:**
- [ ] Analizar la tokenización de texto usando [OpenAI Tokenizer](https://platform.openai.com/tokenizer)
- [ ] Comparar patrones de tokenización en diferentes formatos de entrada

---

#### **Categorías de Modelos de IA y Aplicaciones**

**Modelos de Clasificación**
Propósito: Categorizar entradas en clases predefinidas
Entrada: Muestras de datos (texto, imágenes, métricas)
Salida: Probabilidades de clase con puntajes de confianza
Aplicación en DevOps: Detección de anomalías, clasificación de alertas


**Modelos Generativos**
Propósito: Crear contenido nuevo basado en patrones aprendidos
Entrada: Prompts o contenido parcial
Salida: Texto, código o configuraciones generadas
Aplicación en DevOps: Generación de documentación, autocompletado de código


**Sistemas de Recomendación**


**Implementación Técnica:**
Cada tipo de modelo emplea diferentes arquitecturas y metodologías de entrenamiento optimizadas para casos de uso específicos y requisitos de rendimiento.

**Ejercicio Práctico:**
- [ ] Evaluar distintos tipos de modelos de IA usando plataformas disponibles:
  - Clasificación: [Google Teachable Machine](https://teachablemachine.withgoogle.com/)
  - Generación: OpenAI GPT o Anthropic Claude
  - Multimodal: DALL-E o Midjourney
