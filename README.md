# 🚀 Neon Space Defender & Atenea Vault (Stealth App)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **Una aplicación de camuflaje.** A simple vista, un adictivo juego arcade retro de naves espaciales. En su interior, una bóveda de seguridad oculta diseñada para situaciones de emergencia y recolección de pruebas de forma discreta.

---

## 📖 Descripción

Este proyecto es una **Prueba de Concepto (PoC)** desarrollada como una "Single File Application" (todo en un solo archivo HTML). Combina técnicas de gamificación con privacidad digital.

1.  **Capa Pública (Frontend):** Un juego funcional tipo *Bullet Hell* llamado **Neon Storm**.
2.  **Capa Privada (Backend Simulado):** Una app llamada **Atenea Vault**, accesible solo mediante un código secreto, diseñada para víctimas en situaciones de riesgo que necesitan herramientas ocultas.

---

## ✨ Características

### 🎮 El Juego (Neon Storm)
*   **Motor Gráfico:** Renderizado en HTML5 Canvas con partículas y efectos de neón.
*   **Gameplay:** Sistema de oleadas, puntuación, vidas y *Power-ups*.
*   **Sistema de Skins:** Tienda integrada (Hangar) para desbloquear naves según la puntuación.
*   **Responsive:** Adaptado para móviles y escritorio (con marco de dispositivo simulado en PC).

### 🛡️ La Bóveda (Atenea Vault)
*   **Modo SOS:** Botón de pánico simulado para envío de ubicación silenciosa.
*   **Recolección de Evidencias:**
    *   📸 Simulador de cámara (interfaz realista).
    *   🎙️ Grabadora de audio oculta con temporizador.
    *   📝 Notas de texto encriptadas (simuladas en LocalStorage).
*   **Llamadas Falsas:** Simulador de llamadas al 112 y 016 para disimular o pedir ayuda visualmente.
*   **Botón de Pánico:** Cierre inmediato de la bóveda y retorno al juego.
*   **Persistencia:** Los datos se guardan en el navegador del usuario.

---

## 🔓 Cómo Acceder a la Bóveda (Easter Egg)

Para pasar del modo juego al modo seguro, sigue estos pasos:

1.  Juega o inicia **Neon Storm**.
2.  Pulsa el botón de **PAUSA** (esquina superior derecha).
3.  En el campo "PROMO CODE", introduce el PIN maestro:
    ```text
    1111
    ```
4.  Pulsa **OK**.

> **Nota:** Puedes cambiar este PIN dentro de la configuración de Atenea Vault una vez dentro.

---

## 🕹️ Cheats y Códigos de Juego

Además del código de acceso, el juego incluye trucos para desarrolladores que se introducen en el mismo campo de "PROMO CODE":

| Código | Efecto |
| :--- | :--- |
| `VIDA` | Añade +1 vida extra al jugador. |
| `ESCUDO` | Activa un escudo de invulnerabilidad temporal. |
| `NEON` | Añade +5000 puntos (para probar el desbloqueo de skins). |

---

## 🛠️ Instalación y Uso

Este proyecto no requiere compilación ni dependencias de Node.js, ya que usa TailwindCSS vía CDN.

### Opción 1: Ejecución Local
1.  Clona este repositorio:
    ```bash
    git clone https://github.com/tu-usuario/neon-atenea-vault.git
    ```
2.  Navega a la carpeta y abre el archivo `index.html` en tu navegador favorito (Chrome, Firefox, Safari).

### Opción 2: Despliegue
Simplemente sube el archivo `index.html` a cualquier host estático como **GitHub Pages**, **Vercel** o **Netlify**.

---

## 📂 Estructura del Código

Todo el código reside en un único fichero para facilitar la portabilidad:

*   **HTML:** Estructura del contenedor y las dos capas (Juego y App).
*   **Tailwind CSS:** Configuración personalizada en el `<script>` de cabecera para los colores neón y animaciones.
*   **JS (Game Engine):** Lógica del Canvas, bucle de juego, colisiones y partículas.
*   **JS (App Logic):** Gestión del DOM para la bóveda, almacenamiento en `localStorage` y simulación de funciones del teléfono.

---

## ⚠️ Aviso Legal (Disclaimer)

Esta aplicación es una **DEMO TÉCNICA**.

*   Las llamadas de emergencia (112, 016) son **simulaciones visuales** y **NO** conectan con servicios reales.
*   La función SOS es una simulación de interfaz y no envía coordenadas reales a ningún servidor en esta versión.
*   Los datos se guardan en el `localStorage` del navegador, por lo que borrar la caché del navegador eliminará las "evidencias" guardadas.

*Este proyecto fue creado con fines educativos para demostrar el concepto de esteganografía en software.*

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar la seguridad de la bóveda o añadir niveles al juego:

1.  Haz un Fork del proyecto.
2.  Crea una rama (`git checkout -b feature/AmazingFeature`).
3.  Haz Commit de tus cambios (`git commit -m 'Add some AmazingFeature'`).
4.  Haz Push a la rama (`git push origin feature/AmazingFeature`).
5.  Abre un Pull Request.

---

Hecho con ❤️ y mucho código neón.
