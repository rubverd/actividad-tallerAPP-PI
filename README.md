# 🛡️ Taller de Ciberseguridad: Simulación de Fuerza Bruta (Proyecto APP-PI)

> Herramienta educativa para concienciación sobre contraseñas seguras y auditoría de código generado por IA.

Este repositorio contiene una actividad práctica diseñada para talleres de ciberseguridad en centros de Educación Secundaria y Formación Profesional (FP), dentro del marco del **Proyecto Estratégico de Ciberseguridad APP-PI**.

## 🎯 Objetivo de la Actividad

El objetivo principal es realizar una demostración en vivo (Live Demo) donde los estudiantes puedan visualizar:

1.  **La debilidad de las contraseñas comunes:** Cómo una contraseña sencilla puede ser vulnerada en segundos mediante ataques de diccionario.
2.  **La mecánica de un ciberataque:** Simulación visual de un ataque de fuerza bruta contra un panel de login.
3.  **El riesgo del "Copy-Paste" de la IA:** Concienciar sobre el peligro de implementar código generado por Inteligencia Artificial (ChatGPT, Copilot, Gemini) sin realizar una auditoría de seguridad posterior.

## 📖 El Escenario: "La Trampa de la IA"

Para la actividad, simulamos un escenario muy común hoy en día:

* Un desarrollador junior ha pedido a una IA: *"Générame un código HTML y CSS para un login de una app de torneos de tenis".*
* La IA ha entregado un código **funcional y bonito**, pero **inseguro**:
    * ❌ Permite intentos de login indefinidos (sin bloqueo de cuenta).
    * ❌ No tiene *rate limiting* (control de velocidad de peticiones).
    * ❌ Usa credenciales por defecto (`admin` / `12345`).

La actividad demuestra cómo un atacante aprovecharía estos fallos de diseño para acceder al sistema.

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3:** Interfaz del portal de "Torneos de Tenis".
* **JavaScript (Vanilla):** Lógica del cliente y script de simulación del ataque ("Hacker Script").
* *Nota:* Todo el ataque se ejecuta en el lado del cliente (navegador) para facilitar la demostración sin necesidad de servidores o configuraciones complejas en el aula.

## 🚀 Cómo usar este repositorio

1.  Clonar el repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/taller-fuerza-bruta.git](https://github.com/tu-usuario/taller-fuerza-bruta.git)
    ```
2.  Abrir el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge).
3.  Proyectar la pantalla en el aula.
4.  Explicar la interfaz y lanzar el script de ataque desde el panel de control.

## ⚠️ Disclaimer / Aviso Legal

Esta herramienta ha sido creada **exclusivamente con fines educativos y académicos**. 

El propósito es enseñar a los estudiantes la importancia de fortificar sus sistemas y usar contraseñas robustas.