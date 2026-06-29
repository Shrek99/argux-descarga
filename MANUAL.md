# ARGUX — Manual de instalación

**ARGUX — Inteligencia de Rutas.** Triangula los GPS de tu flota contra tu
catálogo de clientes para detectar visitas, calidad y frecuencia de ruta.
Corre **100% en tu laptop**; tus datos no salen a ninguna nube.

---

## 1. Descargar

👉 **Página de descarga:** https://shrek99.github.io/argux-descarga/

O directo el instalador:
**[Descargar ARGUX-Setup.exe](https://github.com/Shrek99/argux-descarga/releases/latest/download/ARGUX-Setup.exe)**

## 2. Requisitos

- **Windows 10 u 11**, de 64 bits.
- **Docker Desktop** (gratis). ARGUX lo necesita para funcionar.
  El instalador intenta ponerlo solo, pero **es más seguro instalarlo tú
  primero**: https://www.docker.com/products/docker-desktop/ → instala →
  reinicia si te lo pide → déjalo abierto (ícono de ballena en la barra de tareas).

## 3. Instalar

1. **Docker Desktop** (una sola vez): instálalo y déjalo corriendo.
2. **ARGUX**: doble clic a `ARGUX-Setup.exe`. Acepta los permisos.
   Crea un ícono **ARGUX** en tu escritorio.
3. **Abre ARGUX**: doble clic al ícono. La primera vez descarga la última
   versión de la app y la levanta (tarda unos minutos); luego se abre solo
   en tu navegador.

## 4. La primera vez (asistente)

La app **arranca en blanco**. Un asistente te pide:

1. **Credenciales TCVSAT** — tu usuario y contraseña. El botón
   **"Probar conexión"** confirma que funcionan y te dice cuántas unidades
   ve tu cuenta.
2. **Tu primera región** — nombre, prefijo de ruta y ciudad (define tu territorio).
3. *(Opcional)* **Descubrir GPS** desde TCVSAT, y **Telegram** (pega un token
   en *Argux Admin → Credenciales*) si quieres alertas.

## 5. Actualizaciones

Automáticas. Cada vez que abres ARGUX busca y descarga la última versión.
**No reinstalas nada y tus datos se conservan.**

## 6. Problemas comunes

| Síntoma | Solución |
|---|---|
| No abre / se queda cargando | Asegúrate de que **Docker Desktop** esté corriendo ("Engine running") y vuelve a abrir ARGUX. |
| El instalador no pudo poner Docker | Instálalo a mano desde [docker.com](https://www.docker.com/products/docker-desktop/), reinicia y reintenta. |
| ¿Mis datos están en la nube? | No. Todo corre en tu laptop; solo se conecta a TCVSAT para bajar los GPS. |

---

*Soporte: WDBB.*
