# 🎬 ScreenMatch - Aplicación para ver series

**ScreenMatch** es una aplicación que te permite explorar y gestionar series. Los usuarios pueden buscar contenido, ver detalles y acceder a rankings.

---

## 🚀 Tecnologías utilizadas

🔹 **Backend:** Java, Spring Boot, PostgreSQL
🔹 **Frontend:** HTML, CSS, JavaScript
🔹 **Base de Datos:** PostgreSQL
🔹 **Gestor de Dependencias:** Maven
🔹 **Control de Versiones:** Git y GitHub

---

## 📌 Características principales

✅ Buscar series y episodios mediante API.  
✅ Almacenar información en una base de datos PostgreSQL.  
✅ Filtrar series por categoría y calificaciones.  
✅ Visualizar los resultados en una interfaz web amigable.  
✅ Generar rankings de series y episodios más valorados.  

---

## 📂 Repositorios del Proyecto

🔹 **Backend:** [ScreenMatch-Backend](https://github.com/celeste-work/ScreenMatch-Backend)  
🔹 **Frontend:** [ScreenMatch-Frontend](https://github.com/celeste-work/ScreenMatch-Frontend)  

---

## 🔧 Instalación y Configuración

### 🖥️ Backend
1️⃣ Clonar el repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/ScreenMatch-Backend.git
   ```
2️⃣ Configurar la base de datos PostgreSQL y actualizar el `application.properties`.
3️⃣ Ejecutar el backend con Maven o desde el IDE.

### 🌐 Frontend
1️⃣ Clonar el repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/ScreenMatch-Frontend.git
   ```
2️⃣ Abrir el archivo `index.html` en el navegador o ejecutar con un servidor local (ej. Live Server en VS Code).
3️⃣ Verificar que el frontend se comunique correctamente con el backend.

---

## 🔗 Conexión entre Backend y Frontend

📌 **El frontend realiza peticiones al backend** para obtener los datos de series y películas. Para que funcione correctamente:
- Asegúrate de que el backend esté en ejecución antes de abrir el frontend.
- Si el backend corre en `http://localhost:8080`, actualiza los endpoints en el frontend para apuntar a esa URL.

Ejemplo en el frontend (JavaScript):
```javascript
fetch('http://localhost:8080/series')
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## 📩 Contribuciones
Si deseas mejorar la aplicación, eres bienvenido a contribuir. Solo sigue estos pasos:
1️⃣ Realiza un **fork** del repositorio.
2️⃣ Crea una nueva rama (`feature/nueva-funcionalidad`).
3️⃣ Envía un **pull request** con tus cambios.

---

## 📞 Contacto
Si tienes preguntas o sugerencias, puedes contactarme en [LinkedIn: linkedin.com/in/celeste-dev].

¡Gracias por visitar **ScreenMatch**! 🎥✨

