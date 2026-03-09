# Modulo-3-Reconocimiento_LASEC

## Descripción

Este repositorio contiene la documentación y evidencias del **Módulo 3: Reconocimiento Pasivo y Activo**.  
El objetivo de esta actividad fue analizar cómo la información pública puede ser descubierta mediante técnicas de **OSINT, Google Dorks y herramientas de análisis de infraestructura**.

---

## Estructura del proyecto

El repositorio se divide en cuatro secciones correspondientes a las actividades del módulo:

### Sección 1 – Reconocimiento Pasivo con Google Dorks
Se realizaron **8 búsquedas utilizando operadores avanzados de Google** como:

- `site:`
- `filetype:`
- `inurl:`
- `intitle:`
- `"frase exacta"`
- `OR`
- `-` (exclusión)

Cada búsqueda incluye:
- Dork utilizado
- Análisis de resultados
- Evaluación de riesgo
- Capturas de evidencia

---

### Sección 2 – Investigación en GHDB
Se investigaron **3 Google Dorks** obtenidos desde **Exploit Database (Google Hacking Database)** para analizar:

- Qué tipo de información buscan
- Qué tipo de exposición detectan
- La categoría en la que se clasifican

---

### Sección 3 – Maltego (Mapa de Infraestructura)

Se utilizó **Maltego** para generar un grafo de reconocimiento básico siguiendo el flujo:

```text
Dominio → DNS → IP → Location
```
			
Esto permite visualizar cómo se relacionan los componentes de infraestructura de un dominio.

---

### Sección 4 – Reflexión

Se desarrolló un análisis conceptual sobre:

- Diferencia entre **reconocimiento pasivo y activo**
- Riesgos legales del reconocimiento sin autorización
- Aprendizajes sobre exposición de información en internet

---

## Objetivo del módulo

Comprender cómo los atacantes pueden identificar información expuesta públicamente y cómo esta puede ser utilizada durante la fase de **reconocimiento en una auditoría de seguridad o pentest**.

---

## Uso Ético

Este proyecto fue realizado con **fines exclusivamente académicos**.

Las técnicas utilizadas en este repositorio, como **Google Dorks, análisis OSINT y reconocimiento de infraestructura**, deben aplicarse únicamente en entornos autorizados, por ejemplo:

- `localhost`
- laboratorios de práctica
- máquinas virtuales propias
- sistemas o dominios con **autorización explícita**

El reconocimiento o análisis de sistemas **sin autorización del propietario** puede ser considerado actividad ilegal dependiendo de la legislación de cada país.

El objetivo de este trabajo es **comprender cómo se expone la información en internet y fomentar prácticas responsables de ciberseguridad**.

## Autor
Adolfo Mandujano Lara
Ingeniería en Robótica y Mecatrónica
Universidad Autónoma de Zacatecas
LASEC Techonolgy System| Intern - ComputerVision
