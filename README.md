<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Lab 1 CVDS</h3>
</div>

<!-- ABOUT THE PROJECT -->
# Parte 1
## Individual

  1. Crea un repositorio localmente.

  2. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

  3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

     git add <archivo>: Agrega un archivo específico al área de preparación (staging area).
          •	Ejemplo: git add main.java
     git add .: Agrega todos los archivos modificados y nuevos al área de preparación.
     git commit -m "mensaje": Crea un commit con los archivos agregados y un mensaje descriptivo.


  4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
  
  5. Crea un repositorio en blanco (vacío) e GitHub.
  
  6. Configura el repositorio local con el repositorio remoto.
  
  7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto

  8. Configura el correo en git local de manera correcta
 
  9. Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).
 
 # Parte 2
 ## Parejas
 ### Integrantes
 - Emily Noreña Cardozo
 - David Santiago Espinosa Rojas

  1. Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.
     
     Propietario: David - Colaborador: Emily

  2. El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1

  3. El owner le comparte la url via Teams al colaborador

  4. El colaborador acepta la invitación al repositorio

  5. Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.
  
  6. ¿Que sucedió?

     Al subirlo al tiempo hubo un conflicto en el push que se hizo más tarde, pues al intentar hacer push al archivo los cambios se hacen sobre un archivo no actualizado, es decir no se puede subir una modificación  de un archivo ya modificado.

 8. La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos <<< === y >>> (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

<div align="center">
  <image src="assets/1.png" alt="pantallazo de error">
</div>

 8. Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.
 
 9. Resuelvan el conflicto con IntelliJ si es posible 
<image src="assets/13.png" alt="pantallazo de error">
 <image src="assets/2.png" alt="pantallazo de error">

  # Parte 3
 ## Parejas
 1. ¿Hay una mejor forma de trabajar con git para no tener conflictos?
   
     A traves del sistema de ramas o branches con pull request que tienen una revision exhaustive.

 2. ¿Qué es y como funciona el Pull Request?

     Un Pull Request (PR) es una solicitud para fusionar cambios de una rama a otra dentro de un repositorio de git. PR permite a otros desarrolladores revisar, comentar y aprobar los cambios antes de       fusionarlos     en la rama principal (main o develop).

 3. Creen una rama cada uno y suban sus cambios

  <image src="assets/3.png" alt="ramas">


 4. Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

  <image src="assets/4.png" alt="PR">


 5. Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

### Conclusiones
- Git permite tener un control detallado de los cambios que se realizan a lo largo del tiempo.
- Los comandos git add y git commit son fundamentales para capturar y organizar los cambios.
- Los comandos git push y git pull es posible colaborar en proyectos compartidos y mantener los cambios sincronizados con los de otros miembros del equipo.
- El comando git merge permite integrar de forma estructurada el trabajo de diferentes ramas.

 emily.norena-c@mail.escuelaing.edu.co

 david.espinosa-r@mail.escuelaing.edu.co

 

 
</br>


  
