# 🔐 ProtecClave — Auditor y Generador de Seguridad Criptográfica

**Universidad Nacional Federico Villarreal (UNFV)**  
**Facultad de Ingeniería Industrial y de Sistemas (FIIS)**  
**Escuela Profesional de Ingeniería de Sistemas**  

* **Curso:** Tecnología de la Información y Comunicación (2026-2)
* **Docente:** Mg. Petrlik Azabache Ivan Carlo
* **Integrante:** Reyes Quispe Luis Eduardo

---

## 📋 Descripción del Proyecto

**ProtecClave** es una aplicación educativa diseñada para concientizar sobre la ciberseguridad y prevenir riesgos informáticos derivados del uso de contraseñas débiles o predecibles. El sistema audita credenciales en tiempo real de forma **100 % local en memoria** (sin almacenar ni transmitir datos a servidores externos) y ofrece retroalimentación visual inmediata mediante un **Núcleo Criptográfico 3D interactivo**.

---

## 🚀 Funcionalidades Principales

1. **Auditoría en Tiempo Real (6 Criterios):**
   * Verificación de longitud mínima (12 caracteres).
   * Detección de letras mayúsculas (`A-Z`) y minúsculas (`a-z`).
   * Validación de números (`0-9`) y caracteres especiales (`!@#$%&*?-_`).
   * Filtro inteligente contra contraseñas comunes (`admin123`, `qwerty`, `password`) y secuencias repetitivas.
2. **Métricas Técnicas Avanzadas:**
   * Cálculo matemático de **entropía en bits** ($L \times \log_2(N)$).
   * Estimación de **tiempo de descifrado por fuerza bruta** ($10^{10}$ intentos/segundo).
3. **Núcleo Criptográfico 3D:**
   * Visualización dinámica que cambia de color y alineación geométrica según el nivel de seguridad detectado (Rojo, Ámbar, Azul y Verde).
4. **Generador Criptográfico Seguro:**
   * Creación de contraseñas aleatorias de 12 a 24 caracteres empleando fuentes de entropía criptográfica (`crypto.getRandomValues()` / `secrets`).

---

## 🛠️ Tecnologías Utilizadas

* **Frontend & Lógica:** React (`ProtecClave.jsx`), JavaScript (ES6+), Tailwind CSS.
* **Gráficos 3D:** Three.js.
* **Seguridad:** Web Crypto API (procesamiento local sin persistencia).
* **Control de Versiones:** Git & GitHub.

---

## 🔒 Aviso de Privacidad

Esta herramienta tiene fines estrictamente académicos y educativos. Todo análisis se ejecuta de manera volátil en la memoria del navegador; **no se recomienda ingresar contraseñas personales reales** durante demostraciones públicas.
