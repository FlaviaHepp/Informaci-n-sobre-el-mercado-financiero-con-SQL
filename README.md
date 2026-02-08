# 📊Información sobre el mercado financiero con SQL

## 📌Descripción general

Este proyecto reúne una colección de insights analíticos sobre mercados financieros, desarrollados íntegramente en SQL, orientados a detección de tendencias, volatilidad, eventos relevantes y comportamiento del precio.

El objetivo es transformar indicadores técnicos y datos de mercado en clasificaciones accionables, útiles para screening, research y apoyo a decisiones de trading o inversión.

## 🎯Objetivos del proyecto

- Analizar el estado técnico actual de activos financieros
- Identificar tendencias fuertes vs. mercados laterales
- Clasificar activos según volatilidad y comportamiento post-evento
- Proveer queries reutilizables para análisis cuantitativo
- Demostrar dominio de SQL aplicado a finanzas

## 🧠Enfoque Analítico

El proyecto se basa en:
- Indicadores técnicos clásicos (ADX, volatilidad, etc.)
- Clasificaciones interpretables (no solo métricas crudas)
- Análisis en estado actual y reacción a eventos
- Queries pensadas para integrarse en dashboards o pipelines

Cada insight responde a una pregunta concreta del mercado, por ejemplo:
- ¿Qué activos tienen una tendencia confiable?
- ¿Cuáles están en rango lateral?
- ¿Cómo reacciona la volatilidad después de un evento relevante?

## 🗂️Contenido del Repositorio

📁 Insights incluidos

- Clasificación de Tickers por Robustez de la Tendencia (ADX)
- Identifica activos con tendencias fuertes, emergentes o en rango lateral.
- Clasificación de Eventos por Volatilidad Post-Evento
- Analiza el impacto de eventos sobre la volatilidad posterior del activo.

Cada insight está implementado como un query SQL independiente y documentado conceptualmente.

## 🧮Tecnologías Utilizadas

- SQL

Base de datos relacional con:
- precios históricos
- indicadores técnicos
- metadatos de activos
- Enfoque agnóstico a motor (adaptable a PostgreSQL / MySQL / BigQuery)

## 🗃️Modelo de Datos (simplificado)

- tickers
- ticker_id
- nombre_empresa
- sector
- indicadores_tecnicos
- ticker_id
- fecha
- indicadores (ADX, volatilidad, etc.)
- eventos (cuando aplica)
- ticker_id
- fecha_evento
- tipo_evento

## 📈Casos de Uso

- Screening de activos para trend following
- Identificación de mercados aptos para trading de rango
- Evaluación de impacto de eventos
- Análisis exploratorio para research financiero
- Base para dashboards o modelos cuantitativos

## ⚠️Consideraciones

- Los indicadores técnicos no predicen dirección, solo comportamiento
- Los umbrales utilizados son configurables

Los insights deben complementarse con:
- análisis fundamental
- gestión de riesgo
- contexto de mercado

## 🚀Posibles Extensiones

- Backtesting de estrategias basadas en las clasificaciones
- Agregación temporal (semanal / mensual)
- Integración con Python o herramientas de BI
- Alertas automáticas por cambios de estado

## 👤Autor

Flavia Hepp
Proyecto de análisis financiero y SQL aplicado a mercados
