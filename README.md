# 🛡️ Tuwr-Sentinel (Demo)

**Tuwr-Sentinel** es un agente de Inteligencia Artificial diseñado para asistir y responder consultas especializadas sobre ciberseguridad, enfocándose específicamente en los marcos de trabajo de **OWASP** y **MITRE**.

Esta versión es una demostración técnica interactiva que opera bajo una arquitectura de **RAG Local (Retrieval-Augmented Generation)**, ejecutándose por completo de forma local.

---

## 🚀 Características Principales

- **RAG 100% Local en el Navegador**: La base vectorial, la búsqueda semántica y la inferencia del modelo de lenguaje (LLM) se realizan localmente en el cliente sin enviar datos a servidores externos.
- **Especializado en OWASP & MITRE**: Consulta de manera ágil y precisa técnicas de ataque, vulnerabilidades comunes (CWE) y sus respectivas mitigaciones.
- **Multilingüe**: Soporte completo para consultas y bases de conocimiento tanto en **español** como en **inglés**.
- **Ejecución de Alto Rendimiento**: Aprovecha tecnologías modernas como **WebGPU** y **WASM (WebAssembly)** a través del hardware local para ofrecer respuestas fluidas en tiempo real.
- **Enfoque de Seguridad**: Implementa defensas a nivel de cliente contra inyecciones de prompts y sanitización estricta de salidas para evitar ejecuciones de código malicioso (XSS).

---

## 🛠️ Tecnologías Utilizadas

- **Motor de Inferencia**: ONNX Runtime Web.
- **Modelo Base**: `Qwen2.5-0.5B-Instruct` optimizado para la ejecución local.
- **Búsqueda Vectorial**: Motor de búsqueda semántica local de alta velocidad.
- **Interfaz**: Aplicación Web Reactiva (HTML5, Vanilla CSS, JS moderno).

---

## 🔒 Privacidad y Seguridad

Al ser un agente local, **tus preguntas y datos nunca salen de tu dispositivo**. Toda la información de OWASP y MITRE se encuentra de manera consolidada de forma local y el procesamiento se efectúa enteramente en tu CPU/GPU.

---

## 💻 Uso de la Demo

1. Abre la URL publicada de GitHub Pages.
2. Espera a que el modelo base y la base de conocimiento local se carguen en la memoria del navegador (este proceso ocurre una sola vez al inicio).
3. Selecciona tu idioma de preferencia (Español / Inglés).
4. Empieza a realizar preguntas sobre vulnerabilidades OWASP, técnicas de MITRE o estrategias de mitigación.

---
*Desarrollado de manera segura y optimizada por **Strong Tower Apps™**.*
