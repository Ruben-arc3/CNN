# CNN + GPT-2 para Clasificación y Descripción de Señales de Tránsito

Autor: Ruben Mora Martinez

Este proyecto implementa un sistema de visión por computador basado en una **Red Neuronal Convolucional (CNN)** para la **clasificación de señales de tránsito**, integrado con un modelo **GPT-2 en español** para la **generación automática de descripciones técnicas** de la señal detectada.

El sistema combina aprendizaje profundo para visión y procesamiento de lenguaje natural, permitiendo no solo identificar la señal, sino también generar una explicación técnica de su función.

---

## Objetivo del proyecto

- Clasificar señales de tránsito a partir de imágenes usando CNN.
- Procesar anotaciones en formato **Pascal VOC (XML)**.
- Aplicar **aumento de datos** para mejorar el entrenamiento.
- Evaluar el modelo mediante métricas de precisión.
- Generar automáticamente una **descripción técnica en español** utilizando **GPT-2**.

---

## Clases reconocidas

- trafficlight  
- stop  
- speedlimit  
- crosswalk 
