Descarga y descomprime el proyecto
En este chat, busca el archivo backend-taller2-citas.zip que te compartí (el mensaje anterior) y descárgalo. 
Normalmente en tu carpeta Descargas.
Haz doble clic sobre el .zip → Extraer aquí (Windows) o simplemente doble clic (Mac lo descomprime solo). 
Muévelo a un lugar fácil, por ejemplo el Escritorio, en una carpeta llamada backend-taller2-citas.
Verifica que dentro de esa carpeta veas: server.js, package.json, y las carpetas db, routes, middleware, public.

Verifica que tengas Node.js instalado
Abre una terminal y escribe:
node -v
npm -v

<img width="602" height="268" alt="image" src="https://github.com/user-attachments/assets/3b95d993-19df-4f24-91fe-604b8992c213" />

entrar en cmd como administrador y ejecutar.
cd C:\proyecto\backend-taller2-citas  //guardarlo en un lugar que no tenga demasiada carpetas, en este caso lo guarde en disco c

npm install --legacy-peer-deps       // Instala las dependencias
" Espera a que termine (1–2 minutos, verás muchas líneas de texto).
Al final debe decir algo como added 97 packages sin la palabra "error" en rojo."

node server.js                        // ejecuta el servidor.
"[DB] Conexión establecida correctamente: ...
[DB] Usuario de prueba creado -> usuario: "admin" / password: "admin123"
Servidor activo en http://localhost:3000"
