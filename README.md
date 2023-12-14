En este proyecto desarrollamos una aplicación de consola, la cual nos permite realizar operaciones CRUD para manipulación de un Libro

Consideraciones

- Deben tener git instalado en su computador
- Deben configurar sus credenciales

Para clonar el repositorio desde la consola git
git clone https://github.com/VeronicaGuaman/DemoClass1Bootcamp

Una vez descargado, crearse una rama con su nombre, este comando crea la rama y cambia a ella en un solo paso.
git switch -c [Nombre de la rama]

ejemplo
git switch -c VeronicaGuaman

Otra opción es 
git checkout -b VeronicaGuaman


Es importante que se creen la rama a partir de la rama main con cualquier comando mencionados anteriormente y subir sus cambios con la tarea a sus respectivas ramas

Para agregrar los cambios 
git add .
git commit -m "Mensaje del commit"

git push origin [nombre de su rama]
ejemplo
git push -u origin VeronicaGuaman

