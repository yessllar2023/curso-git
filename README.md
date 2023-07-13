# Preguntas

1. ¿Qué es Git?
2. ¿Qué es Github?
3. ¿Qué es el staging Area?
4. ¿Qué es un Commit?
5. ¿Qué comando utilizo para agregar archivos preparados al repositorio?
6. ¿Cual es el nombre por defecto de la rama principal de mi proyecto?
7. ¿Qué es un repositorio local?
8. ¿Qué es un repositorio remoto?
9. ¿Por que hacer git --force es una mala practica?
10. ¿Que es un pull request?**
11. ¿Cómo crear una rama?¿e ingresar a ella?**
12. ¿Qué diferencia hay en usar git checkout a git switch para cambiar de rama?
13. ¿Para que sirve git clone y como usarlo?
14. ¿Qué es forkear?

## Respuestas 

1. **Git** es  una herramienta que nos va a permitir crear diferentes versiones del mismo proyecto **en nuestra computadora.**

10. **pull request** es la peticion para integrar cambios de una rama a otra. es una buena practica al trabajar en equipo para no tener conflictos de codigo, mantener una buena comunicacion

11. para crear una rama  lo haces con el comando **git branch** <nombre-rama>.
y para crear e ingresar automaticamente es **git checkout -b** <nombre-rama>. 
para eliminarla es **git branch -D** <nombre-rama>.
para enlistarlas usamos **git branch** al desplegar el listado podemos identificar en cual rama estamos ya que tiene un * y la palabra resaltada en verde. 

13. permite clonar un proyecto ya forkeado o al participar como colaborador copiarlo y luego trabajar en una version propia con el repositorio local de la carpeta creada. asi se usa **git clone** <url del proyecto>

14. **fork** es copiar un proyecto y realizar modificaciones.