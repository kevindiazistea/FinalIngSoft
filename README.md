# Examen Final – Kevin Diaz

App en HTML la cual contiene, "Nombre y Apellido", "DNI" y la leyenda “Final Ingeniera del Software”.

##  Ejecucion
Abrir index.html en cualquier navegador.

## Ejecucion con Docker
Para ejecutar debemos descargar el proyecto desde GitHub:

Clonar el repositorio desde GitHub
git clone https://github.com/kevindiazistea/FinalIngSoft.git

Ir a la carpeta del proyecto
cd FinalIngSoft

Construir la imagen de Docker
docker build -t finalkevindiaz .

Ejecutar el contenedor
docker run -p 8080:80 --name FinalKevinDiaz FinalIngSoft

Abrir el navegador en
http://localhost:8080

El mismo nos devolvera, un HTML con los datos indicados anteriormente, Nombre y Apellido, DNI y la leyenda "Final Ingeniera del Software"
