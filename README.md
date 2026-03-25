# 🤖 Joomla IT Support Chatbot (Keyword-Based)

### "Automatizando lo repetitivo para escalar lo importante" 🚀

Este proyecto es un asistente virtual ligero diseñado específicamente para integrarse en **Joomla**. Su objetivo principal es actuar como primera línea de defensa para el departamento de IT, filtrando y respondiendo dudas frecuentes de manera instantánea para reducir la carga de tickets manuales.

---

## 🛠️ Arquitectura del Proyecto
El bot utiliza una arquitectura desacoplada para garantizar velocidad y facilidad de mantenimiento:
* **Frontend (Joomla Module):** El contenedor visual que interactúa con el usuario.
* **Core Logic (External JS):** Un motor de procesamiento de palabras clave (keywords) alojado en **Ilimit**, lo que permite actualizaciones globales sin tocar el CMS.
* **Storage:** Sistema de log de comunicaciones para auditoría y mejora continua de respuestas.

---

## ✨ Especificaciones Técnicas
* **Motor de Respuesta:** Lógica basada en mapeo de *keywords* y patrones de coincidencia manual.
* **Stack:** ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
* **Integración:** Módulo nativo de Joomla con llamada a script externo.
* **Persistencia:** Almacenamiento de logs de conversación para análisis de métricas de soporte.

---

## 🚀 Cómo funciona (The Logic)
A diferencia de las IAs "caja negra", este bot es **predecible y seguro**:
1. El usuario introduce una consulta en el módulo de Joomla.
2. El motor de JS procesa la cadena buscando términos clave predefinidos.
3. Se devuelve una respuesta estandarizada de alta precisión.
4. **Tracking:** Cada interacción se registra para identificar nuevas dudas frecuentes que deban ser añadidas al diccionario.

---

## 🛡️ Retos Técnicos Superados
> **"El mayor desafío fue el entendimiento de las keywords"**
>
> Crear un sistema que entienda las variaciones del lenguaje humano (sin usar una IA pesada) requirió una estructura de datos optimizada en JavaScript para mapear múltiples entradas a una única solución correcta, garantizando que el usuario siempre reciba ayuda útil.

---

## 🔧 Instalación y Despliegue
1. Instala el módulo en tu panel de administración de **Joomla**.
2. Asegúrate de que el archivo `chat-logic.js` esté accesible en tu servidor de **Ilimit**.
3. Configura el endpoint del script en los parámetros del módulo.
4. Define tu diccionario de keywords en el archivo de lógica central.

---

## 🤝 Contribuciones
Este es un proyecto de "estudiante eterno" buscando mejorar procesos reales. Si tienes ideas para optimizar el motor de búsqueda o mejorar la UI, ¡abre un PR!

---
<p align="center">
  Desarrollado por <b>Marc Perarnau</b> <br/>
  <i>Optimizando servicios de IT mediante código inteligente.</i>
</p>
