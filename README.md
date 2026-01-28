# ISW123-ReporteroDigital-2023-3786

Aplicación de consola desarrollada en **C#** que simula el ensamblaje de un artículo para un **periódico digital dominicano**, combinando múltiples fuentes de información de forma **asíncrona y en paralelo**, con manejo de eventos y excepciones personalizadas.

Este proyecto fue creado como parte de una evaluación académica para demostrar el uso correcto de programación asíncrona, paralelismo, eventos y manejo de errores.

---

## 📰 Escenario
Cuando se publica una noticia, el sistema obtiene simultáneamente:
- 📝 Texto de la noticia
- 🖼️ Imágenes
- 📊 Análisis periodístico  

Cada parte se procesa de forma independiente y, cuando está lista, se notifica mediante un evento. Al finalizar todas las tareas, el artículo se ensambla y se publica.

---

## ⚙️ Tecnologías y Conceptos Aplicados
- Lenguaje: **C#**
- Programación asíncrona (`async`, `await`)
- Paralelismo con `Task.WhenAll`
- Manejo de eventos (`event Action<string>`)
- Excepciones personalizadas
- Manejo de errores con `try / catch`

---

## 🛡️ Manejo de Errores
El sistema incluye una excepción personalizada llamada:

