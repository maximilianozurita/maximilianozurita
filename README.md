# Maxi Zurita

**Backend Developer | Data Engineer | AI & Agents**

[![Portfolio](https://img.shields.io/badge/Portfolio-maximilianozurita.github.io-0a0a0a?style=flat&logo=github)](https://maximilianozurita.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-maximilianozurita-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/maximilianozurita/)
[![Email](https://img.shields.io/badge/Email-maxi.zurita.seb%40gmail.com-D14836?style=flat&logo=gmail)](mailto:maxi.zurita.seb@gmail.com)

---

## 🚀 Sobre mí

Backend developer con +4 años en sistemas de producción de alta escala (adtech).  
Especializado en **pipelines de datos, integración de LLMs y agentes de IA** sobre problemas reales.

- Datos reales: volumen, complejidad, fuentes heterogéneas
- LLMs en producción: multi-provider, fallback, prompting estructurado
- Agentes autónomos para automatización y generación de artefactos
- Arquitectura backend orientada a performance y observabilidad

---

## 🧠 Proyectos destacados

### 🔹 [smart-cv-builder](https://github.com/maximilianozurita/smart-cv-builder)
Agente de generación de CVs que adapta perfil, skills y experiencia a una oferta laboral concreta.
Pipeline LLM con parsing en 3 capas, fallback multi-provider y scoring ATS.
Salida: PDF + Word via Jinja2 + WeasyPrint + python-docx.

**Stack:** FastAPI · Pydantic v2 · Jinja2 · WeasyPrint · Anthropic · OpenAI · Gemini · Groq · xAI

---

### 🔹 [ai-portfolio-analyzer](https://github.com/maximilianozurita/ai-portfolio-analyzer)
Portfolio de inversión con precios en tiempo real y análisis AI estructurado en 7 secciones.
Arquitectura Flask de 3 capas (routes → services → models), frontend reactivo con caché de precios.

**Stack:** Flask · MySQL · SvelteKit · ECharts · Docker · OpenAI · Gemini · OpenRouter · yfinance

---

### 🔹 [arg-financial-local](https://github.com/maximilianozurita/arg-financial-local)
Pipeline ETL de indicadores económicos argentinos. Integra 5 fuentes oficiales (BCRA, INDEC,
Ministerio de Economía, Bluelytics, ArgentinaDatos), deduplica y exporta a CSV/Parquet via cron.

**Stack:** Python · httpx · pandas · pyarrow · SQLite

---

### 🔹 [arg-financial-data](https://github.com/maximilianozurita/arg-financial-data)
Dataset público con +23 series históricas de Argentina (1994–presente), actualización diaria automática.
Accesible via Python, DuckDB o URLs raw de GitHub — sin autenticación.

**Stack:** CSV · Parquet · DuckDB · pandas

---

### 🔹 [makeDoc](https://github.com/maximilianozurita/makeDoc)
Plugin para Claude Code que genera documentación técnica completa analizando el código fuente.
Modos: creación desde cero, actualización incremental, ejecución como subagente.

**Stack:** Claude Code · Anthropic SDK · Markdown

---

## 🛠️ Stack técnico

**Backend**
Python · FastAPI · Flask · JavaScript · TypeScript · Bash

**Frontend**
SvelteKit · Tailwind CSS

**Data & Storage**
pandas · pyarrow · DuckDB · MySQL · SQLite

**AI / Agentes**
Anthropic · OpenAI · Gemini · Groq · LLM pipelines · multi-provider fallback

**Infra**
Docker · Linux · cron · Git

---

## 🎯 Intereses actuales
- Agentes autónomos aplicados a datos y automatización
- Sistemas de analytics escalables con datos económicos reales
- LLMs en backend productivo: latencia, costo, confiabilidad
- Predicción económica (Argentina) con series temporales reales

---