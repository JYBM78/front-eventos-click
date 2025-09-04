front-eventos-click
🔹 Descripción
front-eventos-click es un proyecto frontend desarrollado en Angular que sirve como interfaz de usuario para la gestión de eventos artísticos y deportivos. Está diseñado para ser modular, escalable y colaborativo, permitiendo que varios desarrolladores trabajen de forma simultánea mediante ramas en Git.
________________________________________
🔹 Tecnologías
•	Angular (TypeScript)
•	CSS para estilos
•	npm para gestión de dependencias
•	Git + GitHub para control de versiones
________________________________________
🔹 Estructura principal
src/                  # Componentes, estilos y lógica principal
angular.json          # Configuración del workspace Angular
package.json           # Dependencias y scripts npm
package-lock.json      # Bloqueo de versiones de dependencias
README.md             # Documentación y guía de uso
.vscode/              # Configuraciones recomendadas para VSCode
________________________________________
🔹 Ramas configuradas
•	master → versión estable del proyecto
•	dev → integración de nuevas funcionalidades
•	yovany, daniela, camilo → ramas personales de desarrolladores
Cada desarrollador trabaja en su rama personal antes de integrar a dev.
________________________________________
🔹 Primeros pasos para nuevos desarrolladores
1. Clonar el repositorio
git clone https://github.com/JYBM78/front-eventos-click.git
cd front-eventos-click
2. Cambiar a tu rama personal
git checkout tu-rama-personal
git pull origin tu-rama-personal
El administrador ya creó ramas asignadas para cada colaborador (yovany, daniela, camilo).
3. Instalar dependencias
npm install
4. Levantar servidor Angular
npm start
•	La aplicación estará disponible en http://localhost:4200/
•	Se recarga automáticamente al modificar archivos fuente
________________________________________
🔹 Flujo de trabajo recomendado
Se creó una rama para funcionalidades/correcciones
git checkout dev

Hacer cambios y commits claros
git add .
git commit -m "feat: descripción clara del cambio"
•	Usa prefijos como feat: (funcionalidad), fix: (corrección), chore: (tareas varias)
Subir cambios al remoto
git push -u origin nombre-de-tu-rama
________________________________________
🔹 Integrar cambios
Integrar a dev
1.	Abrir Pull Request (PR) desde tu rama personal → dev
2.	Revisar y aprobar cambios
3.	Hacer merge a dev
De dev a master
•	Solo cuando dev esté estable y probada:
git checkout master
git merge dev
git push origin master
master solo contiene versiones estables y listas para producción.
________________________________________
🔹 Buenas prácticas
•	Trabajar siempre en ramas personales, no directamente en master o dev
•	Integrar cambios en dev antes de pasar a master
•	Mantener package-lock.json versionado para consistencia de dependencias
•	Hacer commits claros y frecuentes
•	Mantener el repositorio actualizado antes de empezar a trabajar:
git pull origin tu-rama-personal
•	No subir cambios sin pruebas locales
________________________________________
🔹 Ventajas de este flujo
•	master nunca se rompe
•	Cada persona trabaja en su rama sin bloquear a los demás
•	dev permite integración y pruebas antes de pasar a producción
________________________________________
🔹 Recursos adicionales
•	Angular CLI Overview y referencia de comandos
•	Documentación oficial de Angular
