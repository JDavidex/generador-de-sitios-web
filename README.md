# Generador de sitios web | L-1 DIGITAL STUDIO

Herramienta interactiva diseñada para recopilar información de negocios y automatizar la personalización de plantillas de Elementor (WordPress).

◆ **Acceso a la plataforma:** [https://gen.l1ds.co](https://gen.l1ds.co)

---

## ◇ ¿Qué hace el generador?

La aplicación guía al usuario a través de un flujo estructurado de 7 pasos (wizard) para definir la identidad de su negocio, seleccionar un estilo visual y configurar su información de contacto. 

Con estos datos, el sistema genera un perfil estructurado que se utiliza para inyectar dinámicamente contenidos, imágenes, colores y tipografías directamente en WordPress usando Elementor.

---

## ◇ **Captura de pantalla**
![](https://github.com/JDavidex/generador-de-sitios-web/blob/main/(1).png)

---

## ◇ Flujo de experiencia de usuario (wizard)

El proceso de configuración consta de los siguientes módulos interactivos:

◆ **Selección de rubro:** Identificación del sector del negocio entre 20 categorías disponibles (salón de belleza, restaurante, consultorio, etc.).  
◆ **Nombre comercial:** Registro del nombre de la marca o negocio.  
◆ **Tono de comunicación:** Selección del estilo de redacción de los textos (Personal, Profesional, Divertido o Elegante).  
◆ **Identidad visual:** Elección de una paleta cromática y tipográfica preconfigurada.  
◆ **Diseño de plantilla:** Selección del diseño base para el sitio web.  
◆ **Datos de contacto:** Formulario para horarios de atención, teléfonos, dirección física y correo electrónico.  
◆ **Resumen y confirmación:** Vista previa en tiempo real de la plantilla seleccionada con la combinación de colores elegida y un resumen detallado de la configuración antes de procesar el sitio.

---

## ◇ Características de diseño y arquitectura

◆ **Diseño premium e interactivo:** Implementa micro-animaciones fluidas, efectos de cursor magnético personalizados y elementos interactivos para enriquecer la experiencia de usuario.  
◆ **Sistema de variación de copys ("Shuffle Bag"):** Para evitar textos repetitivos en sitios del mismo sector, el sistema selecciona variaciones de redacción de forma inteligente y determinista en el cliente, alternando descripciones y títulos según el tono elegido.  
◆ **Previsualización dinámica:** En el paso final, el usuario puede interactuar con una previsualización en miniatura que simula cómo se verá su sitio web aplicando la paleta de colores y la plantilla elegida.

---

## ◇ Tecnologías utilizadas

◆ **Frontend core:** React 19 y Vite 8.  
◆ **Estilos y maquetación:** CSS Modules y variables CSS personalizadas para mantener una arquitectura de estilos modular y un tema visual dinámico.  
◆ **Animaciones y micro-interacciones:** Javascript Vanilla en el cliente (física de burbujas de fondo, cursor inteligente y comportamientos magnéticos en los botones principales).  
◆ **Despliegue:** Compilado como un sitio web estático optimizado, alojado directamente en servidor y desplegado en plataformas de distribución estática (Vercel, Netlify, GitHub Pages).

---

## ◇ Créditos

Desarrollado y mantenido por [L-1 DIGITAL STUDIO](https://l1ds.co). Todos los derechos reservados.
