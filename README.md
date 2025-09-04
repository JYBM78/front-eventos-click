# front-eventos-click
# Proyecto Colaborativo

Bienvenidos al repositorio front del proyecto eventos click.  
A continuación encontrarás las instrucciones para trabajar de forma ordenada con ramas de colaboradores.

El administrador ya creó las ramas de cada colaborador.
Ejemplo:
## Primeros pasos

### 1. Clonar el repositorio
```bash 

git clone https://github.com/JYBM78/front-eventos-click.git

cd front-eventos-click.git
```

### 2. Cambiar a tu rama asignada

El administrador ya creó las ramas de cada colaborador.
Ejemplo:
```bash
git checkout daniela
```
Verifica la rama activa
```bash
git branch
```

## Flujo de trabajo
Hacer cambios
1. Edita o agrega archivos en tu rama.
2. Añade los cambios:
```bash
git add .
```
3. Guarda un commit con descripción clara:
```bash
git commit -m "Descripción del cambio realizado"
```
### Subir cambios a GitHub
```bash
git push origin nombre-de-tu-rama
```

### INTEGRAR CAMBIOS A MASTER

  Cuando termines una funcionalidad:

1. Sube tu rama (git push origin nombre-de-tu-rama).
2. Ve a GitHub y abre un Pull Request (PR) hacia master.
3. El administrador revisará y aprobará la integración.

### Flujo de ramas recomendado

1. master → siempre estable. Solo recibe cambios probados.
2. dev → rama de integración. Aquí se juntan los cambios de todos antes de pasar a master.
3. ramas personales (daniela, camilo, yovany) → donde cada uno desarrolla.

### Reglas básicas

- No trabajar directamente en main.
- Cada colaborador usa solo su rama asignada.
- Los PR se revisan antes de integrar en master.

## Commits claros y cortos:

feat: agregar formulario de registro
fix: corregir validación de correo
cambios varios

- Subir cambios con frecuencia, no dejes acumular demasiados.
- Mantener el repo actualizado antes de empezar a trabajar:
``` bash
git pull origin nombre-de-tu-rama
``` 
