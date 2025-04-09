
# 🔍 Verificador de Listas M3U (Frontend)

Este proyecto es una herramienta web que permite verificar listas **M3U/M3U8** directamente desde el navegador. Analiza cada enlace y muestra si está **activo** o **inactivo**, y luego te permite copiar o descargar una nueva lista con solo los enlaces válidos.

---

## 🌐 Tecnologías usadas

- HTML5
- CSS3
- JavaScript (vanilla)

---

## 🚀 Características

- 📂 Carga de archivos `.m3u` o `.m3u8`
- 🔎 Verificación de estado de cada enlace mediante peticiones HTTP
- ✅ Interfaz para visualizar resultados en tiempo real
- 📋 Opción para copiar o descargar una nueva lista solo con los enlaces activos
- 🧠 No requiere backend ni instalación de dependencias

---

## 📦 Cómo usarlo

1. Clona este repositorio o descarga los archivos.
2. Abre `index.html` en tu navegador.
3. Sube tu archivo `.m3u` usando la interfaz.
4. Espera mientras se verifica cada enlace.
5. Al finalizar, puedes copiar la nueva lista o descargarla.

---

## 📁 Estructura del Proyecto

```
verificador-m3u/
│
├── index.html         # Página principal
├── style.css          # Estilos
├── script.js          # Lógica de verificación
└── README.md
```

---

## ⚠️ Consideraciones

- Los enlaces se verifican usando peticiones fetch; algunos servidores podrían bloquear CORS.
- Si estás probando localmente y algunos enlaces no responden, prueba subir el proyecto a un servidor o usar `Live Server`.
- Esta herramienta está pensada para fines educativos o de mantenimiento de listas propias.

---

## 📄 Licencia

Distribuido bajo la licencia MIT. Libre de usar, modificar y compartir.

---

## 🙌 Contribuciones

¡Bienvenidas! Si quieres mejorar la funcionalidad, corregir errores o agregar nuevas features, no dudes en abrir un pull request o un issue.
