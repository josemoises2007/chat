# Asegúrate de estar en el directorio de tu aplicación
cd /ruta/a/tu/aplicacion

# Inicializa un repositorio git si aún no lo has hecho
git init

# Agrega todos los archivos al repositorio
git add .

# Realiza tu primer commit
git commit -m "Primer commit"

# Agrega el origen remoto (reemplaza con tu URL de repositorio)
git remote add origin https://github.com/tu-usuario/chat-app.git

# Sube tu código al repositorio en GitHub
git push -u origin master
