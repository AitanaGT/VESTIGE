# VESTIGE // Archivo Vivo de Piel y Memoria

<div align="center">

[![ESD Madrid](https://img.shields.io/badge/ESD-Madrid-141413?style=flat-square)](https://www.esdmadrid.es)
[![Project](https://img.shields.io/badge/Proyectos_Experimentales-4º_Grado-9E2A2B?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Funcional_/_Vertical_Slice-8C8982?style=flat-square)]()

*«La esperanza de morir antes que la persona amada para no soportar su ausencia.»*  
Un cuerpo colectivo digital donde las marcas en la piel permanecen nítidas solo si otros las recuerdan.

</div>

---

## Sobre el Proyecto
**VESTIGE** es una plataforma digital experimental y transmedia que explora el tatuaje memorial no como un elemento estético, sino como un archivo somático y un acto de resistencia frente a la amnesia digital contemporánea. 

Frente a la sobreacumulación fría de fotografías en la nube, el proyecto traslada la física de la piel y el duelo a una experiencia web interactiva basada en el concepto de **Ya'aburnee**.

---

## Manifiesto Anti-UI (Mecánicas de Interacción)
Para replicar la fragilidad de la memoria humana, **VESTIGE** destruye las convenciones de usabilidad web estándar mediante cinco leyes físicas:

1. **La prisa desenfoca la piel:** El consumo rápido es incompatible con el recuerdo. Mover el cursor con ansiedad deforma e introduce desenfoque óptico en la escena 3D.
2. **La fricción del recuerdo (Cursor-Aguja):** Las historias no se abren con un clic instantáneo. Exige **mantener pulsado** bajo el zumbido eléctrico de una máquina de tatuar para simular la punción en la dermis.
3. **Erosión por olvido:** Las marcas que llevan más de 300 días sin ser visitadas se difuminan y pierden opacidad. Cuando un usuario entra a leerlas, la tinta **recupera al instante su negro profundo**, salvándolas del olvido.
4. **Inscripción con vectorización automática:** Permite subir la fotografía real de un tatuaje; un algoritmo adaptativo elimina el fondo por completo y convierte el archivo en tinta pura sobre la anatomía 3D, activando vibración háptica y enrojecimiento de la dermis durante el tatuado.
5. **Red social de resonancia invisible:** Cero perfiles, cero *likes*. Finos hilos de color rojo carmesí conectan en el espacio tridimensional aquellas cicatrices que comparten zona anatómica, permitiendo dejar susurros y ecos anónimos entre portadores.

---

## Stack Tecnológico
* **Core 3D:** Three.js (Escultura anatómica de porcelana mate, sub-superficie y *raycasting* sobre coordenadas locales).
* **Audio Generativo:** Web Audio API (Síntesis en tiempo real de latido cardíaco, zumbido de bobina de tatuaje y acordes armónicos).
* **Gráficos 2D / Canvas:** Algoritmo de estela líquida de tinta y vectorización de imágenes subidas por el usuario.
* **Transmedia:** Generación dinámica de fichas A5 en formato *Stencil* (invertidas en espejo con marcador AR) listas para descargar y transferir a la piel real.

---

## Estructura del Repositorio
```text
📦 VESTIGE
 ┣ 📜 vestige.html       # Archivo monolítico principal (HTML5, CSS3, Three.js & JS)
 ┣ 📁 assets/            # Recursos gráficos, texturas y tipografías
 ┗ 📜 README.md          # Documentación del proyecto
